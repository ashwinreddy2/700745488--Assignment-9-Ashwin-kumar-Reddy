# 700745488--Assignment-9-Ashwin-kumar-Reddy

Here is the video link for the class programming
https://drive.google.com/file/d/1GNwYBRITf1coAhxboB62TF4nUb373BWC/view?usp=sharing

In class programming:
1. Add one more hidden layer to autoencoder
2. Do the prediction on the test data and then visualize one of the reconstructed version of that test data.
Also, visualize the same test data before reconstruction using Matplotlib
3. Repeat the question 2 on the denoisening autoencoder
4. plot loss and accuracy using the history object
dd one more hidden layer to autoencoder

A)
This code first runs the provided code, following which we add some hidden layers in encode (the encoded representation of the input), along with decode (the lossy reconstruction of the input). This model plots an input to its reconstruction as well as the encoder for its encoded representation, and it is then compiled and loaded with the MNIST dataset, after which the data is normalized and flattened, and the autoencoder is trained.

Here is the screenshot regarding this explanation
<img width="788" alt="image" src="https://user-images.githubusercontent.com/122486644/230260607-2aeaf6c8-d384-402c-b911-e21dd0d91550.png">


2. Do the prediction on the test data and then visualize one of the reconstructed version of that test data.
Also, visualize the same test data before reconstruction using Matplotlib

Using the Matplotlib library, we will obtain the test set's reconstructed pictures for this. Using the image to be plotted's index, select a random image from the test set, and then use the imshow() function to plot both the original and the rebuilt picture.

Here is the screenshot regarding this explanation
<img width="841" alt="image" src="https://user-images.githubusercontent.com/122486644/230261655-0b97ac62-2c51-4b07-bd10-b6fee0497bb7.png">



3. Repeat the question 2 on the denoisening autoencoder
First, we ran the provided code, then we added a few lines to display the original noisy and reconstructed images by obtaining the reconstructed images for the test set, and finally by selecting a random image from the test set.

Here is the screenshot regarding this explanation
<img width="902" alt="image" src="https://user-images.githubusercontent.com/122486644/230262173-98946f22-edd3-4f27-b26e-e207aecad561.png">


4. plot loss and accuracy using the history object.
Here, after importing Matplotlib, we are using the autoencoder to teach the autoencoder.We are showing the graphs of both loss and accuracy by using the fit() function, plotting the loss and accuracy, and declaring the title, xlabel, and ylabel functions in the plot() function.

Here is the screenshot regarding this explanation
<img width="877" alt="image" src="https://user-images.githubusercontent.com/122486644/230262766-5a285968-5c84-432a-b051-3f9547276e09.png">
<img width="572" alt="image" src="https://user-images.githubusercontent.com/122486644/230262804-0a36dfc9-2be7-4915-89c4-48b00017bbc7.png">
<img width="636" alt="image" src="https://user-images.githubusercontent.com/122486644/230262844-a31df43e-7fe8-4fbb-9369-83931c970c5e.png">
