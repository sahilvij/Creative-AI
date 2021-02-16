# Creative-AI

The objective of the project is to create art masterpiece (images and videos) by using DeepDream algorithm.

- Using InceptionV3 (CNN) as the pre-trained model (transfer learning) and Pillow (PIL) to manipulate the images, the concept of gradient ascent and activation maximization       were assessed in order to create the masterpiece by combining images.

Steps to generate art masterpiece are given below:
1. Obtaining the InceptionV3 model from keras applications.
2. Importing two images, namely mars.jpg and eiffel.jpg and merging them (saved as ImageBlend.jpg).
3. Converting the merged image to an array and normalizing it.
4. Exploring the activations throughout the layers of the model by assessing the DeepDream algorithm.
5. Calculating the loss and increasing the gradient and maximizing the activations.
6. Saving the newly created images frames-by-frames depending upon the step-size.
7. Uploading those newly created images in a ZipFile.
8. Extracting the newly created images and combining them to generate a video.
