# Hand Gesture Recognition 🖐️

A real-time hand gesture recognition system using **MediaPipe**, **OpenCV**, and **TensorFlow/Keras**.

## Features
- Real-time gesture detection via webcam
- Custom gesture data collection
- Model training using hand landmarks
- Live prediction and display

## Requirements
- Python 3.8+
- MediaPipe
- OpenCV
- NumPy
- Pandas
- TensorFlow / Keras

Install dependencies:
```bash
pip install -r requirements.txt
````

## How to Use

1. **Collect Data**: Run the notebook and enter a gesture name to save hand landmarks.
2. **Train Model**: Use collected CSV files to train a Keras model.
3. **Predict**: Use webcam to detect and classify gestures in real-time.

## Folder Structure

* `Hand Gesture.ipynb`: Main notebook
* `data/`: Collected CSVs
* `model/`: Trained model files
* `gesture_names.txt`: Class labels

