View Layer Direction for the poisons plant app

1) get the camera working using expo: Done
https://medium.com/wesionary-team/camera-module-in-react-native-with-expo-camera-3b8c9f3cd076
2) get any locally stored image to be rendered onto the screen and be recognize by the pre-trainned model: Done
https://github.com/amandeepmittal/mobilenet-tfjs-expo
3) Integrate the camera and the model so that it is possible to take a picture and have the model analylze the photo that was taken.  By this step, it is possible to have image recognition using a "dummy" pre-trained model. : Working on now
4) Figure out what kind of model that ashish is using.  What is the type and how can it translated to something that is similar to the dummy model that I am using in development.
5) Translate  model that ashish is using into tensorflow.js react native model (tfjs-react-native) using onnx.js
6) "swap" out the pre-trainned model used in view layer developement with the custom model that ashish will be making


Interesting sources to consider


https://www.youtube.com/watch?v=Y-0Iy0EntWY&ab_channel=UnsureProgrammer


pytorch -> tfjs: https://github.com/anujdutt9/PyTorch-DeepLearning/blob/master/Udacity%20PyTorch%20Course%20Exercises/Part%206%20(II)%20-%20Saving%20and%20Loading%20Models%20as%20ONNX.ipynb
