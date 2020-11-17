# Drowsiness Dectection
An Alert System for Drowsiness Detection with OpenCV 

[x] With real time data cloud analysis using [Thingspeak Cloud](https://thingspeak.com/ "Thingspeak Cloud").

[x] With real time SMS alerts using [Twilio SMS APIs](https://www.twilio.com/ "Twilio api").

[x] With real time monitoring android app using [MIT app inventor.](http://appinventor.mit.edu/ "MIT")

## Usage

Install all necessary packages using commands below.

```pip install imutils
pip install cmake
pip install dlib
pip install playsound
pip install twilio
pip install opencv-python
pip install requests-futures
```

Replace API keys of thingspeak and twilio as mentioned in code.

For Color screen preview Run: ```python detect_drowsiness1.py --shape-predictor shape_predictor_68_face_landmarks.dat --alarm alarm.wav```

For Grayscale screen preview Run: ```python detect_drowsiness2.py --shape-predictor shape_predictor_68_face_landmarks.dat --alarm alarm.wav```

NOTE: Use Anaconda Promt.

For Android app import .aia file to your [MIT app inventor](http://appinventor.mit.edu/ "MIT") platform,replace thingspeak API keys in building blocks Web section and build .apk file.

## Credits

Thanks to Adrian Rosebrock for OpenCV source code : https://www.pyimagesearch.com/2017/05/08/drowsiness-detection-opencv/
