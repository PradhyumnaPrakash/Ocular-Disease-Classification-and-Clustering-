# Ocular-Disease-Classification-and-Clustering-
This repository contains the code for the data preprocessing, model training and model evaluation of the Convolutional Neural Network and K-Means Clustering models I used to classify and cluster ocular diseases present within fundus images. Two datasets have been used for this research: Ocular Disease Recognition (https://www.kaggle.com/datasets/andrewmvd/ocular-disease-recognition-odir5k) and eye_diseases_classification (https://www.kaggle.com/datasets/gunavenkatdoddi/eye-diseases-classification). 3 supervised model architectures (ResNet50, DenseNet121 and VGG16) and 1 unsupervised model (K-Means Clustering) have been trained. The following are the details of the code including environment specifications, seed settings and hardware/runtime profiling. 

# Environment specifications: 
1. Code run on Google Colab.
2. Requirements:
Python 3.10.x
numpy==1.26.4
pandas==2.2.2
scikit-learn==1.4.2
matplotlib==3.8.4
tensorflow==2.15.1
tensorflow-io-gcs-filesystem==0.36.0
protobuf==4.25.3
# If using GPU TF 2.15 on local with CUDA 11.8:
nvidia-cublas-cu11==11.11.3.6
nvidia-cudnn-cu11==8.9.2.26
nvidia-cuda-nvrtc-cu11==11.8.89
}

Seed Settings:
All shuffling algorithms were set to seed = 90. 




 
