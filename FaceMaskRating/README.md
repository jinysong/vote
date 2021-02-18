# Amazon Face Mask Rating Prediction with Neural Network Model

For a demo of the model in action: [link]

This app is built with Streamlit, and deployed on Heroku. You can write a review and/or review title, and it will a prediction rating between 1 and 5.

## Business Case

While researchers continue to learn more about the coronavirus that causes COVID-19, experts believe that wearing a face mask is one of the most effective ways to prevent the spread of the virus. Many places have mandated mask-wearing in public places, along with other safety measures such as social distancing and hand sanitizing.

Worldwide Face Mask Industry Revenue is Expected to Grow US$ 7.24 Billion in 2020 from US$ 2.86 Billion In 2019. Currently, China is the world’s largest producer and exporter of masks. Other hygienic health products also saw a marked increase during this time.

The pandemic not only changed what people buy, it also greatly impacted how people made their purchases. According to KPMG, two-thirds of Canadians increasing their online shopping habits during COVID-19. The primary decision-making factor among Canadian shoppers is their personal and family health and safety.

Amazon has played a central during the coronavirus crisis, delivering goods to people stranded at home by government shelter-in-place orders. The surge in online buying taxed Amazon’s fulfillment centers, which saw unprecedented volumes as homebound customers flooded it with online shopping orders. 

When purchasing online, reviews and ratings from other customers impact purchasing decisions for over 93% of consumers, according to one report. 

With the rise of COVID-19, online retailers saw an unprecedented demand for face masks. Analyzing the reviews and ratings of the many types of face masks product could serve two important business goals. 

First, understanding consumer behavior could lead to better product development. For example, analyzing what differentiates a good face mask from a bad one and what sentiments get a five-star vs one-star rating could lead to better sales and happier customers.

Second, sentiment analysis could be used to recommend specific products based on customer preferences. For example, if a customer complains about 'size', 'fit', or 'large', a different size product could be suggested to the customer. Similarly, if a customer writes about 'breath', 'air', and 'fog', a product with different material could be recommended instead. As we will see later, these keywords do show up in our sample, and they consistently impact the rating and customer satisfaction.

## Machine Learning Application

I created a Neural Network (NN) model that will predict the star rating on a scale of 1 to 5, based on a written review. The training data is scrape from Amazon's product review section, using a selection of different types of face mask products.
