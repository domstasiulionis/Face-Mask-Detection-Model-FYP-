# Face Mask Detection Model

## :receipt: About
This was my final project for the degree of BEng Software Engineering at the University of Greenwich. The overall aim of this project was to create an accurate face mask detection model using convolutional neural networks and machine learning. One of the main goals for the final model was for it to have the ability detect whether a person was or was not wearing a face mask in real-time via webcam stream. Overall, 9 iterations of the model were made using two methods. The first method involved using the Tensorflow object detection API and the second was a transfer learning method using Keras.   

The best models produced by both methods are uploaded to this repository alongside the dissertation, which documents the entire development process of this project and the models. However, the tensorflow object detection API method had been the main focus during developement whereas the transfer learning with Keras was implemented to mainly serve as a comparison to the tensorflow object detection API method, to investigate whether it would yield better results.   

For a more detailed look into this project, I recommend checking out the dissertation added to this repository. It is a 40,000+ word essay however, a table of contents is provided so you can navigate to the sections you would like to see.   

Grade: First (81%)        

## :hammer: Built Using:
* [Python (3.8)](https://www.python.org/) - Main programming language
* [TensorFlow (2.4)](https://www.tensorflow.org/) - Machine learning framework
* [Keras](https://keras.io/) - Machine learning library

### Test Image Result:
![image](https://user-images.githubusercontent.com/44949034/215362171-ad3f4f9f-6b3d-4537-9c6e-18dc63f90290.png)

###  Live Stream Result:
![image](https://user-images.githubusercontent.com/44949034/215362213-14f5833b-605f-4d51-820a-b77d116e467d.png)

## :star: Features
- [x] Able to detect people wearing face masks via images and live stream input
- [x] Able to detect people NOT wearing face masks via images and live stream input
- [x] Able to detect different classes (mask/no mask) simultaneously
- [x] If a mask is not on a persons face, model will determine that the person is not wearing a mask even if a mask is present in frame
- [x] Model takes glasses, facial expressions and beards into consideration
- [x] Model takes different angles and distance into consideration
- [x] A detection can still made even if the face is partially obstructed (hand on face, etc.)
- [x] High detection accuracy

## :computer: Author
Project created by [@domstasiulionis](https://github.com/domstasiulionis)
