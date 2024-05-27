<h1 align="center">Skin Cancer Classification using Computer Aided Diagnosis</h1>
<div align="center">
  <img src="https://github.com/shahdhairya51/skin-cancer-classification/blob/main/readme_images/05.png" alt="Skin Cancer Classification">
</div>

##  [💻 Website Link](https://skinvision-ai.onrender.com/)

# Abstract

Skin cancer is a prevalent type of cancer worldwide, and early diagnosis is critical for effective treatment. Our system uses a deep learning model trained on a vast dataset of skin images to classify skin cancer into its different types. The model achieves high accuracy and outperforms existing systems. The system can be accessed through a user-friendly web interface, where users can upload skin images and receive a diagnosis in real-time. This AI-based skin cancer classification system has the potential to improve early detection rates and enhance patient outcomes. After integration into workflow, dermatologists and healthcare professionals can make more informed decisions about the diagnosis and treatment of skin lesions.

# Introduction

Skin cancer is a serious and growing health concern, affecting millions of people worldwide. Early detection and accurate diagnosis are crucial for improving patient outcomes, yet current diagnostic methods can be time-consuming and error-prone. This is where machine learning comes in. By leveraging large amounts of data and powerful algorithms, machine learning has the potential to revolutionize the field of skin cancer classification. In this presentation, we will explore the importance of skin cancer classification using machine learning, including its potential to improve diagnosis accuracy, reduce diagnostic time, and ultimately save lives. We will also examine some of the cutting-edge techniques being used today, as well as some of the challenges and opportunities that lie ahead.

## The Problem We Tried to Solve

The first step for a dermatologist to identify whether a skin lesion is malignant or benign is to perform a skin biopsy. In the skin biopsy, the dermatologist takes a sample of the skin lesion and examines it under a microscope. The current process takes almost a week or more, from getting a dermatologist appointment to receiving the biopsy report. This project aims to shorten the current gap to just a couple of days by providing a predictive model using **Computer-Aided Diagnosis (CAD)**. The approach uses **Convolutional Neural Network (CNN)** to classify nine types of skin cancer from lesion images. This reduction of the gap has the potential to positively impact millions of people.

## Motivation

A dermatologist performs a skin biopsy to determine if the skin lesion is benign or malignant (cancerous). The dermatologist removes a portion of the skin lesion during the biopsy and studies it under a microscope. Currently, obtaining a dermatologist appointment and receiving a biopsy report takes around a week or more. The goal of this research is to use computer-aided diagnosis (CAD) to provide a prediction model that will reduce the present gap to a matter of days. The method analyzes photos of lesions to classify nine different forms of skin cancer using convolutional neural networks (CNN). This gap closing has the potential to favorably affect millions of individuals. Our AI model will be able to reach a high level of accuracy and generalization on unseen data, which is an important factor for clinical adoption.

## Data Set

[Kaggle Dataset: Skin Cancer MNIST: HAM10000](https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000)

## Proposed Methodology

<div align="center">
  <img src="./readme_images/methodology.png" alt="Methodology">
</div>

## Results

<div align="center">
  <img src="./readme_images/01.png" alt="Home Page">
  <p>Fig: Home page for dermatologists to upload skin lesions</p>
</div>

<div align="center">
  <img src="./readme_images/02.png" alt="About Page">
  <p>Fig: About Page</p>
</div>

<div align="center">
  <img src="./readme_images/03.png" alt="Lesion Analysis and Results">
  <p>Fig: Lesion Analysis and Results</p>
</div>

## Conclusion

With high levels of accuracy, sensitivity, and specificity achieved by state-of-the-art models, dermatologists and healthcare professionals can make more informed decisions about the diagnosis and treatment of skin lesions, potentially leading to better patient outcomes. The ability of these models to provide quick and accurate diagnoses could also help to reduce patient anxiety and improve overall satisfaction with care. Computer-Aided Diagnosis (CAD) will quickly analyze the data, generate the results, and help save lives.

## Steps to Run this Repository

1. Install dependencies: `npm install`
2. Start the application: `npm start`
3. Open [localhost:3000](http://localhost:3000) in your web browser
