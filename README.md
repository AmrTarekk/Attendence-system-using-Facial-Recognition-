# Attendence-system-using-Facial-Recognition-
This code helps in facial recognition using facenets (https://arxiv.org/pdf/1503.03832.pdf). The concept of facenets was originally presented in a research paper. The main concepts talked about triplet loss function to compare images of different person to recognize out target.

Description :
This Project consists of 3 Tasks : 
First we have to collect our users data such as Name , ID and Photos Including one face.
Second task will be extracting every photo's 128 element Vectors using our FaceNet Pretrained model 
Later we can verify our user attendence by extracting his face details and classify it using KNN


References:

Florian Schroff, Dmitry Kalenichenko, James Philbin (2015). FaceNet: A Unified Embedding for Face Recognition and Clustering

Our implementation also took a lot of inspiration from the official FaceNet github repository: https://github.com/krasserm/face-recognition
