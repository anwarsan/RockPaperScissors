# RockPaperScissors
This is the final project of image classification, part of Belajar Machine Learning from Dicoding Academy. It is an artificial neural network program using TensorFlow. The program should be able to recognize the shape of the hand in form of rock, paper, or scissors.

I've got 5 stars for the final result which has completed these criterias:
1. Accuracy of the model above 85%, mine is around 98% for the train accuracy and the validation accuracy is 97%, this indicates that the model is good fit.
2. Using more than 1 hidden layer.
3. Apply more image augmentation.
4. Using optimizers and loss-functions.
5. Model training does not exceed 30 minutes.

Note: When predicting images, the model will give good prediction results when the uploaded image has a green screen background, but when the image does not have a greenscreen background the prediction results often mismatch. This is because the dataset used for training model has a uniform background, so that the model only recognizes the green screen background, to overcome this we can add more diverse image for the dataset or use pretrained models such as Inception, MobileNet, VGG, and others.
