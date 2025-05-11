<h1 align="center">
EmiliFy: Multimodal Emotion Recognition using <br> Facial and Speech Inputs
</h1>

---

## 📝 Abstract

<div align="justify">

EmiliFy is a multimodal emotion recognition system built using Convolutional Neural Networks (CNN) to classify emotions from both facial expressions and speech. The project combines two deep learning pipelines — one trained on image data and the other on audio samples — to recognize emotions such as happiness, sadness, anger, fear, calm, and more.

By integrating trained CNN models for both modalities, the system allows users to upload an image and an audio clip to predict corresponding emotions. EmiliFy is designed as a local GUI-based application, ideal for human-computer interaction scenarios, affective computing, and mental health assessment tools.

</div>

---

## 📁 Repository Structure

```bash
EmiliFy/
├── Dataset/                      # Contains facial image dataset for training
├── SpeechEmotionDataset/        # Contains audio clips for training speech emotion model
├── model/                       # Stores trained CNN models in .h5 format
├── testImages/                  # Test images for facial emotion prediction
├── testSpeech/                  # Test audio clips for speech emotion prediction
├── FaceCNNTrain.py              # Script to train facial emotion CNN model
├── SpeechTrain.py               # Script to train speech emotion CNN model
├── Main.py                      # GUI application to test both models
├── run.bat                      # Batch script to launch the app
└── README.md                    # Project documentation
```
---
## 🎯 Key Features

- Multimodal input support: facial images and audio recordings  
- Trained CNNs for both facial expression and speech emotion classification  
- Real-time predictions via a local GUI interface  
- Custom dataset folders for testing various emotional states  
- Supports 7+ emotions including happy, sad, angry, calm, fearful, etc.  
- Live model interaction through simple upload and predict interface  

---

## 🛠️ Technologies Used

- **Programming Language**: Python 3.x  
- **Libraries**: NumPy, Pandas, OpenCV, Librosa, Keras, TensorFlow, Tkinter  
- **Development Tools**: Visual Studio Code, Anaconda  
- **GUI Toolkit**: Tkinter  
- **Deployment**: Local machine via `run.bat` launcher  

---

## 📊 Dataset Description

- **Facial Dataset** (`Dataset/`):  
  Image dataset organized by emotion labels (e.g., Angry, Happy, Sad, Neutral, Fearful, etc.) used to train the facial CNN model.

- **Speech Dataset** (`SpeechEmotionDataset/`):  
  Audio dataset comprising `.wav` files with filenames encoding emotion, gender, and speaker information. This is used to train the speech CNN model.

---

## 📈 Results Summary

- Both CNN models were trained separately on respective datasets.  
- Achieved training accuracy >95% for both facial and speech recognition models.  
- Tested using sample files from `testImages/` and `testSpeech/` directories.  

> Emotion predictions are displayed in the GUI after uploading a test image and audio clip.
---

## 📊 Experimental Results and Analysis

- The models were evaluated on custom facial image and speech audio datasets to measure classification accuracy and real-time usability.  
- Both models achieved >95% training accuracy and performed consistently across test inputs.  
- Graphs showing training accuracy, loss per epoch, and classification results are available in the interface and during model training.

> If you would like access to the complete results, visualizations, or further discussions, please feel free to contact me.

🌐 **Contact:** 
- **Email**: manne.bharadwaj.1953@gmail.com
- **LinkedIn**: [Bharadwaj Manne](https://www.linkedin.com/in/bharadwaj-manne-711476249/)
