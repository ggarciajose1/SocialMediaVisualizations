# SocialMediaVisualizations
Class project of MGT 4250 Fall 2023 at Elon University

This project aims to analyze two separate datasets containing information about Android and iOS mobile applications. The goal is to identify trends and characteristics that contribute to userattraction for each platform. By examining factors such as app category, ratings, reviews, and other relevant features, we seek to provide actionable insights for developers and marketers to enhance app visibility and user engagement.

## Questions & Significance 
1) What is the distribution of user ratings and reviews for different Android app categories?
  -  This question will help us understand the user sentiment towards different types of apps on both platforms. It will also reveal which categories tend to receive higher ratings andmore reviews, indicating higher user engagement. It is important to understand the distribution of user ratings and reviews across app categories is crucial for developers and marketers. Positive reviews and high ratings significantly impact app visibility and trust among potential users. Research has shown that higher ratings lead to increased downloads and user retention.
[Reference source](https://www.alchemer.com/resources/blog/differences-between-ios-and-android-app-ratings-and-reviews/)
2) Is there a correlation between app/category and score rating?
  - This question will help us determine if higher download counts are associated with better user ratings. It can provide insights into the relationship between app popularity and user satisfaction. Investigating the correlation between downloads and user ratings is essential for developers. It helps them determine if increasing downloads directly translates to higher user satisfaction.
[Reference Source](https://www.businessofapps.com/insights/ratings-reviews-affect-consumer-decision-download-apps/)
3) Is there is any correlation between the various ratings and the device being an Android or iOS product?
  - This question will help us determine if there is any correlation with ratings depending on the device product being an android or iOS device.  Identifying app categories with the highest user engagement provides valuable insights for developers and marketers looking to target specific demographics or optimize their app offerings. It allows for more targeted marketing efforts and can lead to increased user acquisition and retention.
[Reference Source](https://www.businessofapps.com/data/most-popular-apps/ )

## Data Discription & Upload
Kaggle: 🤖Android vs iOS🍎 Device Benchmarks📊 
  - [Source](https://www.kaggle.com/datasets/alanjo/android-vs-ios-devices-crossplatform-benchmarks/)
  - We were able to find a CSV file dataset on Kaggle that breaks down Android versus iOS device benchmarks into different columns including CPU, GPU, Memory, User Experience and total ratings.

Kaggle: Top 20 Play Store App Reviews (Daily Update) 
  - [Source](https://www.kaggle.com/datasets/odins0n/top-20-play-store-app-reviews-daily-update)
  - The second data set is a CSV file containing app reviews of the top twenty Google Play apps. The columns of this data include: app name, the content of the review, the review ID, and the score for each review. We used the groups function in Tableau in order to group the apps by the category they fit into.
  - These are the sources from the Kaggle website that we used for our analysis. To access them, click the link and it will take you to the Kaggle websiite. From there, hit the download button and upload these data sets into Tableau in order to create visualizations from their data.

## Interpreting Visualizations
Average Score Bar Chart link to visualization
This first bar chart shows the average score for each of the twenty apps. We used the app names to color the chart as well, to make it more visually appealing.

Average Score by Category link to visualization
The second chart shows the average score by app category. We used a tree map so the size of the sections could be a nice indicator for the score that each category received.

Android vs. iOS Ratings link to visualization
The third chart shows the average CPU, GPU, and total score ratings for different Android and iOS devices. We are able to filter through devices by selecting and deselecting from the provided list. 
Simply by looking at the total scores for the different devices, one can see that the different iPhone (iOS) devices have a comparably higher score than the android devices. From the List provided, the iPhone 13s are performing at a rather impressive rate compared to the other devices. 
This chart displays the the correlation between CPU, GPU and total score ratings for different devices. Someone can scroll over the graph to see the average score number as well as select/deselect different devices from the provided list. Overall, this chart showed us that different decives performed better than others especially when looking at the total score for performance. 

## Discussion & Summary
[Article Source](https://onlinelibrary.wiley.com/doi/epdf/10.1002/smr.2316)
The article delves into the relationship between user-reported issues, app ratings, and code quality indicators in the context of mobile app development. It aims to understand how specific types of user feedback are associated with app ratings and whether there is a connection between code quality metrics and critical issues. The study discusses its findings and acknowledges potential threats to the validity of the results. The importance of comprehending user-oriented metrics and code quality in app development is underscored. Various aspects of app development and evolution are explored, including app review classification, change request recommendations, and an examination of mobile app store rating systems. The article also investigates factors influencing the quality of mobile applications and methods for evaluating defects and predicting energy consumption. Much like the research we did for our analyzations, the article took into consideration different ratings to create their conclusions. 

## Conversation with ChatGPT 4
We put our questions into ChatGPT 4 to see if the AI could give us more information regarding our research. Here are the responses we recieved:

What is the distribution of user ratings and reviews for different Android app categories?

As an AI, I don't have real-time access to databases or the ability to pull up-to-date statistics. However, I can tell you generally how you might go about finding this information. You would need to access a dataset that includes Android app categories, user ratings, and reviews. This data could potentially be obtained from the Google Play Store, where each app has a category, user rating, and user reviews. Once you have this data, you could use statistical analysis or data visualization tools to analyze the distribution of user ratings and reviews for different app categories. For example, you might find that games have a wider distribution of ratings than productivity apps, or that social media apps have more reviews than other categories. Please note that the distribution of user ratings and reviews can change over time and may be influenced by many factors, such as changes in app quality, user base, and market trends. Therefore, it's important to use up-to-date data and consider the context when analyzing this information.
Is there a correlation between app category and score rating?

As an AI, I don't have the ability to directly analyze data. However, I can tell you that in general, there could be a correlation between app category and score rating. For example, certain categories of apps might generally have higher ratings because they meet user needs more effectively, or because they attract a user base that is more likely to leave positive reviews. To determine if there is a correlation in your specific case, you would need to conduct a statistical analysis. This could involve calculating the correlation coefficient between app category (converted to numerical form, perhaps through one-hot encoding) and score rating, or conducting a hypothesis test to determine if the difference in average score rating between categories is statistically significant. Remember that correlation does not imply causation - even if there is a correlation between app category and score rating, it doesn't necessarily mean that the category of the app causes it to have a certain rating. There could be other factors at play.
Is there any correlation between the various ratings and the device being an Android or iOS product?

As an AI, I don't have real-time data or the ability to analyze specific datasets. However, I can tell you that the correlation between ratings and the device being an Android or iOS product can depend on various factors. These can include the specific app or service being rated, the user experience on each platform, the demographic of users, and more. For example, if an app is better optimized for iOS, it may receive higher ratings on Apple's App Store compared to Google Play Store, and vice versa. To determine if there's a correlation, you would need to conduct a statistical analysis on a dataset that includes ratings and device information. This could involve techniques like correlation coefficients, cross-tabulation, or regression analysis. Remember that correlation does not imply causation. Even if there's a correlation between ratings and the device being an Android or iOS product, it doesn't necessarily mean one causes the other. Other factors could be influencing the ratings.

## Conclusion:
Overall, the AI's answers were helpful in leading us in new directions for our analysis. The information we received from the Chatbot was considerably vague, since it didn't have the data sets to work with. It could only give us general answers to the questions instead of more in depth analysis about app ratings and user satisfaction. If we could put in all of the data from the Kaggle sets, then the machine could've analysed the data and given us more attuned responses.
