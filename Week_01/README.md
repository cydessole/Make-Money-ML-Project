# Tensorflow.js Transfer Learning Image Classifier Example

The TensorFlow.js Tranfer Learning Image Classifier tutorial is the first assignment. You can look at the repository at [Tensorflow Tutorial](https://github.com/cydessole/TensorFlow.js-Transfer-Learning-Image-Classifier)

## Project

This is the final result of the TensorFlow.js Transfer Learning Image Classifier tutorial on the codelabs website.

You can follow the tutorial at [Codelab Tensorflow tutorial](https://codelabs.developers.google.com/codelabs/tensorflowjs-teachablemachine-codelab/) to create your own Image Classifier.

This project uses the WebCam to predict different classes.
To train the model you press the button of a category when the object of the corresponding category appears on camera.

After enough image samples for each category, your model will predict accurately the object shown on camera.

## Try it !

1. Go to this [page](https://cydessole.github.io/TensorFlow.js-Transfer-Learning-Image-Classifier/) to use the Image Classifier. You will need to grant Webcam privileges.

2. Show the object corresponding to each class (A to D) on camera and press the `Add #` button.

3. After enough training, you will see the right `Prediction` and high `Probability`. If not, you should add more training samples.

## Classic Example : Rock–paper–scissors 

I've seen this example multiple times to test this application.
I did this one as well to test my Classifier.

4 classes : 
  - A: Rock
  - B: Paper
  - C: Scissors
  - D: Nothing

The gif below shows the result after 20 training samples for each class for my model.

![Example Gif](ExampleGif.gif)
