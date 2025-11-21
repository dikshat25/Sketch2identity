<h1 align="center">
  <br>
  Sketch2Identity
</h1>

<div align="center">
   AI-Powered Sketch-to-Photo, Age Progression & Identity Retrieval System
</div>
<hr>

<details>
<summary>Table of Contents</summary>

- [Description](#description)
- [Problem Statement](#problem-statement)
- [Links](#links)
- [Tech Stack](#tech-stack)
- [Progress](#progress)
- [Future Scope](#future-scope)
- [Applications](#applications)
- [Project Setup](#project-setup)
- [Usage](#usage)
- [Team Members](#team-members)
- [Screenshots](#screenshots)

</details>

## 📝Description

**Sketch2Identity** is a forensic AI system that reconstructs a **realistic human face from a hand-drawn sketch**, applies **age progression**, and finally performs **identity retrieval** using facial embeddings.  
This system is designed to support **law enforcement, investigation units, and forensic artists** by automating the traditionally slow and inaccurate manual sketch-based identification workflow.

The project integrates:
- **IsGAN** → Sketch-to-photo generation  
- **StyleGAN / Aging Pipeline** → Age progression  
- **InsightFace + KNN** → Identity retrieval  
- **EDA, augmentation & preprocessing** → Dataset quality improvement  

This makes Sketch2Identity a complete end-to-end forensic recognition pipeline.

---

## ❗Problem Statement

Traditional forensic sketch-based identification is:
- Slow  
- Artist-dependent  
- Prone to human error  
- Inaccurate when matching with large police databases  
- Not reliable when sketches are old or the person has aged  

**Sketch2Identity solves this by converting sketches to realistic images, aging them, extracting identity embeddings, and retrieving matches from a database automatically.**

---

## 🔗Links

- **GitHub Repository**  
  *(Add once uploaded)*  
  https://github.com/your-username/Sketch2Identity

- **📂 Drive Folder (Models, Outputs, Screenshots, Results)**  
  📌 *Click below:*  
  https://drive.google.com/drive/folders/YOUR-FOLDER-ID-HERE

- **Dataset (CUHK Face Sketch Dataset)**  
  https://www.ee.cuhk.edu.hk/~xgwang/CUFS.html

---

## 🤖Tech-Stack

### **Deep Learning / ML**
- PyTorch  
- IsGAN  
- StyleGAN / Synthetic Aging Pipeline  
- InsightFace  
- KNN Classifier  

### **Python Libraries**
- NumPy  
- Pandas  
- OpenCV  
- Pillow  
- Scikit-learn  
- Matplotlib  
- ONNX Runtime  

### **Tools**
- Google Colab  
- Jupyter Notebook  
- Drive Model Loading  

---

## 📈Progress

### ✔ Fully Implemented Features
- Sketch-to-photo translation using **IsGAN**
- Identity-preserving generation  
- Age progression (+20 to +40 years)  
- InsightFace embedding extraction  
- KNN retrieval with **Top-1 / Top-5 accuracy**  
- Complete EDA + dataset quality scoring  
- Augmented dataset: flip, blur, brightness enhancement  
- CSV-based age estimation generated via InsightFace  
- Automated inference pipeline  

### 🔧 Partially Implemented
- Integration of real pretrained WrinkleGAN / CAAE models  
- End-to-end GUI panel for upload & processing  

---

## 🔮Future Scope

- Train a custom GAN on larger datasets  
- Add sketch enhancement (denoising + structural correction)  
- Multi-angle sketch reconstruction  
- Web-based deployment with real-time inference  
- Crime database integration API  
- Add super-resolution module to handle poor sketches  
- Use transformer-based vision encoders for better identity matching  

---

## 💼Applications

Sketch2Identity can be used for:

- 👮 **Forensic sketch matching**  
- 🔍 **Crime suspect identification**  
- 🧓 **Age progression for missing persons**  
- 🧭 **Cold case investigations**  
- 🧬 **Cross-modality identity retrieval**  
- 📁 **Police database automation**

---

## 🛠 Project Setup

Clone the repository:

```bash
git clone https://github.com/your-username/Sketch2Identity
cd Sketch2Identity
