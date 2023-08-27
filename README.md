

                                                                                                    Credit Card Usage Patterns in India: A Detailed Analysis

                                                                                                    Why decide to work with this dataset?
I decided to work with this dataset because I have observed that in India, the issue of unreported income (black money) has been increasing over time. Both my parents are government servants in high-ranking positions, and through their experiences, I have come to understand how hidden financial transactions play a significant role in the country's economy. However, my perspective on this changed after I moved to the USA.

India has introduced various measures to combat money laundering and the circulation of black money, including two instances of demonetization in 2016 and 2023. These actions were taken to address concerns about tax evasion and its impact on the central bank's reserves and the well-being of the less privileged. In my opinion, if India aims to adopt this trend, it should focus on promoting the use of credit cards and consider adopting a "social credit system."

Implementing such changes won't be simple, as they require a shift in people's mindset. To start, we need to grasp the fundamental aspects of credit card usage. Despite the government's efforts to promote credit cards in 2016, they were met with resistance due to negative perceptions among the Indian population. Even in my parents' case, their traditional beliefs make it difficult to change their views.

Breaking these traditional mindsets is the biggest challenge. If we succeed in addressing this root issue, the government might introduce a social credit system. This will undoubtedly be a complex process, but by educating and encouraging people, we can work towards reducing the prevalence of hidden financial dealings and fostering a more transparent economic environment.

                                                                                                         Introduction
This report delves into the patterns of credit card usage in India, aiming to shed light on how people in the country are using credit cards, what they are spending, and the potential impact on the economy. The unique challenges posed by unreported income and the adoption of credit cards are discussed, along with insights into how credit card usage might shape India's financial landscape.

