# Emotion Detector

**Project name:** Emotion Detector (final project, Python Project for AI & Application Development).

A Flask web application that detects emotions (anger, disgust, fear, joy, sadness)
and the dominant emotion in a text, using the Watson NLP `EmotionPredict` service.

## Structure
- `EmotionDetection/emotion_detection.py` - the `emotion_detector` function
- `EmotionDetection/__init__.py` - makes `EmotionDetection` a package
- `test_emotion_detection.py` - unit tests
- `server.py` - Flask web server (`/` and `/emotionDetector`)
- `templates/index.html`, `static/mywebscript.js` - web interface

## Run
```
python3 server.py        # open http://localhost:5000
python3 -m unittest test_emotion_detection.py
pylint server.py
```
