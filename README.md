# Image-Compression-Using-PCA

# 🧠 PCA-Based Image Compression Project

This project demonstrates how to compress images using **Principal Component Analysis (PCA)** in Python. It shows how PCA can reduce the dimensionality of image data while preserving visual quality — resulting in smaller file sizes and faster processing.

---

## 📷 Project Overview

- 🔍 **Goal**: Apply PCA to RGB image channels and reduce file size without losing much quality.
- 🧠 **Technique**: Compress each color channel (Red, Green, Blue) using PCA separately.

---

## 📁 Folder Structure

### 🚀 How It Works
1) Load Image (any .jpg or .png file)

2) Split Channels (R, G, B)

3) Apply PCA separately on each channel

4) Reconstruct Image with reduced components

Compare Sizes and Quality

## 🧠 What is PCA?
PCA (Principal Component Analysis) is a dimensionality reduction technique that projects data into a lower-dimensional space while preserving as much variance (information) as possible.

In image compression:

PCA removes redundant features from each color channel.

This reduces the size of image data while keeping it visually close to the original.

## 📊 Results
Images are compressed using different PCA component values (e.g., 10, 20, 50, 100). You can visually compare:

## 📌 Conclusion
Compressing images using PCA offers the following benefits:

* 🗂️ Saves storage space, especially with large datasets.

* ⚡ Faster processing in machine learning pipelines.

* 📦 Reduces transfer and storage cost.

* 🔄 Useful in bandwidth-limited or real-time systems.

PCA helps us keep important image features while reducing redundancy — making our work more efficient and scalable. 🎯

Made with ❤️ by [**Marwan Tamer**]
