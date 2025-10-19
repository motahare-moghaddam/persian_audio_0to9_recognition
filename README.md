
## 🧠 Project Overview

**Title:** Persian Audio 0–9 Recognition with Unknown Class Handling and ONNX Optimization  
**Goal:** Build a robust Persian digit classifier using deep learning, with real-time interfaces and model optimization.

**Dataset:** Collected by Computer Science students at Rajaee University, Spring 2024.

**Tools & Technologies:**  
- TensorFlow / Keras  
- CNN & RNN architectures  
- Spectrogram and waveform analysis  
- ONNX conversion and quantization  
- Python audio processing libraries (e.g., `pyaudio`, `librosa`)

---

## 📊 Final Model Performance

- **Validation Accuracy:** `0.8177`  
- **Confusion Matrix:**  
  ![Confusion Matrix](https://github.com/motahare-moghaddam/persian_audio_0to9_recognition/assets/174936236/0cdb4e44-b60c-4b1f-815a-a9d2ab1b3d4d)

- **Spectrogram Sample:**  
  ![Spectrogram](https://github.com/motahare-moghaddam/persian_audio_0to9_recognition/assets/174936236/e768c12a-d970-48c8-8d43-9442aeb08493)

---

## 🧩 Project Phases

### 🔹 Phase 1: Unknown Classifier
> Added an "Unknown" class to handle out-of-distribution audio samples. Trained the model as an 11-class classifier to detect digits 0–9 and "Other".

📄 Highlights:
- Data augmentation for unknown class
- Model architecture tuning
- Evaluation metrics and visualizations

---

### 🔹 Phase 2: Audio Interfaces
> Developed two interfaces for real-world audio input:

1. **Offline Processor:** Splits long audio files using silence detection and classifies each segment.  
2. **Live Stream Recognizer:** Captures audio from microphone and performs real-time digit recognition.

📄 Highlights:
- Silence-based segmentation
- Real-time microphone stream handling
- GUI/CLI interface options

---

### 🔹 Phase 3: ONNX Conversion & Quantization
> Converted the trained model to ONNX format and applied quantization for deployment efficiency.

📄 Highlights:
- ONNX export and validation
- Quantization techniques (dynamic/static)
- Performance comparison before/after optimization



---



---

## 📚 Documentation & Resources

- [ONNX Official Docs](https://onnx.ai/)
- [TensorFlow Audio Recognition](https://www.tensorflow.org/tutorials/audio)

---

## 🧑‍💻 Author

**Motahare Moghaddam**  
Computer Programming Instructor | Tehran  
Passionate about teaching, deep learning, and building educational tools in Farsi.

