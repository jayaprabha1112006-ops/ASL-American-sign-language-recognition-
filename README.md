American Sign Language recognition system with static image and real-time webcam input using deep learning.

To install the required modules : pip install tensorflow keras opencv-python streamlit numpy

[Download ASL Dataset from Kaggle](https://kaggle.com/your-dataset-link)

Files explanation:

Train.py- This script trains a Convolutional Neural Network (CNN) using the ASL dataset (images of American Sign Language letters).

Sign.h2 - A serialized version of the trained deep learning model. 

Real-Time Recognition- Captures frames, applies ROI cropping and preprocessing methods to guess the sign language dynamically

Static Recognition -Works on uploaded images or text input instead of live video. It has two features :

  1.Sign language to English language : Combines sign language letters to form words/sentences.

  2.English to sign language : Converts each character into its ASL hand gesture representation.
