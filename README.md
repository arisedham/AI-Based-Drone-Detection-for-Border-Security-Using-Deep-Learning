# AI-Based-Drone-Detection-for-Border-Security-Using-Deep-Learning
Collection of CNN and ResNet-based deep learning models for drone and image recognition tasks. Clink here for more: https://new.express.adobe.com/webpage/AjDUvS4OC9GJo



This repository demonstrates a project titled **“AI-Based Drone Detection for Border Security Using Deep Learning”** which uses Convolutional Neural Networks (CNN) and ResNet50 models to classify drone vs non-drone images in a border security context.

## Project: Drone Detection for Border Security
See the folder: `drone_detection_border_security/`

### 🚀 Background
With the increasing use of drones for delivery, surveillance and potential illegal activities, unauthorized drone intrusions along national borders pose significant security threats. Traditional surveillance systems struggle to detect these drones effectively. (Adapted from presentation)  

### 🎯 Objective
Develop a real-time drone detection system using deep learning (CNN & ResNet50) that can be integrated with live video feeds (e.g., CCTV) to alert security personnel of drone threats.  

### 📊 Dataset 
- ~1,625 images covering two drone types (multi-rotors & fixed-wing) + non-drone objects (birds, airplanes, etc)  
- Training/test split: 70%/30%  
(See dataset folder for details)  

### 🧠 Models
- CNN: built from scratch, good baseline  
- ResNet50: pretrained transfer-learning for superior performance  
- Results: CNN achieved ~85% accuracy with good precision on Drone class (0.95) but weaker on Non-Drone. ResNet50 achieved ~94% accuracy with balanced precision/recall/F1 for both classes. (From slides)  

