# MULTI-CLASSIFICATION-REVIEW-OF-CNN-MODELS
Performed multi-classification on a flower dataset (five classes) using 4 different CNN architectures.

TASKS:
Step1: Import all necessary libraries from Tensorflow.Keras like preprocessing, sequential model, Rescaling, Conv2D, Dense, Flatten, MaxPooling2D, Dropout, GlobalAveragePooling2D, etc.

Step2: Start with the first model of CNN that has pooling layers and a dropout layer. We create an object for a sequential model and add conv2D layers of sizes 32, 64, 128, and 256. We also add a dropout layer and finally an output layer with a softmax activation function. Next, compile, fit and save the model. Find testing accuracy. Load the saved model to make predictions if needed.

Step3: Start with the first model of CNN that has pooling layers. We create an object for a sequential model and add conv2D layers of sizes 32, 64, 128, and 256. Here we don’t add a dropout layer and finally, add an output layer with a softmax activation function. Next, compile, fit and save the model. Find testing accuracy. Load the saved model to make predictions if needed. 

Step4: Start with the first model of CNN that has pooling layers. We create an object for a sequential model and add conv2D layers of sizes 32, 64, 128, and 256. We change the image size from (100,1 00) to (125, 125). We don’t add a dropout layer and finally, add an output layer with a softmax activation function. Next, compile, fit and save the model. Find testing accuracy. Load the saved model to make predictions if needed.

Step5: Start with the first model of CNN that has pooling layers. We create an object for a sequential model and add conv2D layers of sizes 32, 64, 128, and 256. We change the filter size from (3, 3) to (5, 5). We don’t add a dropout layer and finally, add an output layer with a softmax activation function. Next, compile, fit and save the model. Find testing accuracy. Load the saved model to make predictions if needed.

Step6: Print the max testing accuracy to get the best model of all

Step7: Store 10 images of flowers and get predictions of all 10 flowers with the best CNN model.

![image](https://user-images.githubusercontent.com/54590466/234067897-ea71f51d-9e65-4d97-906f-643c69294344.png)


![image](https://user-images.githubusercontent.com/54590466/234067911-2c7ccc8a-11ef-4de6-915e-eb4caa0fb206.png)


![image](https://user-images.githubusercontent.com/54590466/234067931-50303c1a-bacd-439f-8999-c33db9d0282a.png)


![image](https://user-images.githubusercontent.com/54590466/234067993-45723bc6-c012-468a-9fc7-69ad01c089be.png)


![image](https://user-images.githubusercontent.com/54590466/234068159-bda513ae-8358-4e94-bcb9-445221c3bb23.png)


![image](https://user-images.githubusercontent.com/54590466/234068254-f866890e-7176-4bfb-8d61-049cea95b200.png)

