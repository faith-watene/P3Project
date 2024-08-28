# Phase 3 Project

***Business and Data Understanding***

For this project, we will be building a classifier to predict whether a customer will ("soon") stop doing business with SyriaTel,
a telecommunications company. This is a binary classification problem.
Expectedly, the audience here would be the telecom business itself, interested in reducing how much money is lost because of customers
who don't stick around very long. Therefore, we will be looking at any predictable patterns that can help us come to a conclusion.

The data we will use for this project has no null values and has 21 columns containing the information we will require to carry out our analysis. The columns are listed below where we have loaded our data

***Data Modelling and Evaluation***

Our notebook demonstrates an iterative approach to model-building i.e.
It runs and interprets a simple, baseline model for comparison, introduces new models that improve on 
prior models and interprets their results, explicitly justifies model changes based on the results
of prior models and the problem context and describes any improvements found from running new models

Below are the graphs and confusion matrices generated from this process;

https://github.com/faith-watene/P3Project/blob/master/upload1.png

https://github.com/faith-watene/P3Project/blob/master/upload2.png

https://github.com/faith-watene/P3Project/blob/master/upload3.png

https://github.com/faith-watene/P3Project/blob/master/upload4.png

https://github.com/faith-watene/P3Project/blob/master/upload5.png

***Conclusion and Recommendations***

### Conclusion

Based on the analysis of the dataset, we focused on the **`International plan`** and **`Voice mail plan`** columns to identify patterns and characteristics of clients likely to stop using the telecom service. The analysis revealed significant insights into the factors that influence customer churn. 

1. **International Plan**: Customers who have subscribed to the international plan may have different usage patterns compared to those who haven't. We've observed that an international plan can be an indicator of customer churn. Customers might opt for other services or plans that offer better international rates or connectivity, leading to a higher likelihood of stopping the current service.

2. **Voice Mail Plan**: The subscription to a voice mail plan also provides insight into customer behavior. Customers with a voice mail plan might be using less voice services or might be underutilizing the features of their subscription. This could contribute to dissatisfaction.

3. **Model Performance**: The models developed, including Logistic Regression, Random Forest Classifier, Support Vector Machine, and K-Nearest Neighbors, have provided varying levels of accuracy and insights into customer churn. The confusion matrices generated for each model show how well the models can distinguish between customers likely to churn and those likely to stay.

### Recommendations

1. **Targeted Retention Strategies**:
   - **For International Plan Subscribers**: Develop special offers or discounts for customers. This could include offering better rates, exclusive packages,
    or value-added services that cater specifically to their needs.
   - **For Voice Mail Plan Subscribers**: Analyze the usage patterns of customers with voice mail plans to understand if they are fully utilizing the service. Provide tutorials, benefits communication, or incentives to increase the usage of voice mail services.
2. **Customer Education and Engagement**:
   - **Educational Campaigns**: Implement educational campaigns to help customers understand the benefits of their plans and how they can maximize usage. This could reduce the perception of underutilization and increase customer satisfaction.
   - **Feedback Collection**: Collect feedback from customers, especially those who have opted out of the international or voice mail plans, to understand their reasons. This feedback can be invaluable in refining service offerings and preventing churn.

3. **Data-Driven Marketing**:
   - **Predictive Analytics**: Use the models developed to continuously monitor and predict customer churn. Implement a predictive analytics framework to actively identify at-risk customers and engage them with personalized marketing campaigns.
   - **Customized Communication**: Develop personalized communication strategies based on customer data insights, e.g. if a customer is identified as a frequent international caller, present offers that highlight the benefits of staying with the service.

4. **Service Enhancement and Innovation**:
   - **Innovate and Improve**: Continuously come up with ideas that cater customer needs and industry trends, e.g. by updating the international and voice mail plans to include new features, improved rates, or other enhancements that can retain customers.
   - **Competitor Analysis**: Regularly analyze other competitors services to ensure you are caught up in terms of pricing, features and customer experience.

By implementing these recommendations, the telecom service provider can reduce customer churn and increase customer loyalty.
