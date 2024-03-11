# Restaurant clustering using k-means and Sentiment Analysis

In the dynamic landscape of the Indian restaurant industry, Zomato, a prominent restaurant aggregator and food delivery platform, has accumulated a vast dataset reflecting the diverse culinary experiences across different cities. The challenge lies in extracting meaningful insights from this rich dataset to benefit both customers and the company itself.

## 1. Customer Sentiment Analysis

The project aims to delve into the sentiments expressed by customers in their reviews. By employing sentiment analysis techniques, we intend to gauge the overall satisfaction levels of customers with the restaurants listed on Zomato. This analysis will provide actionable insights into the strengths and weaknesses of different establishments, aiding both potential diners in making informed choices and Zomato in enhancing its user experience.

## 2. Restaurant Clustering

Another critical aspect of the project involves clustering Zomato's vast restaurant database. By employing appropriate clustering algorithms, we aim to group restaurants with similar characteristics, such as cuisine types, pricing, and user ratings. This segmentation will not only facilitate an organized understanding of the restaurant landscape but also empower Zomato with strategic information to address specific business challenges.

## 3. Business Case Solutions

The insights generated from customer sentiment analysis and restaurant clustering will contribute to solving several business cases. For customers, it will assist in locating the best restaurants in their locality based on peer reviews. Simultaneously, for Zomato, the analysis will pinpoint areas of improvement and growth opportunities, allowing the company to refine its services and cater to evolving customer preferences.

# Insights from Sentiment Analysis
- ![sentiment-analysis-postive](https://raw.githubusercontent.com/pvanand07/Zomato_Restaurant_Clustering_Unsupervised_ML/master/output-images/sentiment-analysis-positive.png)
- ![sentiment-analysis-negative](https://raw.githubusercontent.com/pvanand07/Zomato_Restaurant_Clustering_Unsupervised_ML/master/output-images/sentiment-analysis-negative.png)

 Insights about potential impact on business:

1. **Chicken as a High-Risk Item**: While chicken has a relatively high positive sentiment, it has a disproportionately high negative sentiment compared to its positive score. This suggests that chicken dishes are crucial to get right, as they can significantly impact customer sentiment.

2. **Consistency in Service**: Service has a high positive sentiment, but also a notable negative sentiment. Consistent service quality could be a determining factor in overall customer satisfaction.

3. **Experience and Taste**: These are areas with substantial positive sentiment but also notable negative sentiment. This indicates that while good experiences and taste are praised, bad ones leave a strong negative impression on customers.

4. **Quality Over Speed and Accuracy**: Quality has a high positive sentiment and a relatively lower negative sentiment compared to order and time. This implies that customers value the quality of their food over the efficiency of service

5. **Value for Money**: Money has a low positive sentiment and a negative sentiment, which suggests that the perception of value for money is a concern for customers.

6. **Operational Aspects**: The negative sentiments for 'order', 'delivery', and 'time' are lower than for 'food', 'chicken', and 'place', but are still significant. This could indicate that operational efficiency in order processing and delivery is an area for improvement.

7. **Staff Interaction**: Staff have higher positive sentiment and comparatively lower negative sentiment. This suggests that good staff interactions can greatly enhance the customer experience, but poor interactions have less impact on negative sentiment compared to food quality or place.
   
# Insights from Clustering Analysis

- ![Scatterplot of Cost vs Average Ratings with Top 3 Cuisines Labeled](https://raw.githubusercontent.com/pvanand07/Zomato_Restaurant_Clustering_Unsupervised_ML/master/output-images/Scatterplot-cuisines-Labeled.png)
- ![Cuisine Distribution Across Clusters](https://raw.githubusercontent.com/pvanand07/Zomato_Restaurant_Clustering_Unsupervised_ML/master/output-images/cuisine-distribution.png)

- ## Cluster Analysis
- Cluster 1 has low cost and, a high ratio of ratings to cost. This cluster has a variety of cuisines, such as desserts, continental, biryani, and Chinese, which may indicate that these restaurants **offer a good balance of quality, price, and diversity**.

- Cluster 2 has the highest average cost and ratings, indicating that it consists of high-end restaurants that offer premium quality and service. The cuisine of this cluster is mainly Italian and Asian, suggesting that these are **popular and profitable choices for upscale dining**.

- Cluster 5 has the second highest average ratings, but a lower cost than cluster 2. This cluster has a large proportion of Asian restaurants, indicating that this **cuisine is well-liked and affordable by the customers**. This cluster also has some continental and Chinese restaurants, which may appeal to a diverse range of tastes and preferences.

- Cluster 4 has the lowest average ratings, but a moderate cost. This cluster is dominated by biryani and Chinese restaurants, which may indicate that these cuisines are oversaturated or underperforming in the market. **The low ratings may also reflect the quality, service, or hygiene issues of these restaurants.**

- Cluster 6 has the lowest average cost, but also low ratings. This cluster consists mostly of fast food restaurants, which may cater to the budget-conscious or time-pressed customers. However, **the low ratings may suggest that these restaurants do not offer much value or satisfaction to the customers.**

- Cluster 0 and 3 have similar costs and ratings, but different cuisines. Cluster 0 has mostly north Indian and Chinese restaurants, while cluster 3 has mostly south Indian and continental restaurants. **These clusters may reflect the regional and cultural preferences of the customers, as well as the availability and competition of these cuisines in the market.**



# **Summary of Business Case Solutions Based on Insights:**

1. **Optimizing Food and Place Experiences:**
   - Invest in improving the quality and ambiance of restaurants, focusing on addressing the high negative sentiment associated with food and place.

2. **Strategic Approach to Chicken Dishes:**
   - Implement a detailed review and improvement strategy specifically for chicken dishes, given their high impact on both positive and negative sentiments.

3. **Prioritizing Consistent Service Quality:**
   - Develop and implement training programs for staff to ensure consistent service quality, considering its influence on overall customer satisfaction.

4. **Balancing Experience and Taste:**
   - Conduct regular quality checks to maintain positive sentiments related to experience and taste, mitigating the negative impact of occasional lapses.

5. **Emphasizing Quality Over Speed and Accuracy:**
   - Adjust operational priorities to prioritize food quality over speed and accuracy, aligning with customer preferences.

6. **Addressing Value for Money Concerns:**
   - Review pricing strategies to align with customer expectations and communicate value-added services to address the negative sentiment associated with money.

7. **Strategic Approach to Cluster Insights:**
   - Provide insights to restaurants based on their cluster categorization, enabling them to tailor strategies for improvement or expansion.

8. **Encouraging Diversity in Cuisine Offerings:**
   - Encourage restaurants to diversify their cuisine offerings based on cluster insights to meet varied customer preferences.

These specific business case solutions derived from the insights aim to guide Zomato and its partner restaurants in addressing key areas of improvement, optimizing customer satisfaction, and fostering sustainable business growth.
