# DeepSpeech for Mental Health Monitoring

# Introduction 
This project aims to create a compact, low-power audio monitoring system for detecting mental health language markers. Inspired by a study on absolutist words, we propose a wearable device using the Arduino Nano BLE Sense board. The system involves gathering keyword audio samples, expanding the Speech Command dataset, training a machine learning model for keyword spotting, and deploying it for real-time testing on the Arduino board.

# Files Included

1. Data Collection:
Download or create a labeled audio dataset for training and testing.

2. Deep Learning Model:
Train the machine learning model for audio keyword spotting using the dataset.

3. TinyML (TFLite) File:
Convert the trained model to TensorFlow Lite format.

4. Deploy on Arduino:
Use Arduino inference code to deploy the TFLite file on the Nano BLE Sense board.

5. Testing:
Connect the Arduino board, analyze real-time audio signals, and evaluate keyword spotting performance.

# Results
<a href="https://youtu.be/X7iaZbnHmng" target="_blank"><img src="https://i9.ytimg.com/vi/X7iaZbnHmng/mqdefault.jpg?sqp=COiS5qwG-oaymwEmCMACELQB8quKqQMa8AEB-AHUBoAC4AOKAgwIABABGEogYyhlMA8=&rs=AOn4CLB6xPh3TVmEpGrswkj58HSybSpw5A" 
alt="UAV Line Follower" width="240" height="180" border="10" /></a>

# Conclusion

In summary, our project successfully implemented a deep learning-based audio monitoring system for mental health markers, showcasing effective keyword spotting on the Arduino Nano BLE Sense board. The compact wearable design, coupled with real-time functionality, holds promise for discreet and continuous mental health language monitoring in daily life
