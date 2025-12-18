# Task 05: Neural Style Transfer

## 📌 Overview
Neural Style Transfer is a technique in which the **style of one image**
(such as a famous painting) is applied to the **content of another image**
(such as a photograph).

The final output image keeps the **structure of the content image**
but looks like it was painted in the **artistic style** of the style image.

---

## 🎯 Objective
To implement Neural Style Transfer using deep learning and generate
an artistic image by combining:
- **Content Image** – what the image shows
- **Style Image** – how the image looks

---

## 🧠 How It Works (In Simple Words)
1. A pre-trained CNN model (VGG19) is used.
2. The model extracts:
   - Content features from the content image
   - Style features from the style image
3. A new image is created and updated repeatedly.
4. The final image looks like the content image painted
   in the style of the style image.

---

## 🛠 Tools & Technologies Used
- Python
- PyTorch
- TorchVision
- Pre-trained VGG19 model
- NumPy
- PIL (Image Processing)

---

## 📂 Project Files
