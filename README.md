# Face Emotion Recogition on FER2013 (69% Test Accuracy)

Real-time face detection and emotion/gender classification using fer2013 dataset.

You can view the Kaggle Notebook [here.](https://www.kaggle.com/uday47/face-emotion-recognition-resnet50-fer2013)

Due to computational limitations, model training and video stream was done on Google Colab.

The model achieved 69% validation accuracy which is apprximately 4% higher tha human-level accuracy.

You can download the trained model [here.](https://drive.google.com/file/d/11Gb3gzrG2z9-IgqxisitJgYl-B1LAzmS/view)

#### Image Demo

![](https://github.com/Uday47/Face-Emotion-Recogition-on-FER2013-69-Test-Accuracy-/blob/master/Images/Group.png)


#### Video Demo

![](https://github.com/Uday47/Face-Emotion-Recogition-on-FER2013-69-Test-Accuracy-/blob/master/Images/FERStream.gif)


I worked on a face emotion recognition project and I absolutely enjoyed the process. I worked on a dataset called FER2013 dataset. The data consisted of 48x48 pixel grayscale images of 35000 faces. The faces had been automatically registered so that the face is more or less centred and occupies about the same amount of space in each image.

The task was to categorize each face based on the emotion shown in the facial expression into one of seven categories (0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral). The training set consists of 28000 examples and the public test set consists of 7000 examples.

I trained the model on an architecture similar to ResNet-50 and declared loss and accuracy as evaluation metrics. The model surpassed Human-level accuracy and achieved 69.08% test accuracy with 0.99 test loss. 

As I did not have sufficient computational resources, I did the entire project on Google Colab free resources alone. I also wrote the code to recognize emotion over live video feed and image input. I used Keras/Tensorflow library for modelling. I enjoyed working on this project as it was challenging and helped me gain better understanding of implementation. 
