# 🦴 Knee Osteoarthritis Detection using Ensemble CNN



![Python](https://img.shields.io/badge/Python-3.8-blue)




![Deep Learning](https://img.shields.io/badge/Deep%20Learning-CNN-green)




![Flask](https://img.shields.io/badge/Backend-Flask-red)




![Status](https://img.shields.io/badge/Status-Completed-brightgreen)



## 📌 Overview
An automated deep learning system that detects Knee Osteoarthritis (KOA) 
severity stages from X-ray images using an Ensemble CNN combining 
ResNet50, MobileNetV2, and AlexNet with a real-time Flask web interface.

## 🎯 Problem Statement
Knee Osteoarthritis affects millions worldwide. Manual diagnosis from 
X-rays is time-consuming and error-prone. This system automates 
detection for faster and accurate early diagnosis.

## ⚙️ Pipeline
1. Collect knee X-ray dataset
2. Preprocess — resize to 224x224, normalize (ImageNet distribution)
3. Pass through 3 pretrained CNN models simultaneously
4. Extract and concatenate features (7424 dimensions)
5. Classify into 5 severity stages
6. Display prediction via Flask web app

## 🎯 Output Classes
| Grade | Stage     | Description              |
|-------|-----------|--------------------------|
| 0     | Normal    | No OA signs              |
| 1     | Doubtful  | Minimal narrowing        |
| 2     | Mild      | Definite osteophytes     |
| 3     | Moderate  | Moderate narrowing       |
| 4     | Severe    | Large osteophytes        |

## 🛠️ Technologies Used
| Category        | Tools                           |
|-----------------|---------------------------------|
| Language        | Python 3.8                      |
| Deep Learning   | TensorFlow, Keras               |
| CNN Models      | ResNet50, MobileNetV2, AlexNet  |
| Web Framework   | Flask                           |
| Data Processing | NumPy, OpenCV, Matplotlib       |

## 📊 Model Details
- *Input Size:* 224 x 224
- *Loss Function:* CrossEntropyLoss
- *Optimizer:* Adam
- *Feature Vector:* 7424 (concatenated from 3 models)
- *Output:* 5-class classification

## ✅ Results
- High accuracy on multi-class classification
- Fully automated end-to-end pipeline
- Real-time predictions via web interface
- Supports early diagnosis and clinical decision-making

## 🔮 Future Scope
- Mobile app deployment
- Hospital system integration
- Training on larger real-world datasets

## 👩‍💻 Author
*Shaik Muskan*
B.Tech CSE (AI) — Chaitanya Bharathi Institute of Technology
[LinkedIn](https://www.linkedin.com/in/shaik-m-0b6963264) | [GitHub](https://github.com/Smuskan3145)
