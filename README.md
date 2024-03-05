# NLP_Predict reviews
# Topic objective: 
  + The goal of the project brought by the team is to process natural language customer reviews and then draw conclusions about whether the customer will buy again or encourage future consumers to buy that product. The project helps consumers have an objective view of the products they plan to buy on e-commerce platforms. In addition, the research not only aims to improve consumer experience but also support commercial businesses. e-commerce and fashion brands to improve product quality, customer service and marketing strategies based on consumer opinions.
  + For customers who rate and encourage repeat purchases, it means they are satisfied with both the products and services of the brand, so sellers also need to take care and focus on interacting and maintaining good services for customers. with this customer file to gain brand loyal customers. For customers whose reviews do not recommend repurchasing, suppliers need to find out what problems their products are having and what needs to be improved, then make modifications and provide good service again. best.
  + Therefore, the project the group brings is not just a simple research on product evaluation, but plays an important role in the development of e-commerce and data analysis, bringing great benefits to both consumers and fashion businesses.
# Data set 
  + Consider the dataset, which includes 23,486 rows corresponding to customer reviews and 10 feature variables.
    ![image](https://github.com/MQuynh/NLP/assets/120617972/a0460543-cf07-48c0-94e2-f21084b21627)
  + Data Visualization:
  ![image](https://github.com/MQuynh/NLP/assets/120617972/47f9ba7e-df24-45fb-b142-fe0221a3a562)
  ![image](https://github.com/MQuynh/NLP/assets/120617972/c2a9cc74-3008-44f7-829f-ede276a23cb1)
  ![image](https://github.com/MQuynh/NLP/assets/120617972/1079db51-9da0-4377-b9da-5df1def276c0)
# Setting up a general model 
  + For building the classification model, the team set the target variable as Recommended IND to find a model that predicts customer review scores based on variables collected about reviews and shoppers. Methods used include Naive Bayes, Decision Tree, Logistic Regression and LSTM. Use the points: Accuracy score, Precision, Recall, F1 Score and Support to calculate the accuracy of each model and the charts: Model Accuracy, Confusion Matrices and Contrastive Loss to compare.
    ![image](https://github.com/MQuynh/NLP/assets/120617972/a46f668a-ffcc-4a02-92f1-102edebecbd2)
    ![image](https://github.com/MQuynh/NLP/assets/120617972/6c12b715-df41-4c77-816f-65a0974c8292)
# User interface
- INTERFACE USER INSTRUCTIONS
  + Enter the rating in the Input box
    ![image](https://github.com/MQuynh/NLP/assets/120617972/b8055406-384e-47ac-8428-e8c508f51c18)
  + Select Button “Predict” to predict
    ![image](https://github.com/MQuynh/NLP/assets/120617972/b9a1058a-2f1a-4285-97a4-b681e1934897)
  + The results are returned in the Output box
    ![image](https://github.com/MQuynh/NLP/assets/120617972/2b474eaf-33ee-414c-8c72-863142507c86)
  + To finish the prediction process, select Button "End".
    ![image](https://github.com/MQuynh/NLP/assets/120617972/87f1a48f-abb9-4241-bd05-7381c07414cd)
- INTERFACE RESULTS RETURNED
  + For “Recommended” results – recommended purchase
    ![image](https://github.com/MQuynh/NLP/assets/120617972/6145bdfa-6b9f-4247-85ae-24a1a52ba37e)
  + For “No Recommended” – do not recommend purchasing
    ![image](https://github.com/MQuynh/NLP/assets/120617972/04154736-74b6-4486-adde-d49cd5d03a7b)
  + For users who have not entered a review but have pressed “Predict”
    ![image](https://github.com/MQuynh/NLP/assets/120617972/ce783ab3-8a67-43fd-b057-c993f3280bdf)







