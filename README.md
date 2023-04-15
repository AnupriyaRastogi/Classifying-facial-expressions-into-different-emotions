# Classifying-facial-expressions-into-different-emotions
Facial expression recognition is a technique that may be carried out by humans or computers and here, in my 
project:
1. Facial Feature Extraction: Face recognition in the surroundings and extraction of facial features from the 
recognized face region e.g., detecting the shape of face and its components such as eyes, using Haar-cascade in OpenCV.
2. Facial Expression Interpretation: Examining how the facial features move and/or change, and then 
categorizing this data into several interpretive categories for emotions like a grin or a frown, like joy or 
rage, or attitude categories like contempt or neutrality, etc. In order to do this, we employed and trained 
three different types of models, as follows:
a. CNN Model: Convolutional neural networks, often known as CNNs or ConvNets, specialize in processing 
input with a grid-like design, such as images. The three layers of a CNN are generally convolutional, 
pooling, and fully connected.
b. SVM Model: SVMs, a type of supervised learning method that performs well in high-dimensional 
domains.
c. DeepFace: DeepFace is the Python face recognition and facial attribute (age, gender etc.) analysis 
module. This free and open-source DeepFace library wraps all the most recent AI facial recognition 
models.
3. Image Manipulation: Manipulating pictures' brightness, contrast, and sharpness using Python PIL (pillow) 
library’s ImageEnhance module, to see how it would impact the CNN model's and DeepFace model's ability 
to anticipate emotions.
4. Real-time/Live Emotion Prediction: Prediction of emotions in real-time (webcam) using CNN model and 
DeepFace with face annotation.
