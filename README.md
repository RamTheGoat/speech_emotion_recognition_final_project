# 🎤 Speech Emotion Recognition Using Deep Learning

## Overview

This project uses Deep Learning and Computer Vision techniques to recognize human emotions from speech audio files.

Audio recordings are converted into **Mel Spectrogram images**, then classified using pretrained CNN architectures.

The system compares two popular transfer learning models:

- ResNet18
- MobileNetV2

The best model is then used to predict emotions from custom uploaded voice recordings.

---

## Dataset Used

### RAVDESS Dataset

Ryerson Audio-Visual Database of Emotional Speech and Song

Contains professional actors speaking with labeled emotions:

- Neutral
- Calm
- Happy
- Sad
- Angry
- Fearful
- Disgust
- Surprised

---

## Technologies Used

- Python
- Google Colab
- PyTorch
- Torchvision
- Librosa
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Grad-CAM

---

## Deep Learning Pipeline

### Step 1: Audio Preprocessing

Each `.wav` file is converted into a Mel Spectrogram image.

### Step 2: Transfer Learning Models

Two pretrained CNNs were fine-tuned:

- ResNet18
- MobileNetV2

### Step 3: Evaluation

Models were compared using:

- Validation Accuracy
- Validation Loss
- Confusion Matrix
- Precision / Recall / F1 Score
- Inference Speed
- Parameter Count

### Step 4: Explainability

Grad-CAM heatmaps were used to visualize which parts of the spectrogram influenced predictions.

### Step 5: Custom Voice Testing

Users can upload their own voice recordings and receive predicted emotional labels.

---

## Files Included

- `FinalProject.ipynb` → Full notebook implementation
- `README.md` → Project documentation

---

## Example Results

The model successfully identified emotions such as:

- Happy
- Sad
- Angry
- Neutral
- Fearful

CNN transfer learning significantly improved classification accuracy.

---

## How To Run

1. Open notebook in Google Colab
2. Upload RAVDESS dataset zip file
3. Run all cells
4. Upload custom audio to test predictions

---

## Future Improvements

- Use larger audio emotion datasets
- Add transformer models
- Real-time microphone prediction
- Deploy as web application

---

## Contributors

- Ram Patel  
- Jessie Cai 
- Katie Cheng

University of Georgia  
Computer Science
