# CISC 480 Senior Portfolio

## Overview

This repository serves as my senior portfolio for **CISC 480 – Senior Capstone** at the University of St. Thomas. It collects and contextualizes three projects completed during my time as a computer science student:

- A deep learning **Pneumonia Detector** for chest X-ray classification  
- A **Handwritten Digit Recognition** model using a Convolutional Neural Network (CNN)  
- A personal **Portfolio Website** hosted with GitHub Pages  

Each linked repository includes its own detailed `README.md` with an overview, installation instructions, and usage guidance. This portfolio focuses on *why* I chose to highlight these projects and how they connect to my growth as a developer and to the St. Thomas mission of using knowledge and skills to advance the common good.

---

## Project 1: Pneumonia Detector (DenseNet121 · PyTorch)

**Repository:** [Pneumonia-Detector](https://github.com/thomas-sabu-cs/Pneumonia-Detector)

This project implements a pneumonia detector using chest X-ray images and a **DenseNet121** backbone in **PyTorch**. It includes a full training pipeline on the Kaggle pneumonia dataset, class imbalance handling, Grad-CAM visualizations for model explainability, and a **Gradio** web interface for uploading X-rays and receiving predictions. The project is explicitly framed as a research and educational tool rather than a clinical system, but it demonstrates how modern deep learning techniques can be applied to real-world medical imaging problems.

I chose this project because it represents a clear step beyond “toy” examples and engages with a meaningful application domain: **healthcare**. Working on it pushed me to think carefully about data ethics, dataset bias, evaluation metrics (AUC, confusion matrices), and model interpretability—especially important when predictions could influence human health decisions. This aligns with the St. Thomas emphasis on **acting wisely and working skillfully to advance the common good**: even in an academic setting, I had to consider how AI tools can support, but never replace, human expertise and responsibility.

---

## Project 2: Handwritten Digit Recognition with CNN (MNIST)

**Repository:** [Handwritten-Digit-Recognition-with-CNN](https://github.com/thomas-sabu-cs/Handwritten-Digit-Recognition-with-CNN)

This project builds a **Convolutional Neural Network** in **TensorFlow/Keras** to classify handwritten digits (0–9) from the **MNIST** dataset. The notebook walks through data loading and preprocessing, CNN architecture design, model training, evaluation, and visualization (including accuracy/loss curves and a confusion matrix). It serves as a solid, end-to-end example of how to approach an image classification problem, from raw data to an evaluated model.

I chose to highlight this project because it represents a key **foundational milestone** in my machine learning journey. Implementing and tuning a CNN on MNIST helped me internalize core concepts—convolutions, pooling, activation functions, overfitting, and regularization—that I then applied in more complex projects like the Pneumonia Detector. In terms of the St. Thomas mission, this project reflects **critical thinking and disciplined learning**: mastering fundamental tools and theory so they can later be used in service of more impactful applications.

---

## Project 3: Personal Portfolio Website

**Repository:** [Website](https://github.com/thomas-sabu-cs/Website)  
**Live Site:** [thomas-sabu-cs.github.io/Website](https://thomas-sabu-cs.github.io/Website)

This project is a personal **portfolio website** built and deployed using **GitHub Pages**. The site presents my background, skills, and selected projects in a way that is accessible to a broad audience—classmates, faculty, and potential employers. The repository tracks the full history of the site’s development, including layout, styling, and content updates.

I chose this project because it highlights another essential dimension of computer science work: **communication and presentation**. It is not enough to build interesting models and systems; we also need to explain them clearly, organize them coherently, and make them discoverable. This site is my attempt to do that. It connects to the St. Thomas mission by emphasizing professional formation and **lifelong learning**—using technical skills not only to solve problems, but also to present myself as a responsible, reflective practitioner who is prepared to contribute to the common good beyond the classroom.

---

## How to Use This Portfolio

Each section above links directly to the underlying project repository. For each project, you will find:

- A detailed `README.md` with **Overview**, **Installation Instructions**, and **Usage Instructions**
- Source code and/or notebooks demonstrating the implementation
- Additional documentation or assets where appropriate (e.g., images, notebooks, scripts)

This `senior-portfolio` repository is intended as the central entry point: it explains why these projects were selected, how they fit together in my academic development, and how they reflect the mission and values of the University of St. Thomas.
