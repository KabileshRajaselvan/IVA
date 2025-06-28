
# 🎥 Spatio-Temporal Segmentation and Scene Cut Detection

### Lab 4 – IVA (Image and Video Analytics)

**Author:** A. Kabilesh Rajaselvan (21MIA1132)
**Institution:** SCOPE, VIT Chennai
**Date:** 28-06-2025

---

## 🧠 Objective

To analyze a video by:

* Extracting frames
* Performing **spatio-temporal segmentation**
* Detecting **scene transitions** (hard and soft cuts)
* Generating a visual summary of objects and cuts

This lab aims to simulate real-world applications such as video surveillance, traffic monitoring, and IoT-based event detection.

---

## 🧩 Problem Statement

In video analytics, meaningful interpretation of scenes depends on the ability to:

* Isolate moving objects from static backgrounds
* Track motion over time
* Identify scene changes (cuts) effectively

Challenges arise from variable lighting, gradual scene transitions, and overlapping objects.

---

## 🚀 Expected Output

* ✅ Extracted video frames
* ✅ Segmented foreground objects
* ✅ Hard and soft scene cuts detected
* ✅ Visual summary of segmentation and transitions

---

## 🛠 Methodology

### 1. **Video Loading & Frame Extraction**

* Use OpenCV to read the video
* Extract and store individual frames

### 2. **Spatio-Temporal Segmentation**

* Apply color thresholding to highlight objects
* Use Canny Edge Detection for sharp boundaries
* Track object changes across frames to detect motion
* Separate foreground from background by comparing changes over time

### 3. **Scene Cut Detection**

* **Hard Cuts**: Pixel-level differences across frames
* **Soft Cuts**: Gradual color/intensity shifts over time

### 4. **Result Visualization**

* Overlay segmentation masks on frames
* Highlight scene cuts with labels or bounding boxes
* Show key frames as a visual report

---

## 📊 Applications

* Video surveillance
* Traffic camera analysis
* IoT-based video monitoring systems
* Abnormal event detection

---

## 🔬 Challenges & Observations

* **Object Segmentation Accuracy** is sensitive to noise and lighting
* **Soft Cut Detection** requires more advanced techniques like histogram comparison or ML-based models
* Could be extended to real-time video summarization and abnormal activity alerts

---

## ✅ Conclusion

This experiment provides foundational knowledge in video analytics, particularly in segmenting frames and detecting temporal changes. It serves as a valuable component for larger projects in **AI-based surveillance** and **IoT video analysis systems**.

---


