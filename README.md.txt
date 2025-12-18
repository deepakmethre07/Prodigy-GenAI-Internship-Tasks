# Generative AI Tasks

This repository contains **five Generative Artificial Intelligence (AI) tasks**
implemented using **Python and Deep Learning**.

The project showcases my practical understanding of **Generative AI techniques**
such as text generation, image generation, probabilistic models, GANs, and neural
style transfer.  


## 📌 Tasks Overview (With Details)

### 🔹 Task 01: Text Generation using GPT-2
**Description:**  
This task uses a pre-trained **GPT-2 transformer model** to generate
human-like text. A short input sentence (prompt) is given, and the model
continues the text in a meaningful way.

**Concepts Used:**
- Natural Language Processing (NLP)
- Transformers
- Text generation

---

### 🔹 Task 02: Image Generation from Text
**Description:**  
In this task, images are generated from text prompts using
**diffusion-based generative models**.  
The model converts a descriptive sentence into a visual image.

**Concepts Used:**
- Diffusion models
- Text-to-image generation
- Creative AI

---

### 🔹 Task 03: Text Generation using Markov Chains
**Description:**  
This task demonstrates a simple **probability-based text generation method**.
Each word is generated based on the previous word using a Markov process.

**Concepts Used:**
- Markov Chains
- Probabilistic modeling
- Basic text generation

---

### 🔹 Task 04: Image-to-Image Translation using pix2pix (cGAN)
**Description:**  
This task uses a **Conditional GAN (pix2pix)** to translate one image into another.
For example:
- Sketch → Realistic image
- Map → Satellite image

**Concepts Used:**
- Generative Adversarial Networks (GANs)
- Conditional GANs
- Image translation

---

### 🔹 Task 05: Neural Style Transfer
**Description:**  
This task applies the **artistic style of one image** to the **content of another image**
using a pre-trained **VGG19 convolutional neural network**.

**Example:**
- Content image: Photograph
- Style image: Painting

**Concepts Used:**
- CNNs
- Feature extraction
- Artistic image generation

## 🛠 Requirements (Libraries Used)

torch
torchvision
transformers
diffusers
numpy
matplotlib
pillow
tqdm
scipy

## 🛠 Tools Used

The following tools and technologies were used to build and run this project:

### 🔹 Programming Language
- **Python (3.8+)** – Used for writing all scripts and implementations

### 🔹 Development Tools

- **Google Colab** – Cloud-based execution with GPU support

## ▶ Where to Run This Project

Run on Google Colab (Recommended)
Best option if your system is slow or you need GPU support.

**Why Colab?**
- Free GPU access
- No installation issues
- Easy to run deep learning code

**Steps:**
1. Open https://colab.research.google.com
2. Upload the project files or individual task scripts
3. Enable GPU:
   - Runtime → Change runtime type → Select GPU
4. Run the code cells

---

## ✅ Recommended Choice

- **Google Colab** for heavy tasks like Image Generation and Neural Style Transfer
- **Local system** for lighter tasks like Markov Chain and GPT-2 text generation

## 👤 Author
**Deepak Methre**
