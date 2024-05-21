# Emotion_detection_with_CNN

### Download data
https://drive.google.com/file/d/1AsrfjR0twlv8lH8jjkwy9XfIH5Zh6NEu/view?usp=sharing

### Packages need to be installed
pip install -r requirements.txt

### Train Emotion detector
- with all face expression images in the FER2013 Dataset
- command --> python TrainEmotionDetector.py

It will take several hours depends on your processor. (On i5 processor with 8GB RAM it took me around 7 hours)
after Training , you will find the trained model structure and weights are stored in your project directory.
emotion_model.json
emotion_model.h5

copy these two files create model folder in your project directory and paste it.

### run your emotion detection test file
python TestEmotionDetector.py

