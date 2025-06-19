---
title: Deception Detection
description: "This project is about automatic deception detection in video call situations, based on video and audio cues."
background: /assets/theme/images/layout1_overview_onlyImage.jpg
                                 
permalink: /project/
---

{: .alert .alert-warning}
 
* todo: project image 
![image](/deception/assets/theme/images/project_img.jpg)

## Motivation
Deception detection is a complex, multidisciplinary field that has gained increasing attention through advances in AI.
While traditional polygraph tests are still in use, automated and less invasive methods based on computer vision and machine learning are being explored — not only in criminalistics and border control, but increasingly in economic contexts.

In digital markets, deception (e.g., misleading product claims) can harm both consumers and honest providers. Despite people’s confidence in their ability to detect deception, research shows their accuracy is only slightly above chance — while they also tend to underestimate how well they can deceive others.
Automated systems could therefore provide valuable support in remote interactions such as virtual sales or consultations.
This project explores the capabilities and limitations of deception detection systems, along with their potential impact on society.

## Goals and Procedures
In this project, we acquired a new dataset for video-based deception detection in low-stake, economic contexts: the Buyer-Seller-Deception-Game (GAME) Dataset. 
It contains webcam-based negotiations in a generalized, abstract market setting — designed to capture core dynamics of real buyer-seller interactions without tying them to specific products.

We apply both deep learning and traditional machine learning approaches to extract cues from video and audio modalities — including Action Units, emotion intensities, gaze direction, head pose, and also audio features as prosody or energy.
In a second step, we train deception detection models on these cues using our dataset as well as five additional publicly available datasets. This allows us to evaluate both the quality of the extracted cues and their sensitivity to contextual factors, such as the type of deceptive scenario.

## Innovation and Perspectives
Unlike previous work that focuses on high-stake scenarios or simplified tasks (e.g., stating whether an image is real or not), this project addresses realistic, everyday online contexts.
The GAME dataset is the first of its kind to target low-stakes deception detection in an economic setting based on actual interaction and incentives.

We compare a range of novel deep learning-based features developed in our group with established tools such as OpenSmile and OpenFace, testing them across different datasets to assess how context-dependent these cues are.
Additionally, we investigate user attitudes towards online-compatible deception detection systems, and how their presence may affect seller deception or improve buyer decision-making.

The GAME dataset will be made freely available for research, supporting the responsible development of explainable AI systems for future remote communication applications.
In our future project, we will further adress additional approaches of deception detection,  including hand gestures, vital parameters and a comparison of RBG vs Thermal camera cues.

![image](/deception/assets/theme/images/dfg_logo_englisch_blau_en.gif)
