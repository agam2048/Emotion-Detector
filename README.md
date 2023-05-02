# Emotion-Detector

The project was initialized by me in my 5th sem of computer science engineering, the projects focuses on AI that helps to determine the mood of a person by looking at the face and deciding it upon the various factors .
The projects goes like - 
* Human emotions are the mental state of feelings and are spontaneous. There is no clear connection between emotions and facial expressions and there is significant variability making facial recognition a challenging research area. 
* Recently online video interviews have been increasingly used in the employment process. Though several automatic techniques have emerged to analyze the interview videos, so far, only simple emotion analyses have been attempted, e.g. counting the number of smiles on the face of an interviewee. 
* So we have created a emotion detector which helps in Emotion Detection using Haar-Cascade Classifier and Convolutional Neural Network(CNN) for the psychometric interviews.
* A CNN model is trained with grayscale images from the FER dataset to classify expressions into five emotions, namely happy, sad, neutral, fear and angry. To improve the accuracy and avoid overfitting of the model, batch normalization and dropout are used. The test results obtained show that Model is 89% accurate for all the five emotions.

Application of the project goes like - 
* A CNN model is trained with grayscale images from the FER dataset to classify expressions into five emotions, namely happy, sad, neutral, fear and angry. To improve the accuracy and avoid overfitting of the model, batch normalization and dropout are used. The test results obtained show that Model is 89% accurate for all the five emotions.
* Job interviews are an important tool for employee selection. Conducting online interviews brings many beneﬁts to both interviewers and interviewees, including allowing many job applicants to be evaluated by HR staﬀ, the convenience of oﬄine reviewing and decision making by HR staﬀ and supporting long-distance interviews to reduce costs.
* Pre-hire assessments can save thousands of dollars per headcount in turnover costs, not including the higher cost of employing poor performers. With AI, you can compare a candidate against an ideal, model employee. AI tools can add additional insights into people’s personalities and motivations that screeners can’t see on paper.
* Hence, comes our model, emotion detector which will help to identify the emotions of the interviewee not just using his submitted video but also while interviewing him on the skype call. We can use all his submitted pictures too and it will detect the five emotions: angry, happy, sad, surprise and neutral. 

Steps of implenting the Face emotion detector - 
 * The first is to detect a face in an image and draw a rectangle around it and the next step is to detect landmarks in this face region. The third step is extracting spatial and temporal features from the facial components. The final step is to use a Feature Extraction (FE) classifier and produce the recognition results using the extracted features

* Image standardization: it includes various sub-processes such as the removal of noise from the image, making all the images uniform in size and conversation from Red, Green and Blue (RGB) to grayscale. 
 Face detection: It aims to remove all the unwanted things from the picture, such as background and to keep relevant information, the face from the data. 
 Facial component analysis: Here, regions of interests are detected. This step is necessary as it helps to minimize the errors that can arise due to rotation or the alignment of the face.

* The images are 48X48 grayscale cropped images. The csv file consists of a flattened array of image stored in the form of a string.
The target labels are integer encoded in the csv file. They are mapped as follows:
      0  Angry
      1  Happy
      2  Sad
      3  Surprise
      4  Neutral
      
* CNN - CNN, is a deep learning neural network sketched for processing structured arrays of data such as portrayals.
CNN are very satisfactory at picking up on design in the input image, such as lines, gradients, circles, or even eyes and faces.
CNN can run directly on a underdone image and do not need any preprocessing.
Firstly we have imported libraries such as numpy, keras and OpenCV for emotion detection
We have used webcam for capturing video to calculate the emotions.
Cascade algorithm helps in detecting the pixels of the particular image or video.


PROJECT SCOPE - 
Devices to detect an employees’ mental well-being can be created which will detect the face of the employee at the time he enters the company and give it’s results which will not only improve the performance of employees but issues such as depression and anxiety can be caught at early stages and they do not have to suffer in silence.
Facial emotion recognition is an emerging field so considering other NNs such as Recurrent Neural Networks (RNNs) may improve the accuracy. The feature extraction is similar to pattern recognition which is used in intelligence, military and forensics for identification purposes. Thus, techniques such as the Capsnet algorithm for pattern recognition can be considered.


      


