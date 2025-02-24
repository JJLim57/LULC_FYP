# SkyMaster: Drone for Land Use Mapping 🚀🌍

## Overview
**SkyMaster** is a land use and land cover (LULC) classification project that utilizes **RGB images captured by drones** to analyze and classify land cover types. This project aims to provide an affordable, efficient, and accessible **machine learning-based solution** for LULC classification, leveraging **Support Vector Machine (SVM) and Random Forest (RF) models**.

This work was done as part of a **Capstone Project at Taylor’s University**, where the team **developed a drone, trained, and tested a machine learning model** using aerial imagery captured by the drone.

## Role:
Lead Data Scientist & ML Developer - Using the captured aerial imagery, I trained and test machine learning model to determine which ML model was able to classify land accurately.

---

## 📌 Project Description
### **Objectives**
- **Develop a cost-effective autonomous drone** capable of capturing high-resolution images and geospatial data.
- **Train and optimize machine learning models** to classify different land cover types.
- **Create a Python-based land classification system** that processes RGB drone imagery.
- **Build a user-friendly interface** to automatically select the best classification model for LULC mapping.

### **Key Features**
✅ **Custom-built F450 quadcopter drone** with a high-resolution camera and GPS module  
✅ **RGB image-based classification** using SVM and Random Forest  
✅ **Geospatial data processing** using QGIS for orthomosaic map creation  
✅ **Automated classification model selection** based on test results  
✅ **Machine learning pipeline** including feature extraction, training, and evaluation  

---

## 🛠️ Tech Stack & Tools
### **Hardware**
- **Drone:** F450 quadcopter with **2212 920KV brushless motors**
- **Camera:** SIYI A8 mini **high-resolution RGB camera**
- **GPS:** Holybro M9N module **for accurate geolocation tagging**
- **Flight Controller:** Pixhawk 6C with ArduPilot
- **Communication:** Telemetry system for remote monitoring

### **Software & Libraries**
- **Programming Language:** Python 🐍
- **Machine Learning:** `scikit-learn` (SVM, Random Forest)
- **Geospatial Processing:** `QGIS`, `Rasterio`
- **Visualization & UI:** `Matplotlib`, `Tkinter`
- **Drone Control:** ArduPilot for autonomous flight

---

## 🖼️ System Workflow
1. **Drone captures RGB images & geospatial data** 📷📡
2. **Images are pre-processed & stitched into an orthomosaic map** 🗺️
3. **Feature extraction from RGB bands (Red, Green, Blue)** 🎨
4. **Train & test machine learning models (SVM, RF) for classification** 🤖
5. **Best-performing model is used for land use classification** ✅
6. **Final classified LULC map is generated** 🌍

---

## 🔍 Machine Learning Models
### **Support Vector Machine (SVM)**
- Used to find an **optimal hyperplane** for class separation.
- Works well for **high-dimensional feature spaces**.

### **Random Forest (RF)**
- An ensemble learning method combining multiple decision trees.
- Provides **high accuracy** and **robustness against overfitting**.

> **Evaluation**: Both models were trained and tested on different images, and the best-performing one is automatically selected for classification.

---

## 🏆 Results & Findings
- **SVM and RF performed well**, with **varying results depending on the image dataset**.
- **Feature engineering on RGB-only data** showed promising results in distinguishing vegetation, water bodies, and urban areas.
- **The classification interface successfully selects the best model** based on dataset performance.

---

## 📂 Project Structure

