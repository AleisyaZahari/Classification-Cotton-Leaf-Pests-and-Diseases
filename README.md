# Classification of Cotton Leaf Diseases and Pests Using Convolutional Neural Network (CNN)
## Overview
This project aims to classify cotton leaf diseases and pests using a Convolutional Neural Network (CNN). The model is built from scratch to help farmers detect plant diseases and pests early, with a classification accuracy of 91%.

## Project Title
Classification of Cotton Leaf Diseases and Pests Using Convolutional Neural Network

## Author
Aleisya Zahari Salam
Department of Mathematics, Faculty of Mathematics and Natural Sciences, Universitas Pamulang

## Research Advisor
Yulianti Rusdiana, S.Si., M.Sc.

## Abstract
Cotton plays an important role in the textile and food industries, making its cultivation a priority. However, cotton is susceptible to various diseases and pests. Manual identification of cotton leaf diseases and pests is often inaccurate and time-consuming, so a more efficient solution is needed. The utilization of technology and information is able to classify the types of diseases and pests of cotton leaves with digital image processing. With the existence of digital images to determine the types of diseases and pests of cotton plant leaves carried out using the Convolutional Neural Network (CNN) method. This research aims to obtain the results of the classification of disease and pest types on cotton plant leaves using the CNN method, and find out how much accuracy is obtained in the classification. The data used are images of cotton plant leaves with six categories, namely Bacterial Blight, Powdery Mildew, and Target spot diseases, Aphids and Army Worm pests, and healthy conditions. The data is divided into three parts, namely training, validation, and test data, with a ratio of 75%; 15%; 10% respectively. Data was preprocessed and augmented. The training model process ended at epoch 23 with a batch size of 16. Of the total 361 images of plant diseases and pests, 330 images were correctly classified. The classification process resulted in an accuracy of 91%, indicating the model's good ability to classify cotton leaf diseases and pests.



## Problem Identification
- Various diseases, such as Bacterial Blight, Powdery Mildew, and Target Spot, can affect cotton plants at different growth stages. Pests like Aphids and Army Worms also damage leaves and hinder cotton production, leading to economic losses for cotton farmers.
- Manual identification of diseases and pests by farmers is often inefficient and inaccurate. Visual inspection by farmers takes a long time and frequently results in delayed detection at early stages, leading to ineffective treatment and further losses.
- Mistakes in identifying diseases and pests may cause farmers to use incorrect treatments, such as pesticides, which negatively impacts cotton yields.

## Problem Formulation
- How effective is the classification of cotton leaf diseases and pests using the Convolutional Neural Network (CNN) method?
- What level of accuracy can be achieved in the classification of cotton leaf diseases and pests using the Convolutional Neural Network (CNN) method?

## Methodology
- Data Collection: The dataset consists of labeled images of cotton leaves affected by various diseases and pests.
- Model Architecture: A custom CNN architecture was designed from scratch.
- Training and Evaluation: The model was trained on the collected dataset and achieved a 91% accuracy rate.
- Testing: The model was tested on unseen data to evaluate its performance in real-world scenarios.

## Results
- Dengan menggunakan metode CNN, 58 citra Aphids terklasifikasi dengan benar, sedangkan 7 citra terklasifikasi salah. Terdapat 56 citra army worm terklasifikasi dengan benar, namun masih terdapat kesalahan prediksi sebanyak 4 citra. Untuk kelas healthy semua data terklasifikasi benar dengan total 60 citra. Terdapat 53 citra bacterial blight terdeteksi dengan benar dan memiliki kesalahan prediksi yang berjumlah 7 citra. Terdapat 52 citra target spot yang terklasifikasi dengan benar, dan 9 citra yang terklasifikasi tidak tepat. Dari total 361 citra, jumlah data yang terklasifikasi benar sebanyak 330 citra.
- Proses klasifikasi jenis penyakit dan hama daun tanama kapas menggunakan metode CNN mendapatkan akurasi sebesar 91%. Hal ini mengindikasikan bahwa model telah berhasil mengenali dan mengklasifikasikan penyakit dan hama pada daun kapas dengan tingkat ketepatan yang cukup tinggi.


## Future Work
Future improvements could include:
- Expanding the dataset to cover more types of diseases and pests.
- Exploring pre-trained models such as YOLO or ResNet for potentially higher accuracy.
- Deploying the model as a mobile or web-based application to allow farmers to use it in real-time.