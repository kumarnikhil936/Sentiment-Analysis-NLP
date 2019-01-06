# Sentiment-Analysis-NLP

Objective: 
“TripAdvisor is the world’s largest travel site where you can compare and book hotels, flights, restaurants etc. 
The data set provided in this challenge consists of a sample of hotel reviews provided by the customers. 
Analyzing customers reviews will help them understand about the hotels listed on their website i.e. 
if they are treating customers well or if they are providing hospitality services as expected.
In this challenge, you have to predict if a customer is happy or not happy.” 

Solution provided uses 2 layer NN implemented in Keras. One might go for a LSTM network for NLP problems which will insure better performance. 
Also, here the model used is Bag of words. If we had used other models like Word2Vec, the results would have been hopefully better. 
This solution achieves ~90% accuracy on training dataset within 10 epochs. 

Dataset description:  https://www.dropbox.com/s/o8jeborvubfs7fn/trip_advisor_hackerearth_data.zip?dl=0
- User_ID :: unique ID of the customer
- Description :: description of the review posted
- Browser_Used :: browser used to post the review
- Device_Used :: device used to post the review
- Is_Response :: target variable

Steps :
- Preprocess data 
- Extract features 
- Build model
- Train model
- Test performance

References: 
https://appliedmachinelearning.blog/2017/12/21/predict-the-happiness-on-tripadvisor-reviews-using-dense-neural-network-with-keras-hackerearth-challenge/

