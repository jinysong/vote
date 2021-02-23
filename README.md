# Vote Participation Prediction with Ensemble Modeling

This project is inspire by the article [Why Many Americans Don't Vote](https://projects.fivethirtyeight.com/non-voters-poll-2020-election/) by Amelia Thomson-DeVeaux, Jasmine Mithani and Laura Bronner on FiveThirtyEight.

## Table of Contents

[Questions Code Book](#codebook)





## Questions Code Book<a name="codebook"/>
Q1. Are you a U.S. citizen?
  1. Yes
  2. No [TERMINATE]

Q2. In your view, how important are each of the following to being a good American? (1. Very important, 2. Somewhat important, 3. Not so important, 4. Not at all important)
  1. Voting in elections
  2. Serving on a jury
  3. Following what happens in government and politics
  4. Displaying the American flag
  5. Participating in the U.S. Census every ten years
  6. Knowing the Pledge of Allegiance
  7. Supporting the military
  8. Respecting the opinions of those who disagree with you
  9. Believing in God
  10. Protesting if you believe government actions are wrong

Q3. How much do you agree or disagree with the following statements? (1. Strongly agree, 2. Somewhat agree, 3. Somewhat disagree, 4. Strongly disagree)
  1. Systemic racism is a problem in the United States.
  2. Systemic racism in policing is a bigger problem than violence and vandalism in protests.
  3. Society as a whole has become too soft and feminine.
  4. The mainstream media is more interested in making money than telling the truth.
  5. Traditional parties and politicians don’t care about people like me.
  6. The way people talk needs to change with the times to be more sensitive to people with different backgrounds.

Q4. How much of an impact, if any, do each of the following have on your life? (1. A significant impact, 2. Somewhat of an impact, 3. Just a slight impact, 4. No impact at all)
  1. Elected officials in Washington, D.C. (e.g. the president, member of Congress)
  2. Elected officials in my state (e.g. governor, state representative)
  3. Elected officials in my city or community (e.g. mayor, city council)
  4. The news media
  5. Large financial institutions on Wall Street
  6. Law enforcement and the legal system

Q5. As far as making progress on the important issues facing the country, does it really matter who wins the 2020 presidential election, or will things be pretty much the same regardless of who is elected president?
  1. Who wins the election really matters
  2. Things will be pretty much the same

Q6. In general, how many of the people in elected office today are like you?
  1. A lot
  2. Some
  3. Only a few
  4. None

Q7. Thinking about the design and structure of American government, which would you say is more in line with your view?

  1. A lot of changes are needed
  2. Changes are not really needed

Q8. How much would you say you trust each of the following? (1. A lot, 2. Some, 3. Not much, 4. Not at all)

  1. The presidency
  2. Congress
  3. The Supreme Court
  4. The Centers for Disease Control (CDC)
  5. Election officials
  6. The intelligence community (e.g. FBI or CIA)
  7. The news media
  8. The police
  9. US Postal Service

Q9. Now, we’re going to describe various types of political systems and ask what you think
about each as a way of governing this country? (1. Very good, 2. Fairly good, 3. Fairly bad, 4. Very bad way of governing the country)

  1. Having a democracy, where politicians are elected
  2. Having experts, not government, make decisions according to what they think is best for the county
  3. Having a strong leader who does not have to work with Congress and elections
  4. Having the army rule

Q10. Do any of the following currently apply to you? (1. Yes, 2. No)

  1. Receiving long-term disability
  2. Have a chronic illness
  3. Been unemployed for more than a year
  4. Have been evicted from your home within the past year

Q11. Since February of 2020, have any of the following things happened to you? (1. Yes, 2. No)

  1. Lost your job, either temporarily or permanently
  2. Tested positive for COVID-19
  3. Had a friend or family member test positive for COVID-19
  4. Had a friend or family member die of COVID-19
  5. Worried about how you would pay for your rent or mortgage, for groceries, or health care expenses
  6. Quit your job to care for a child or family member

Q14. Based on your perceptions and experiences of the Republican Party, which is the most accurate description of the party’s attitude toward people like you?
  1. The Republican Party wants people like me to vote and works hard to earn our votes
  2. The Republican Party wants people like me to vote but does not work hard to earn our votes
  3. The Republican Party does not care whether or not people like me vote
  4. The Republican Party does not want people like me to vote, but does not work hard to keep us from voting
  5. The Republican Party does not want people like me to vote, and works hard to keep us from being able to vote

Q15. Based on your perceptions and experiences of the Democratic Party, which is the most accurate description of the party’s attitude toward people like you?
1. The Democratic Party wants people like me to vote and works hard to earn our votes
2. The Democratic Party wants people like me to vote but does not work hard to earn our votes
3. The Democratic Party does not care whether or not people like me vote
4. The Democratic Party does not want people like me to vote, but does not work hard to keep us from voting
5. The Democratic Party does not want people like me to vote, and works hard to keep us from being able to vote

Q16. In general, how easy or difficult do you think it is to vote in national elections?
  1. Very easy
  2. Somewhat easy
  3. Somewhat difficult
  4. Very difficult

Q17. When thinking about a presidential election, how confident are you that each of these ways of voting are secure and safe from fraud? (1. Very confident, 2. Somewhat confident, 3. Not very confident, 4. Not at all confident)
  1. In-person voting machines
  2. Paper ballots cast in person
  3. Paper ballots submitted by mail
  4. Electronic votes submitted online or by email

Q18. Have you or any members of your household ever experienced the following situations when trying to vote? (1. Yes, 2. No)
  1. Was told they did not have the correct identification
  2. Could not find the polling place
  3. Missed the voter registration deadline
  4. Was unable to physically access the polling place
  5. Could not obtain necessary assistance to fill out a ballot
  6. Had to cast a provisional ballot
  7. Couldn’t get off work to vote when polls were open
  8. Waited in line to vote for more than an hour
  9. Was told name was not on the list even though they were registered
  10. Did not receive absentee or mail-in ballot in time

Q19. Which of the following do you think would get more people to vote in national elections? Please choose all that apply.
  1. More outreach to ordinary Americans from candidates or elected officials
  2. More information about the candidates from unbiased sources
  3. Making Election Day a national holiday
  4. Being automatically registered to vote
  5. Automatically receiving a ballot in the mail
  6. Being able to vote in-person before Election Day
  7. Being able to register and vote on the same day
  8. Being able to vote by phone or online
  9. Having more candidates to choose from
  10. Other [specify] [A]

Q20. Are you currently registered to vote? (1. Yes, 2. No)

Q21. On November 3, 2020 there will be an election for president, members of the United States Senate, House of Representatives, and other state and local offices. Do you plan to vote in the November 2020 election? If you have already voted, please select ‘yes.’ (1. Yes, 2. No, 3. Unsure/Undecided)

Q22. (ASK IF NO IN Q21) You previously indicated that you are not currently registered to vote. Which of the following reasons best describes why you are not currently registered to vote?
  1. I don’t have time to register or vote
  2. I don’t trust the political system to serve my needs
  3. I don’t know how to register
  4. I don’t want to register
  5. I am not eligible to vote [please specify why] [A]
  6. I don’t think my vote matters [A]
  7. Other [SPECIFY] [A]

Q23. Which presidential candidate are you planning to support?
  1. Donald Trump
  2. Joe Biden
  3. Unsure

Q24. Regardless of your current voter registration status and plans to vote (including if you have already voted), what would be your preferred method of voting this year?
  1. Mail-in or absentee ballot
  2. In-person before Election Day
  3. In-person on Election Day
  4. Other [please specify] [A]

Q25. How closely are you following the 2020 presidential race?
  1. Very closely
  2. Somewhat closely
  3. Not very closely
  4. Not closely at all

Q26. Most eligible citizens don’t vote in every national election (the November general elections). In general, which of the following categories do you think best describes you?
  1. I always, or almost always, vote in national elections
  2. I sometimes vote in national elections
  3. I rarely vote in national elections
  4. I don’t vote

Q27. Thinking back to some recent elections, as best you remember, did you vote in the following elections? (Yes, No)
  1. The election for Congress in 2018
  2. The presidential election in 2016
  3. The election for Congress in 2014
  4. The presidential election in 2012
  5. The election for Congress in 2010
  6. The presidential election in 2008

Q28. Thinking back to the last few national elections that you voted in, which of the following were the most important reasons in your decision to vote? Please choose all that apply.
  1. Voting is an important civic duty
  2. I was excited about one of the candidates and wanted to vote for him/her
  3. I disliked one of the candidates and wanted to vote against him/her
  4. I wanted to support the political party I identify with
  5. There was a specific issue I cared about, and one of the candidates was better on that issue
  6. I enjoy voting
  7. Voting is easy
  8. Other [specify] [A]
  
Q29. (IF SOMETIMES VOTE, RARELY VOTE OR DO NOT VOTE IN Q26) Thinking back to the last few national elections where you decided not to vote, which of the following were the most important reasons in your decision not to vote? Please choose all that apply.
  1. I didn’t like any of the candidates
  2. Because of where I live, my vote doesn’t matter
  3. No matter who wins, nothing will change for people like me
  4. Our system is too broken to be fixed by voting
  5. I wanted to vote, but I didn’t have time, couldn’t get off work, something came up, or I forgot
  6. I’m not sure if I can vote
  7. Nobody talks about the issues that are important to me personally
  8. All the candidates are the same
  9. I don’t believe in voting
  10. Other [specify] [A]

Q30. Generally speaking, do you think of yourself as a...Select one answer only.
  1. Republican
  2. Democrat
  3. Independent
  4. Another party, please specify … [O]
  5. No preference

Q31. (ASK IF REPUBLICAN IN Q30) Would you call yourself a...
  1. Strong Republican
  2. Not very strong Republican

Q32. (ASK IF DEMOCRAT IN Q30) Would you call yourself a...
  1. Strong Democrat
  2. Not very strong Democrat
  
Q33. (ASK IF INDEPENDENT, ANOTHER PARTY, HAVE NO PARTY PREFERENCE OR REFUSED IN Q30) Do you think of yourself as closer to the...
  1. Republican Party
  2. Democratic Party

- PPAGE: Age of respondent
- GENDER: Gender of respondent
- EDUC: Highest educational attainment category. Note: Associate’s degree is grouped in “some college.”
- RACE: Race of respondent, census categories. Note: all categories except Hispanic are non-Hispanic.
- INCOME_CAT: Household income category of respondent
- RESPID: Unique respondent ID
- WEIGHT = Weight
- VOTER_CATEGORY:
  - always: respondent voted in all or all-but-one of the elections they were eligible in
  - sporadic: respondent voted in at least two, but fewer than all-but-one of the elections they were eligible in
  - rarely/never: respondent voted in 0 or 1 of the elections they were eligible in
