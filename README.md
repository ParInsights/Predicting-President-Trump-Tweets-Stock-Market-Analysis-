# An Analysis and Prediction Model of President Trumps Tweets:


[A Full Final Write Up Can Be Found Here](https://github.com/ParInsights/Predicting-President-Trump-Tweets-Stock-Market-Analysis-/blob/master/WriteUp_Presidential_Tweet_Analysis_Project%20.pdf)

## Introduction
President Trump is changing the political landscape by using his tweets to talk directly to the American people1 in an attempt to move his policy agenda. By using Twitter, he is changing the discussion for Congress, the Judiciary, the media, and his own administration. This change has implications for policy based on the significant reactions to these tweets by both politicians and Federal employees (Graham, 2019).7 Sentiment analysis2 and natural language processing can help assess the potential impact of how these words(tweets) shape policy by his administrators, as well as the impact on his favorability ratings for re-election.
Natural language processing (NLP) is a methodology that allows researchers to analyze the sentence and language-related data using computational techniques to determine specific outcomes. NLP has a wide variety of uses, for example, it is used to predict words and texts on mobile phone messaging apps. It is also used to translate web pages and help users when conducting online searches. Within NLP, we specifically chose to use a tool called sentiment analysis, or opinion mining. It is the automated process of identifying and extracting the subjective information that underlies a text. This can be either an opinion, a judgment, or a feeling about a topic or subject. The most common type of sentiment analysis is called ‘polarity detection’ and consists of classifying a statement as ‘positive’, ‘negative’ or ‘neutral’ (MonkeyLearn, 2020).9
This project will evaluate Trump’s tweets and determine trending using current data science techniques including NLP, Word Clouds and Sentiment analysis (IEE Explore, 2018).8 In addition, we will also use the Trump approval rating, as measured by various polls, as an additional variable for comparison (trump-approval-ratings, 2020)

## Recommendations
Tweeting at critical times does impact policy and forces administrators to respond to the “tweet crisis” as demonstrated in 3 specific cases. (Border Security, Impeachment, AmericaFirst-TPP) Polling data shows that there are trends in tweeting and retweeting data that affect polling senti- ment. This is seen in the data the week after either a high negative or high positive tweet.
For our model we chose the cosine model. This allows us to group similar tweets into categories to see if there is behavior before and after a policy change that influence the policy. Our three examples are: Impeachment, Trans Pacific Partnership and Border Security.
Presidential re-electability (PRE) based on tweets needs a different data set than is currently captured. We define the PRE using the polling data and can see the trends but to predict PRE need to map the policies that are being affected in order to predict PRE. We would need additional polls on economy, tax reform and other polls to truly determine PRE.
We believe that his tweeting (related to the market) does not largely affect his approval or disapproval rating.


## Specification
Our hypothesis states that Trump’s tweets impact voters’ perception of him and impact his chances for electability. We will measure this by analyzing data collected concerning his tweeting behavior and compare it with polling data in an attempt to find a correlative relationship. In addition to the primary hypothesis, we will also attempt to find correlation between tweeting behavior and stock market fluctuations.
1. Can we produce a best guess estimate for the re-election of a sitting president based on the Tweet sentiments?
2. Does the positive or negative tone of the tweets have an impact on his favorability based on consecutive poll data?
3. Does a specific word use have an impact on his poll ratings or the stock market?
4. From our models, are we able to compare successful outcomes to unsuccessful outcomes to see if the language between the two was consistent?
5. We can also use the same method in analyzing a drop-in poll’s. 2

6. Is there a pattern of tweet habits? Often times with social media postings, there are specific “best times” to posts for highest visibility. Does President Trump’s tweets follow or not follow these recommendations?

## 4 Observation
 ### 4.1 The Data
####  4.1.1 Tweet Data
The tweet data used in this paper was an open source dataset provided by TrumpTwitterArchive.5 The dataset consisted of every tweet when from President Trump’s official Twitter account form 1/1/2017 to 3/7/2020 ( ̃16,000 rows). Each row represents a single tweet and contained the following features.
Since the majority of our analysis centers around the sentiment of Trump’s tweeting we need a way to score each tweet in this regard. To do this analysis we used both polarity and sentiment analysis. We also used the Cosine model.
#### 4.1.2 Polling Data
The polling data used was provided by the fivethirtyeight6 project. 4.1.3 Stock Market Data
The stock market data used was provided by Kaggle10 and Yahoo11

## Analysis
We used 3 analysis techniques. Polarity (sentiment), Cosine and NLP. Polarity analysis is an efficient method that helps to understand how President Trump reaches out to his followers, the community, and the public. This analysis revolutionized the freedom of speech, the feelings and opinions of the individual into a specific topic. The data show that the majority of the people are consistent in their polls, despite the language. Overall the positive sentiment of the tweets has increased over the years.

The Cosine model was used to evaluate the consistency in tone and the language of the tweets to determine what President Trump wanted in policy and if the policy was subsequently implemented. This model calculated angle distance to generate comparable word weights that were used to grade similar tweet language. The model output was based on a single date of significance and generated the top five tweets that had the highest score in comparison to the words of the original tweet.
In the first model output on Border Security, the date was 27 January 2017, a time when Border Security was an issue for Trump. Subsequently, the Homeland Security Director, Kirstjen Michele Nielsen ”resigned” after Trump took issue to the general weakness of the border and reflected a critical tone in his tweet on 27 January 2017. The model also generated five comparable tweets on border security and policy intent on 19 July 2017, 3 March 2017, 25 November2018, and 4 June 2018. The policy direction of these comparable tweets were also respectively implemented as tariffs were officially enacted with China and the US ended participation in the TPP. The tone of his policy is therefore consistently defined in his tweet language and clearly results in direct action within his administration.

In the second example, a date within the Impeachment Trial of 24 Sept 2019 was chosen to further analyze the tweet language compared to the policy outcome. The model in this case returned language that consistently showed just how much the President played to his base and not to the overall public, to include Democrats, in these tweets. Instead he used tweets to encourage pressure from his base on Lawmakers as a resource of direct support in enacting preferable policy. Furthermore, on 7 February 2020, Trump used a tweet against Mitt Romney as a Senator who voted to impeach the President. The language is repetitive on 14 February 2020, along with a re-tweet of a supporter also against Mitt Romney. This language is once again a clear use of Twitter language to influence a desired outcome by encouraging public pressure from supporters.
