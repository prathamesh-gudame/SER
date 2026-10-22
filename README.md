# SER
Speech Emotion Recognition using ML
# Speech Emotion Recognition using Machine Learning

Final-year B.E. project (Electronics Engineering, VESIT Mumbai, 2023-24), built in a team of four. A convolutional neural network (CNN) that recognises emotions in speech from MFCC audio features.

## Results
- Seven emotion classes: angry, disgust, fear, happy, neutral, sad, surprise.
- About 96% accuracy on test data after 50 training epochs.
- The notebook can record a new voice clip and predict its emotion.

![Training and test accuracy](images/ser-accuracy.png)

## How it works
1. Load labelled speech clips.
2. Extract MFCC features with Librosa.
3. Train a CNN in TensorFlow.
4. Evaluate on test data and classify new recordings.

## Data
<!-- fill in: dataset name and link -->

## Tech
Python, TensorFlow, Librosa, NumPy, Pandas, scikit-learn, Matplotlib, Google Colab

## Run it
Open `speech-emotion-recognition.ipynb` in Google Colab and run the cells in order.

## My part
<!-- fill in: what you personally did -->