In these datasets we are having following variables:
•	City: Transaction location
•	Date: Transaction date (Includes ‘Day-Month-Year’ (It’s a Indian way to write)
•	Card Type: Credit card category (Gold, platinum, signature, silver)
•	Exp Type: Expense category (bills, beauty, etc.)
•	Gender: Cardholder's gender (male & female)
•	Amount: Transaction amount

                                                                                                      Business Question
Imagine this situation: I am a Senior Data Analyst with 5 years of experience in the finance department. The government wants to decrease the use of undisclosed money and make transactions clearer. For this goal, they want to examine patterns and trends from previous years. 

                                                                                                              Insights and Key Questions
India has currently a 1.408 billion population, upon on that according to the data the average money spent is Rs.156,412. Given the number of people who used credit cards (26,053) and the total amount spent (₹4,074,833,373), we can calculate the average amount spent per person and then analyze the distribution in terms of the percentage of the population that used credit cards and the remaining percentage that did not.

•	Average Amount Spent per Person = Total Amount Spent / Number of People
•	Average Amount Spent per Person = ₹4,074,833,373 / 26,053
•	Percentage of Population Using Credit Cards = (Number of People Using Credit Cards / Total Population) * 100
•	Percentage of Population Not Using Credit Cards = 100 – Percentage of Population Using Credit Cards

Let’s calculate,
 Average Amount Spent per Person ≈ ₹156,209.62 (rounded to two decimal places)
Percentage of Population Using Credit Cards ≈ (26,053 / 1,408,000,000) * 100 ≈ 0.00185% 
Percentage of Population Not Using Credit Cards ≈ 100 – 0.00185% ≈ 99.99815% 

The information tells us that a very small proportion of the population, approximately 0.00185%, is currently using credit cards, which is indeed a very low percentage considering the total population of 1.408 billion. This indicates that the utilization of credit cards is relatively limited within the population.

                                                                                                     Key questions & Answers
1.	Who is Using Credit Cards?
We discovered that a very tiny portion (about 0.00185%) of India's population presently uses credit cards. This suggests that credit card use isn't common

2.	Gender Differences
Interestingly, women are using credit cards for more expenditures compared to men. This highlight changing spending tendencies and greater financial self-reliance among females.

3.	Preferred Card Types
Distinct income groups prefer specific credit card types. For instance, those with higher incomes lean towards premium cards, while individuals with mid-range incomes choose gold or silver cards.

4.	Regional Variations:
More people in cities like Bangalore, Mumbai, Delhi, and Ahmedabad use credit cards. We also have data for New Mumbai and Old Delhi (I didn't separate the data intentionally). As a data analyst, it's important to consider factors like regions and cultural habits. For example, there's a difference between people in Delhi and Old Delhi in terms of their thinking and wealth. This matches the economic growth and business in these cities.

5.	Spending Categories:
People are spending the most on food, fuel, and groceries using their credit cards. This could be attributed to changing lifestyles and increased urbanization.

6.	Transaction Patterns:
We noticed a trend of increased credit card usage around salary disbursement days, indicating that people might be using these days to pay their credit card bills.

Visualization:
This is our second phase. We've already grasped the data, and now it's time to create visualizations. These visuals will help us spot trends and look for segmentation analysis. Segmentation analysis involves factors like salary and area, which are significant. We're using the data from 2013 to 2015 to uncover these trends


Color pallet: Most of the colors are easy to see for people who have color blindness, especially for those with up to 40% color blindness. 
To show male and female, I used dark pink and dark blue. I chose dark colors for important things, like red.


1.	Male and Female credit card usage ratio
2.	<p>
This dataset indicates that 26,053 individuals are currently using credit cards. Among these users, 47.5% are male, while 52.5% are female. (I recall, Professor, that you mentioned your dislike for pie or donut charts. However, I believe these are the most suitable visualizations for this kind of data.)

 </p>
![image](https://github.com/BASH-EPIC/Tableau_Predictive_model_of_Credit-Card-Spending-Habits-in-India/assets/81670865/a718df4d-ee55-47ac-8ecb-ca046b64bde4)


2.	Distribution of Card Types
In India, credit cards play a significant role in the financial landscape, although their adoption varies across income segments. These visualizations provide valuable insights into the socioeconomic distribution of credit card users. The availability of different types of credit cards, ranging from basic to premium categories, allows individuals to access a variety of benefits and privileges. However, obtaining premium cards, like signature or silver credit cards, often requires a higher income or creditworthiness.
•	Gold Credit Cards: 6,367 users (Mid-range income)
•	Platinum Credit Cards: 6,398 users (Upper-middle to High income)
•	Signature Credit Cards: 6,447 users (High income)
•	Silver Credit Cards: 6,840 users (Mid to Mid-high income)
This summary outlines the distribution of credit card types across different income segments in India, highlighting the preference for specific cards among various income groups.


 ![image](https://github.com/BASH-EPIC/Tableau_Predictive_model_of_Credit-Card-Spending-Habits-in-India/assets/81670865/63400107-8ec5-483c-b68b-44b8968dea66)



3.	City-wise Spending with Credit Cards: Where and How Much?
In this report, we look at how people use credit cards in different cities. We have a chart that shows which cities use credit cards a lot and how much they spend. It's interesting! The cities with the most credit card use is Bangalore (because of IT companies), Mumbai, Delhi, and Ahmedabad. This tells us that Bangalore is a big hub for IT and has lots of young people. Ahmedabad is also important for business and development.

This discovery makes us think that if smaller cities grow, it could be good for India's economy. This approach could make the country's money system stronger and create more jobs, leading to more spending by people.

 ![image](https://github.com/BASH-EPIC/Tableau_Predictive_model_of_Credit-Card-Spending-Habits-in-India/assets/81670865/e4bc8b4c-4f73-4cb4-b8ae-92fc46589bbe)

![image](https://github.com/BASH-EPIC/Tableau_Predictive_model_of_Credit-Card-Spending-Habits-in-India/assets/81670865/72c26bc1-efdd-43b7-8ec1-46e1b76ece22)

4. Money Flow in Different Cities: Exploring Spending in Millions
The graph illustrates the spending habits of people in different cities, with Mumbai, Delhi, and Surat highlighted as the top spenders. The values are given in millions, providing an insight into the economic activity and consumer behavior of these specific cities.
This graph shows the amount of money people in various cities spend, measured in millions. In the data, we see that Mumbai leads with spending of 576.75 million, followed by Delhi with 556.93 million, and Surat with 114.49 million.

 
Divergent Financial Habits: A Glimpse at Delhi vs. Mumbai (from UPPER Graph ONLY)
We can see a big difference between how people handle money in Delhi and Mumbai. Delhi is where politics and culture are important, while Mumbai is all about business and money.
As an Indian citizen, I know that Delhi has a lot of money flowing around. Even though our data might not show if there's black money in Delhi, it's still one of the richest cities in the country. People in Delhi tend to be wealthier, which explains the gap.
And then we have Surat, where spending habits are quite unique. Even though it's known as the "Businessman's City," people in Surat prefer to use cash rather than credit cards. This is interesting because many businesspeople there still like doing things in cash, even when digital options are available.
 ![image](https://github.com/BASH-EPIC/Tableau_Predictive_model_of_Credit-Card-Spending-Habits-in-India/assets/81670865/ab8c9b10-fd8e-433d-b324-c0bbe2719a0c)

5. Money Spent by Men and Women: Surprising Trends
The graph shows how much money both men and women have spent until now. It's quite surprising that women have spent more than men. This year, women have spent a big total of 97,186,563 million rupees, while men have spent 76,506,734 million rupees.
This points to an interesting pattern where women seem to be spending more. This might mean that women's shopping habits are changing. To understand this better, we could investigate what factors are causing this difference. It could give us insights into how culture and society affect spending choices.

![image](https://github.com/BASH-EPIC/Tableau_Predictive_model_of_Credit-Card-Spending-Habits-in-India/assets/81670865/22191b40-0b00-43f3-a1f0-66a7faa08698)


6. Where People Spend on Credit Cards: Male vs. Female Trends
This graph reveals the top spending areas for credit card usage among males and females. Food, fuel, and groceries are the main categories where people spend the most. This could be because in growing cities, people order food due to busy schedules, while fuel costs come from commuting to work. Interestingly, travel expenses are relatively low.
Another interesting finding is the noticeable difference in bill payments between men and women. On average, women pay around 57 million, while men pay 33 million. This suggests that women in India are earning well and managing their expenses independently, which is a positive trend for the country.
Similar patterns can be seen in spending on food and entertainment. When it comes to entertainment and fuel, men tend to spend more

5. Money Spent by Men and Women: Surprising Trends
 
![image](https://github.com/BASH-EPIC/Tableau_Predictive_model_of_Credit-Card-Spending-Habits-in-India/assets/81670865/2a5f32ba-af85-4061-a50b-276064617c90)

 

7.	Analyzing Transaction Patterns: Salary Disbursement Impact:
The data gives us interesting information about how transactions happen. Certain days, like the 26th, 6th, 7th, 15th, and 11th of the month, show the most transactions. It would be good to check if these days are when people get their salaries, which usually happens once a month in India.
The graph suggests that people in the Indian IT sector, especially those working with big US companies, are causing these patterns. The dates we see usually match with when people get paid, especially for IT professionals who often get their salary on these specific dates. I think they might be using these days to pay their credit card bills. This trend seems to be seen mainly in people from private companies

 ![image](https://github.com/BASH-EPIC/Tableau_Predictive_model_of_Credit-Card-Spending-Habits-in-India/assets/81670865/ee4db044-7829-4170-b3d2-9f9d94b71215)


8.	Seeing Trends in Dates, Amounts, and Gender on Tableau ( Forecasting model)
This is the bit technical graph. This visualization helps us understand data better. We made a special range from 60% to 80% of the average and drew an average line. We also put in the dates, amounts of money, and genders on Tableau.
This helps us see if the data points fit in this special range or not. We can see if dates, amounts of money, and genders follow certain patterns or if there are any differences. This can help us find out more about how people spend money, whether there are patterns based on gender, and if the money spent changes over time.

In this graph, when we look at 60% of the average spending, both spending habits went down. One reason could be that there were many holidays and festivals during that time. But, during these days, Indians tend to spend a lot. The graph is really interesting because spending went down and then up again. 

A key point to notice here is that both trends go down together. If one trend goes down, the other does too. This might be because the factors affecting both trends are linked in some way.

Think about it this way: Imagine during holidays, people might spend less because they're saving for celebrations. But then, when the celebrations come, they spend more. So, the two trends might be connected by the holiday season.

![image](https://github.com/BASH-EPIC/Tableau_Predictive_model_of_Credit-Card-Spending-Habits-in-India/assets/81670865/e975a986-165b-4367-83a5-951907e3b5e8)

 

9.	Forecasting credit card transactions

In this analysis, I used the Forecast inbuilt technique within Tableau to predict future credit card transaction amounts. The dataset consisted of years, transactions & gender
Reason for Using Forecasting: The goal was to anticipate upcoming trends in credit card transactions, providing insights that can aid decision-making and planning.
Prediction Mechanism: Tableau's forecasting algorithm analyzes the historical transaction data, and recognizes patterns, seasonality, and trends. It then constructs a mathematical model that captures these patterns. Using this model, Tableau generates forecasted values for future years, extending the observed patterns into the future.

The graphs illustrate actual and predicted credit card usage for both genders over a span of years. The projections for 2015 and 2016 are generated from historical data in 2013 and 2014. The data presents fluctuations in credit card usage between males and females across the specified years.

As we can see the no. are inclined so we'll use simple average increase calculation ( basic math ) so cross chcek the data.
•	2013: Female - 1848 (in thousands), Male - 2079 (in thousands)
•	2014: Female - 7533, Male - 8258
•	2015 Predicted: Female -?, Male – 8286
•	
The calculation for 2015 Female Prediction:
The trend from 2013 to 2014 shows an increase from 1848 to 7533 in female credit card usage. Let's calculate the average increase and apply it to predict 2015.
•	Average Increase = (7533 - 1848) / 2 = 2842.5
•	Predicted 2015 Female Usage = 7533 + Average Increase = 7533 + 2842.5 = 10375.5

The calculation for 2015 Male Prediction:
Using the same approach, we'll calculate the average increase in male usage and apply it to predict 2015.
•	Average Increase = (8258 - 2079) / 2 = 3089.5
•	Predicted 2015 Male Usage = 8258 + Average Increase = 8258 + 3089.5 = 11347.5

So, the predicted credit card usage for 2015 would be approximately:

Female: 10375.5 (in thousands)
Male: 11347.5 (in thousands)
There is still a huge gap in both calculations, probably tableau used different concepts for that.
 
![image](https://github.com/BASH-EPIC/Tableau_Predictive_model_of_Credit-Card-Spending-Habits-in-India/assets/81670865/eb2de6d2-dfc6-4199-9838-6fed86f6d775)

Key Observations:
To help smaller cities and towns develop, more focus should be put there. People tend to move to these places for education and work, which can improve the country's Gross Domestic Product (GDP) and create jobs. Overall, this can help India become more digital and modern.

• People who use credit cards the most are usually from the middle class and wealthier sections of society.
• Individuals working in private companies use credit cards more often, whereas there's not enough data about government officials' credit card use. This suggests that credit cards are mainly popular among those who work in private firms.
• People don't seem to spend a lot on travel. Offering attractive travel deals could encourage more spending in this area.
• The data also shows that more credit card users are in well-developed cities. This shows a link between credit card use and urban growth, meaning the government should focus on developing cities comprehensively.



Recommendations:
To gain a deeper understanding, we consider exploring the following aspects:
•	Age groups: How different age groups use credit cards and spend.
•	Occupation types: How profession influences credit card usage.
•	Credit card benefits: What specific card features attract users?
•	City development index: How urbanization impacts credit card adoption.
•	Economic indicators: Correlations between credit card usage and broader economic trends.


My Personal Thoughts:
1.	In 2013, about 1% of the population was using credit cards, which was a decent start. However, during the COVID pandemic, credit card usage declined not because of increased awareness, but due to job loss and education challenges. As people regain employment and access to education, credit card usage seems to be increasing again.
2.	To better understand the data, it's beneficial to compare cities that are economically well-off but spend less, with cities that are still developing but show higher or good credit spending. A close investigation into Delhi's spending patterns is important (although this data would need to come from the government). Analyzing the trends of increased and decreased spending, such as when someone who was spending well suddenly starts spending less, can provide valuable financial insights.
3.	The types of credit cards people use also play a crucial role. They reveal income levels, as each card has specific criteria. In India, people usually have a maximum of 2 to 3 credit cards.
4.	Additionally, we should explore the spending patterns of government officials, even though we don't currently possess evidence of their spending habits.
These insights could offer a comprehensive view of credit card usage, the economy, and the financial behaviors of different segments of the population.

After looking at all the data, I don't believe we can accurately predict a model just yet. To make better predictions, we need to gather more data, like sentiment analysis, geographic information linked to culture, and data about different sectors (private vs. government jobs). Collecting this kind of information will take time, as it's a detailed process.
We also need to remember that in many places in India, people prefer to pay in cash. If they can pay in cash, they often get discounts. This is sometimes used to earn money that's not reported for taxes, which is a way of hiding income. So, we must be cautious and take this into account.
There are more actions like this that we need to keep in mind while doing our analysis. It's a complex situation with many factors to consider.

Conclusion:
This report highlights the evolving credit card usage patterns in India and their potential implications. As credit card adoption increases, it has the potential to shape the financial landscape, foster transparency, and contribute to economic growth. By delving deeper into the data and considering various factors, we can develop strategies that align with this change.

Implications and Future Directions: The findings of this analysis have several implications:
•	Credit card usage is not widely adopted in India, presenting an opportunity for growth.
•	There's a potential for targeted marketing strategies based on income groups and spending patterns.
•	The relationship between credit card usage and economic indicators like GDP growth can be explored further.

References:


1.	PricewaterhouseCoopers. (n.d.). The changing landscape of India’s credit industry. PwC. https://www.pwc.in/industries/financial-services/fintech/dp/the-changing-landscape-of-indias-credit-industry.html



# Tableau_Predictive_model_of_Credit-Card-Spending-Habits-in-India
