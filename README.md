# Deep-Learning-Algorithms-based-Computer-aided-Diagnosis-for-Lung-Cancer
In this work, we developed a Convolutional Neural Network (CNN) to detect the cancerous nodules .Generally , benign nodules are less cancerous and cannot spread in other parts of body while malignant nodules are highly chance of being cancerous and can spread it to other parts of body. In our work , images of benign and malignant were used  for our CNN. Our CNN established, trained, and validated using data set. Model evaluation showed that the CNN model is able to detect the cancerous nodules with 68.84 % accuracy.
## 💻Model architecture
<img src="https://github.com/manvitharoy123/Deep-Learning-Algorithms-based-Computer-aided-Diagnosis-for-Lung-Cancer/blob/main/2.jpg" width="200" title="hover text">
- 📍We are using a Convolutional Neural Network (CNN) model.CNN are used to detect  patterns in an image. This is done by convoluting over an image and detecting for patterns . The network can detect lines and corners in the few front layers of CNN. With the help of  our neural network ,  we can then transfer these patterns down to next layers and begin to identify more complex patterns as we go down. This property shows that CNN are very useful  in detecting objects in images . 
The proposed model using CNN to detect nodule  from lung cancer CT Scan images .

- 🗒️CNN model composed of three main layers :-
      1.	Convolutional layer
      2.	Pooling layer
      3.	Fully connected layer

- 🌟Conv2d (). Construct a two-dimensional convolutional layer with the number of filters, filter kernel size, padding, and activation function like arguments.
- 💬max_pooling2d (). Construct a two-dimensional pooling layer using the max-pooling algorithm.
- 🤜Dense (). Construct a dense layer with the hidden layers and units

## 🗒️Model summary
<img src="https://github.com/manvitharoy123/Deep-Learning-Algorithms-based-Computer-aided-Diagnosis-for-Lung-Cancer/blob/main/1.jpg" width="200" title="hover text">
## 💻Training
For training the model we will take the dataset from train set and also we are validating the model using validation set.
The training in performed for 30 epochs.
During training we monitor the loss.
We use the loss function sparse_categorical_crossentropy.
Computes the crossentropy loss between the labels and predictions.
Use this crossentropy loss function when there are two or more label classes. We expect labels to be provided as integers.

## 📍Accuracy
<img src="https://github.com/manvitharoy123/Deep-Learning-Algorithms-based-Computer-aided-Diagnosis-for-Lung-Cancer/blob/main/3.jpg" width="200" title="hover text">
<img src="https://github.com/manvitharoy123/Deep-Learning-Algorithms-based-Computer-aided-Diagnosis-for-Lung-Cancer/blob/main/4.jpg" width="200" title="hover text">

## 📍Result analysis
<img src="https://github.com/manvitharoy123/Deep-Learning-Algorithms-based-Computer-aided-Diagnosis-for-Lung-Cancer/blob/main/5.jpg" width="200" title="hover text">

## 🤜conclusion
- We  have used modified cnn model and we got testing accuracy approximately 70%. We got sensitivity of 0.7169.

