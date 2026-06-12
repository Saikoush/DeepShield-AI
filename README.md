# DeepShield-AI

## Development of an AI/ML Based Solution for Detection of Face-Swap Deepfake Videos

DeepShield-AI is an AI-powered deepfake detection system designed to identify face-swapped and manipulated videos using Computer Vision and Deep Learning techniques. The project focuses on detecting forged facial content by analyzing video frames and extracting facial features using advanced neural network architectures.

---

## Project Overview

With the rapid growth of AI-generated media, deepfake videos have become a major concern in social media, cybersecurity, journalism, and digital forensics. DeepShield-AI provides an intelligent solution to distinguish between genuine and manipulated videos.

The system processes uploaded videos through multiple stages:

1. Video Frame Extraction
2. Face Detection and Cropping
3. Image Preprocessing
4. Deep Learning-Based Classification
5. Deepfake Probability Prediction
6. Report Generation

---

## Features

- Face-Swap Deepfake Detection
- Video Upload and Analysis
- Automatic Frame Extraction
- Face Detection using MTCNN
- Deep Learning-Based Classification
- Confidence Score Prediction
- Real vs Fake Classification
- User-Friendly Dashboard
- Scalable AI Pipeline

---

## Technology Stack

### Frontend
- Streamlit

### Backend
- Python

### AI/ML Frameworks
- TensorFlow
- Keras
- EfficientNet

### Computer Vision
- OpenCV
- MTCNN

### Dataset
- FaceForensics++
- Celeb-DF
- DFDC Dataset

---

## System Architecture

```text
Input Video
     |
     v
Frame Extraction
     |
     v
Face Detection
     |
     v
Face Cropping
     |
     v
Image Preprocessing
     |
     v
Deep Learning Model
     |
     v
Prediction
     |
     v
Result Dashboard
```

---

## Project Structure

```text
DeepShield-AI/
│
├── app.py
├── train.py
├── predict.py
├── requirements.txt
│
├── dataset/
├── uploads/
├── models/
├── reports/
│
├── utils/
│   ├── face_extractor.py
│   ├── preprocessing.py
│   └── report_generator.py
│
└── README.md
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/Saikoush/DeepShield-AI.git
cd DeepShield-AI
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Running the Project

### Train the Model

```bash
python train.py
```

### Predict Deepfake Videos

```bash
python predict.py
```

### Launch Web Application

```bash
streamlit run app.py
```

---

## Expected Outcomes

- Detect manipulated facial videos with high accuracy.
- Assist in combating misinformation and digital fraud.
- Provide a practical AI solution for media authentication.

---

## Future Enhancements

- Real-Time Deepfake Detection
- Mobile Application Support
- Multi-Face Detection
- Explainable AI Visualizations
- Cloud Deployment

---

## Author

**Sai Koush**
GitHub: https://github.com/Saikoush

---

## Academic Project

Mini Project submitted for the fulfillment of Bachelor's Degree requirements in Artificial Intelligence and Machine Learning.

Project Title:
**Development of an AI/ML Based Solution for Detection of Face-Swap Deepfake Videos**