# Audio_emotion_detection
  Emotion recognition from voice data

This project starts with code copied from https://www.kaggle.com/samiaimad/ai-uni-project: 
ai-uni-project.ipynb

ai-uni-project-Copy1.ipynb is a copy that I used for development
Later I added vad.py and detectVoiceInWave.py for voice activity detection

Code needed to be overhauled to make it run. I also tried a different approach for getting the spectrograms, namely adding all audio per class together, then segmenting so as to keep only the voice parts, and then segmenting into pieces of a single length.

While training accuracy increased over iterations (typically up to 70%), validation accuracy never got very high (59%).

Left off with a to do list for further improvements and things to try.


Use virtual environment VoiceRec1

#Rogier Landman 2022
