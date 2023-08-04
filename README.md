# [Aravindh Chandrasekar's Project Portfolio](https://github.com/arvs3k)
## [Project 1: Bank Customer Churn - Project Overview](https://github.com/arvs3k/Customer-churn)
1. Identify and visually represent the factors that contribute to customer churn.
2. Develop a prediction model that can classify if a customer is likely to churn or not.
    * Ideally, choose a model that can also provide a probability of churn, making it easier for customer service to focus on preventing churn among customers with a higher likelihood of leaving.
    * Evaluate and select the most effective model based on its performance. So that customer service can efficiently target efforts to prevent churn.

![image](https://user-images.githubusercontent.com/110792339/230479976-3c97c2f4-4c31-4c1e-a859-e482ef694c03.png)

Based on the results obtained, my primary objective is to accurately predict customers who are likely to churn, so that appropriate measures can be implemented to prevent churn. The recall measure for the positive class (churned customers) is more important to me than the overall accuracy score of the model.

Given that only 20% of the data represents churned customers, achieving a recall higher than this baseline would already be an improvement. However, I aim to achieve the highest possible recall while maintaining a high precision, so that the bank can effectively allocate its resources towards customers identified by the model without wasting resources on false positives.

Upon reviewing the fitted models, it appears that the random forest model performs the best in terms of achieving a balance between recall and precision. With a precision score of 0.88 on the positive class (churned customers) based on the training set, the model correctly identifies 88% of customers predicted to churn, and with a recall score of 0.53 on the positive class, the model is able to highlight 53% of all actual churned customers.

## [Project 2: Netflix Sales Report (Tableau Dashboard) - Project Overview]
![image](https://github.com/arvs3k/arvs3k.github.io/blob/main/Netflix%20Sales%20Dashboard.png)
![Netflix Sales Dashboard](https://github.com/arvs3k/arvs3k.github.io/assets/110792339/54610af8-1c9e-4da4-8af2-7ced7673d031)

## [Project 3: Stress, Anxiety & Depression Prediction - Project Overview](https://github.com/arvs3k/Stress-Anxiety-Depression)
* This research focused on detecting anxiety, depression and stress using the Depression, Anxiety and Stress Scale questionnaire. Data were collected from a total of 39775 participants via data hosted on OpenPsychometrics.org a nonprofit effort to educate the public about psychology and to collect data for psychological research. Their notes on the data collected in the codebook.txt and subsequently classified using five machine learning algorithms – namely Decision Tree, Random Forest Tree, Naïve Bayes, Support Vector Machine and KNN. 
* Engineered features by cleaning different majors, religion, status of people participated in the survey.
* The f1 score measure was added, which helped identify the best accuracy model among the five applied algorithms as the Random Forest classifier. Furthermore, the specificity parameter revealed that the algorithms were also especially sensitive to negative results.

![image](https://user-images.githubusercontent.com/110792339/230479538-9c621a89-4275-4a18-8701-ade0ea86160a.png)

## [Project 4: Global Development Initiative](https://github.com/arvs3k/Global-Development-Initiative)
* This database includes commitment information for over 1.5 million development finance activities funded between 1947 and 2013, covers 96 donors, and includes ODA, OOF flows, Equity Investments, and Export Credits where available.
* Analyzed how donations changed over time between 1947 and 2013.
* Examined how the identity of the donor and recipient is linked to the geographic location of each country.
* Created a visual representation to compare the amount of donations and receipts of each country, with the aim of identifying whether there are any nations that donate significantly more than they receive, or vice versa using R.

![image](https://user-images.githubusercontent.com/110792339/230484527-7a30d519-e67e-4e63-a9a1-e69275d7001f.png)

![image](https://user-images.githubusercontent.com/110792339/230484665-8cd3cd44-2667-4ccc-a479-f235645ff911.png)

![image](https://user-images.githubusercontent.com/110792339/230484744-afe7f082-3f45-4e84-b84e-fde16a31b1d3.png)

Our analysis indicates that the geographical location of a country plays a crucial role in determining whether it is a donor or a recipient of aid. We examined the total amount of donations made over various time periods and found that the highest amount of donations occurred in 1992 for several development projects, such as Rescheduling and Refinancing, Import Support, and Industrial Development. This highlights the significance of time in understanding the flow of aid to different regions.

To gain a better understanding of the distribution of donors and recipients, we created a visualization of the regions and the total amount of money spent and received by each country. Our analysis showed that each country has a unique focus on different areas of development. For instance, the United States places significant emphasis on Air Transport, among other sectors. These findings emphasize the need for tailored approaches to development that take into account the specific priorities and challenges of each region and country.
