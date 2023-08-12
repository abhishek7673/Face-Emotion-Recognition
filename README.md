# Emotion_detection_with_CNN


### Packages need to be installed
- pip install numpy
- pip install opencv-python
- pip install keras
- pip3 install --upgrade tensorflow
- pip install pillow

### download FER2013 dataset
- from below link and put in data folder under your project directory (63MB)
- https://www.kaggle.com/msambare/fer2013

### Train Emotion detector
- with all face expression images in the FER2013 Dataset
- command --> python TranEmotionDetector.py

It will take several hours depends on your processor. (On i7 processor with 16 GB RAM it took me around 4 hours)
after Training , you will find the trained model structure and weights are stored in your project directory.
emotion_model.json
emotion_model.h5

copy these two files create model folder in your project directory and paste it.

### run your emotion detection test file
python TestEmotionDetector.py

# BRIEF INTRO
# Face-Emotion-Recognition
This is my mini project, I choose in my academics. Face Emotion Recognition/Detection is very useful now-a-days. It is widely used in the study of the face emotionin some aspect. It can be used in medical field.
Emotion detection using CNN has found applications in various domains. One prominent application is facial expression analysis, where CNNs can accurately identify emotions from facial images or videos. This technology can be employed in fields such as mental health monitoring, lie detection, and personalized user experiences.
* Another application is in human-computer interaction, where systems can adapt their behavior based on the detected emotions of users. For example, a virtual assistant can provide more empathetic responses if it detects frustration or sadness in the user’s voice.
Emotion detection using CNN also has significant potential in market research and sentiment analysis. By analyzing social media posts, customer reviews, and other textual content, companies can gain insights into customer satisfaction, sentiment trends, and the effectiveness of their marketing campaigns.
# CONVOLUTIONAL NEURAL NETWORK: Powerful Neural Networks for Images and Videos.
In deep learning, a convolutional neural network (CNN) is a class of artificial neural network most commonly applied to analyze visual imagery and scene. A Convolutional Neural Network (CNN) is a specialized type of neural network primarily used in computer vision tasks. It has proven to be highly effective in analyzing and extracting patterns from visual data, making it well-suited for tasks such as object recognition and image classification. CNNs consist of multiple layers, including convolutional layers, pooling layers, and fully connected layers, that work together to extract and process features hierarchically.

 They have many application such as: They have applications in:
         # image and video recognition,
         # recommender systems,
         # image classification,
         # image segmentation,
         # medical image analysis,
         # natural language processing,
         # brain–computer interfaces,
         # financial time series.
