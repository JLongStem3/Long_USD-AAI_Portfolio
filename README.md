# USD-AAI_Portfolio

Welcome this repository is a collection of projects and assignments that I have collected throughout my experience as a Master's Student at the University of San Diego studying their Applied Artificial Intelligence program. Many of the projects included are of my own individual work, some however began as a team/group project, which then I later revise and adjusted to fit my portfolio. With a Bachelors in Physics and prior experience working with AutoCad, and 3D simulation, I am relatively new to GitHub as a portfolio reference. I hope you tag along, enjoy the journey and reach out to me if interested in any research ideas! Thank you,
___
**[(1) AI Fundamentals & Applications](https://github.com/JLongStem3/Long_USD-AAI_Portfolio/tree/main/AI%20Fundamentals%20%26%20Application%20-%20Prediction%20Model)**  
This project explores the fundamentals of Artificial Intelligence (AI) by comparing two machine learning algorithms, Random Forest and XGBoost, for predictive analysis using the [Heart Disease Prediction](https://www.kaggle.com/datasets/rishidamarla/heart-disease-prediction) dataset. Exploratory Data Analysis (EDA) reveals key trends, such as a strong correlations and highlights imbalances that may introduce bias. Evaluation metrics indicate XGBoost delivers improved accuracy, precision, and recall, however, both models exhibit challenges in identifying all positive cases, suggesting further refinement is required. This project emphasizes the iterative nature of machine learning development and the importance of tailored approaches for real-world applications.

_Files:_  
_Heart_Disease_Prediction.csv = Dataset_
_Long_AI_Fundamentals.ipynb = Notebook_
_Long_AI_Fundamentals_Notebook.pdf = pdf version_

___
**[(2) Computer Vision (Exercise) - Object Detection](https://github.com/JLongStem3/Long_USD-AAI_Portfolio/tree/main/Computer%20Vision%20(Exercise)%20-%20Object%20Detection)**  
This project introduces key computer vision concepts through a three-part assignment involving video processing, pose estimation, and real-time object detection. We use OpenCV to read a video, extract metadata, and apply filters to create a sketch effect. Then we focus on _pose estimation_ using TensorFlow Hub to analyze movements in a GIF format video. Lastly we implement real-time object detection with YOLOv8 and a webcam, integrating pre-trained models for live camera feed capture. Note you must provide your own video files (video/path) to use the code effectively. The assignment emphasizes hands-on learning with tools like Google Colab, OpenCV, and TensorFlow, progressively building skills in video analysis and AI-based detection techniques.  

_Files:_  
_YOLO for Object Detection.ipynb = Stand Alone Notebook_

___
**[(3) Natural Language Processing](https://github.com/JLongStem3/Long_USD-AAI_Portfolio/tree/main/Natural%20Language%20Processing)**  
In this study we build a chatbot by leveraging the [Ubuntu Dialogue Corpus](https://www.kaggle.com/datasets/rtatman/ubuntu-dialogue-corpus), a vast dataset containing nearly one million dialogues from Ubuntu support chats. We train a chatbot on a focused subset of dialogueText_196 we used for processing. We used a pretrained transformer-based GPT architecture. Once trained, the chatbot was integrated into a user-friendly interface. Responses are displayed within the notebook for easy tests and continuing research. The project demonstrates how naturally occurring dialogue data can enhance a chatbot’s ability to engage users effectively.  

_Files:_  
_Chatbot_Ubuntu.ipynb = Notebook (Run the code from the checkpoint to access the chatbot)_
_checkpoint-500 = Model (Load this model checkpoint to prevent retraining)_  

![Chatbot](https://github.com/user-attachments/assets/692bd8df-3942-40d6-afe9-8ea3c73d0e4d)
