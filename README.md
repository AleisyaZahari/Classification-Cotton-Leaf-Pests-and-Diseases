# Classification of Cotton Leaf Diseases and Pests Using Convolutional Neural Network (CNN)

## Overview
This project aims to classify **cotton leaf diseases and pests** using a **Convolutional Neural Network (CNN)**. The model is built from scratch to assist farmers in detecting plant diseases and pests early, achieving a **classification accuracy of 91%**.

## Author
**Aleisya Zahari Salam**  
Department of Mathematics, Faculty of Mathematics and Natural Sciences, Universitas Pamulang  

## Research Advisor
**Yulianti Rusdiana, S.Si., M.Sc.**

## Abstract
Cotton is essential for the **textile and food industries**, making its cultivation a priority. However, it is susceptible to various **diseases and pests** that affect crop yields. **Manual identification** is often **inaccurate and time-consuming**, necessitating a more efficient solution.

This study utilizes **digital image processing** and the **CNN method** to classify cotton leaf diseases and pests. The dataset consists of **six categories**:
- **Diseases**: Bacterial Blight, Powdery Mildew, Target Spot
- **Pests**: Aphids, Army Worm
- **Healthy Leaves**

The dataset is split into **training (75%), validation (15%), and testing (10%)**. Data preprocessing and augmentation techniques were applied. The model was trained for **23 epochs** with a **batch size of 16**, correctly classifying **330 out of 361 images**, achieving **91% accuracy**. The results indicate the CNN model’s strong ability to classify cotton leaf diseases and pests.

---

## Problem Identification
- **Various cotton diseases**, such as Bacterial Blight, Powdery Mildew, and Target Spot, affect plants at different growth stages.
- **Pests like Aphids and Army Worms** damage leaves and reduce cotton yield, causing **economic losses**.
- **Manual identification** by farmers is **inefficient, time-consuming, and prone to errors**, leading to delayed detection and improper treatment.
- **Misidentification of diseases and pests** can result in the **incorrect use of pesticides**, negatively impacting cotton production.

## Problem Formulation
1. **How effective is the classification of cotton leaf diseases and pests using the CNN method?**
2. **What level of accuracy can be achieved in the classification of cotton leaf diseases and pests using CNN?**

## Methodology
### **1. Data Collection**
- The dataset consists of **labeled images of cotton leaves** affected by various diseases and pests.
- Images are preprocessed and augmented to enhance model performance.

### **2. Model Architecture**
- A **custom CNN model** is designed from scratch to classify six categories.

### **3. Training and Evaluation**
- The dataset is split into **train (75%), validation (15%), and test (10%)**.
- The model is trained using **categorical crossentropy loss** and **Adam optimizer**.
- Achieved **91% classification accuracy**.

### **4. Testing**
- The model was tested on **unseen data** to evaluate its performance in real-world scenarios.

## Results
Using the **CNN method**, the classification results were:
- **Aphids**: **58** correctly classified, **7** misclassified.
- **Army Worm**: **56** correctly classified, **4** misclassified.
- **Healthy Leaves**: **60** correctly classified (**100% accuracy**).
- **Bacterial Blight**: **53** correctly classified, **7** misclassified.
- **Target Spot**: **52** correctly classified, **9** misclassified.
- **Total Correctly Classified Images**: **330 out of 361**.
- **Final Model Accuracy**: **91%**.

These results indicate that the CNN model is **highly reliable** in classifying cotton leaf diseases and pests.

---

## Future Work
To enhance the effectiveness of the model, the following improvements can be made:
- **Expand the dataset** to include more types of diseases and pests.
- **Explore pre-trained models** such as **YOLO or ResNet** for potentially higher accuracy.
- **Deploy the model** as a **mobile or web-based application** to allow farmers to use it in real-time.

---

This research demonstrates the potential of **deep learning-based image classification** for assisting farmers in diagnosing cotton plant diseases and pests accurately. Further improvements can increase its real-world usability and impact.

