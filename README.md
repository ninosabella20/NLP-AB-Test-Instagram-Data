# Analyzing Roger Federer Instagram Posts

This project focuses on determining whether the sentiment of comments, caption sentiment, and the number of likes on Roger Federer's Instagram posts are influenced by whether or not his posts are related to tennis. Using Natural Language Processing (NLP) techniques, real-world data from Federer's Instagram posts were analyzed, and A/B testing was employed to assess any significant differences between tennis-related and non-tennis-related posts.

## Table of Contents
- [Introduction](#introduction)
- [Hypotheses](#hypotheses)
- [Methodology](#methodology)
- [Results](#results)
- [Conclusion](#conclusion)
- [Future Work](#future-work)

## Introduction
The project seeks to determine whether the performance metrics of Roger Federer’s Instagram posts, such as:
- **Comment Sentiment**
- **Caption Sentiment**
- **Likes**

are dependent on whether the content of the post is related to the sport Federer is most famous for: **Tennis**.

## Hypotheses
To assess the significance of tennis-related content on post performance, we formulated the following hypotheses:

- **Null Hypothesis (H0):** There is no significant impact of whether or not the content is tennis-related on post performance metrics.
- **Alternative Hypothesis (H1):** There is a significant impact of whether or not the content is tennis-related on post performance metrics.

## Methodology
1. **Data Collection:**
   - Real Instagram posts from Roger Federer were collected, including captions, comments, and likes.
   
2. **Natural Language Processing:**
   - **Sentiment Analysis** was applied to the comments and captions using an NLP model to quantify the sentiment.
   
3. **Categorization:**
   - Posts were categorized into two groups:
     - Tennis-related content
     - Non-tennis-related content
   
4. **A/B Testing:**
   - A series of A/B tests were conducted to determine if there is a statistically significant difference in performance metrics between the two groups.

5. **Statistical Analysis:**
   - We used p-values to assess the significance of differences between tennis and non-tennis posts. A p-value threshold of 0.05 was used to determine significance.

## Results
The results from the A/B testing showed the following p-values for each performance metric:

- **Likes**: p = 0.07 (7% probability that the population means are the same).
- **Caption Sentiment**: p = 0.18 (18% probability that the population means are the same).
- **Comment Sentiment**: p = 0.76 (76% probability that the population means are the same).

## Conclusion
Based on the results of the A/B tests, there was **not enough statistical evidence** to reject the null hypothesis (H0). 

This means we **could not conclude** that the use of tennis-related content in posts had a statistically significant impact on performance metrics such as likes and sentiment.

- **Likes:** The difference was notable but did not reach statistical significance (p-value of 0.07). However, with more data, the p-value might fall below the 0.05 threshold, suggesting a potential significant difference in likes for tennis vs. non-tennis content.
  
- **Comments:** The least influenced metric, with a p-value of 0.76, suggesting no significant effect of tennis-related content on comment sentiment.

## Future Work
Further research could include:
- Gathering more data to increase the power of the statistical tests.
- Exploring other post metrics such as reach, shares, or engagement rate.
- Refining sentiment analysis by using advanced models that can capture the nuances of sports-related language.
  
By incorporating additional data points, it may be possible to observe statistically significant differences, particularly in terms of likes.
