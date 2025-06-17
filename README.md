**Crowd Counting using CSRNet with Attention Mechanism**
---
**📌 Overview**

This project implements a crowd counting system based on CSRNet (Congested Scene Recognition Network) enhanced with an Attention Mechanism to improve performance in densely populated scenes. The model is designed to generate high-quality density maps from input crowd images, providing accurate estimations of the number of people in each scene.

---
**🧠 Key Features**

**CSRNet Backbone**: Uses VGG-16 frontend for feature extraction and dilated convolutions in the backend to expand the receptive field without losing resolution.

**Attention Module**: Integrates a channel and/or spatial attention mechanism to enhance feature representations and focus on important regions in the image.

**High-Resolution Density Maps**: Generates smooth and precise density maps for accurate counting.

**Support for Standard Datasets:** Compatible with popular crowd counting datasets like ShanghaiTech (Part A & B) and UCF-QNRF.

---
**Dataset**
![Image](https://github.com/user-attachments/assets/032d4e7a-0b8d-40c5-8133-50d9d25b9291)

---

**Prediction**
![Image](https://github.com/user-attachments/assets/032d4e7a-0b8d-40c5-8133-50d9d25b9291)
