# YOGGUIDE
## Problem Statement
#### Regular yoga practices can reduce causes of their suffering. As a result, it has become growing massively and increasingly over the past few years around the world. However, not everyone can go out to participate in yoga classes because of inconvenient public transportation systems for the old people, mostly people can’t go due to time issue. Therefore, it is important for them to practice Yoga at homes by themselves. However, it is not easy for novice Yoga people, particularly seniors, to find the incorrect parts of their Yoga poses by themselves. Usually people doing yoga poses at home without instructor either do in incorrect manner or overdo the poses which lead to acute pain and long-term chronic problems.

## Method
#### Our approach is based on deep learning approach to classify yoga images from 3 poses mainly reverse-warrior, warrior and plank pose. A CNN (Convolutional Neural Network) is an approach which is used for pose estimation of multi-stage classifier where each stage improves the results of the previous one. For the problem of yoga pose recognition two solutions are proposed and enforced. To detect pose, one uses simple sequential model and the other uses two machine learning models which is posenet pre-build TensorFlow model for the 18 body joints for pose estimation then move through second method which is CNN sequential model for the detection of exercise after doing some prepossessing. We have created CNN model using Keras with tensorflow as backend and saved that model and loaded it into Tkinter(Tk)  framework, which is used as frontend GUI to load images/videos or capture live through camera and then perform classification.
![image](https://user-images.githubusercontent.com/83614728/132245044-f97d0872-d579-4c2d-b170-65c086fa049b.png)

## Desktop Application
#### Following is a snippet of desktop application created using python Tk. We can check results in real time video or add images to classify yoga poses.
![image](https://user-images.githubusercontent.com/83614728/132245528-724a4996-d025-45bc-b254-cf82ffa8f2f2.png)
![image](https://user-images.githubusercontent.com/83614728/132246697-6ef110ab-d839-475d-b2bf-543d00f53e17.png)


