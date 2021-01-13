---
title: "Machine Learning Gait Stimulation"
layout: archive-no-title
excerpt: "Machine learning based electrical stimulation to assist neurological patients' gait <br><img src='/images/confusionmatrix.PNG' width='400' height='400'/><br>"
collection: portfolio
---

# Machine Learning Based Electrical Stimulation to Assist Neurological Patients' Gait

[**Evolution Devices**](https://www.evolutiondevices.com/) is a company in Berkeley, CA, which uses Functional Electrical Stimulation to assist walking in patients of neurological conditions such as stroke and MS. The **EvoWalk** device is a smart wearable device which is unobtrusive and can wirelessly track motion data and adjust stimulation, and is backed by partners such as the NSF and Toyota Mobility Foundation. 

In conjunction with **Evolution** and **UC Berkeley**, I led a team of graduate students who worked on ways to personalize these stimulation patterns depending on the patient's gait pattern. One project we worked on involved developing a **Convolutional Neural Network** to classify different types of gait based on kinematic data. Our model is able to distinguish between **6 different gaits** with **87% accuracy**, and can be modified to use raw acceleration data from on-body sensors for real-time imputation, or use 3D motion capture to track joint angles during walking. 

Our project brief can be seen [here](/files/ML Gait Stimulation.pdf). 

<br>

Example of the motion-capture gait lab and sample joint angle output:

<img src='/images/ourangles.png' width='750' height='500'/>

&emsp; <img src='/images/swing1.PNG' width='750' height='500'/>