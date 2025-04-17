# 🎨 Neural Style Transfer (NST) on Images

Apply the magic of art to your photos using Neural Style Transfer (NST)! This project blends the **content of one image** with the **style of another**, implemented using TensorFlow and VGG19 from the ground up (no pre-built style transfer models!).

---

## 🔍 Project Overview

This project demonstrates how to build a Neural Style Transfer pipeline for images — combining deep learning, computer vision, and optimization.

> Unlike plug-and-play pre-trained models, this implementation builds the core NST logic manually, making it a perfect blend of theoretical learning and practical creativity.

---

## 🧠 How It Works

1. **Extract features** from a pre-trained VGG19 model (content & style layers)
2. **Compute losses**:
   - Content loss: Difference in high-level features of the content image and generated image
   - Style loss: Gram matrix difference between style image and generated image
3. **Optimize** the generated image using gradient descent to minimize total loss
4. **Visualize & Save** the styled image!

---

## ✨ Features

- Custom feature extraction from **VGG19**
- Gram matrix computation for **style loss**
- **GradientTape optimization** from scratch
- Adjustable `content_weight` and `style_weight`
- Clean, modular code structure for learning or enhancement

---

## 🛠️ Tech Stack

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- PIL (Image Processing)



🔬 What I Learned

Implementing NST from scratch using feature loss engineering
Deep understanding of VGG19 architecture
Use of Gram matrices for style representation
Custom optimization using tf.GradientTape
Hyperparameter tuning for style vs content balance



🚀 Future Enhancements

To further develop this project:

📹 Extend to videos with temporal consistency (see nst-video roadmap)
🧪 Add a Fast Style Transfer variant (real-time inference)
🖼️ Implement Multi-style blending
🌐 Convert into a Flask or Streamlit web app
📱 Deploy on mobile using TensorFlow Lite






