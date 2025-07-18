# Emotion Classification from Social Media Usage 

This project explores whether emotional states can be predicted using only **behavioral metrics from social media**, such as usage time, messaging frequency, and likes received. Using a Kaggle dataset of 1,000 users, we trained and compared **48 supervised machine learning models**.

## Key Features
- Dataset: "Social Media Usage and Emotional Well-Being" by Emirhan Bulut (Kaggle)
- Models: KNN, Neural Networks, SVM, Naive Bayes, Logistic Regression
- Best Model: **KNN (k=6)** with **85% accuracy**
- Focus: Predict emotions (Happiness, Sadness, Anxiety, etc.) using only numeric user behavior data

## Main Findings
- Emotions like **Happiness**, **Anxiety**, and **Sadness** are strongly distinguishable via digital behavior
- Linear models underperformed due to non-linear data patterns
- Behavior-based ML can potentially support ethical emotion-aware systems

## Files Included
- `train.csv`: Complete Dataset with 1000 users data from [Data Source]((https://www.kaggle.com/datasets/emirhanai/social-media-usage-and-emotional-well-being?phase=FinishSSORegistration&returnUrl=%2Fdatasets%2Femirhanai%2Fsocial-media-usage-and-emotional-well-being%2Fversions%2F1%3Fresource%3Ddownload&SSORegistrationToken=CfDJ8E2Q1d-RsbJJgqYMf1tS3xICwQ6HiENqiXQDS2PEgnpN2WWI23NZ73Ss7yNxY2UzNJSlZyscT-N1NUzNmpG5I8q7wycYQ8z9_WfaXi9zx4dsp0sE0LBA3oi7fGhnakty9e0XEAKVLabrX6djx0rZhs5UGpZ3XLALivANy_9Txz54lJgDyooVNxGTvSJa3OE-UHO6ipizEDL544wfxNKlxTAPKQ24Tv9bQbDEOz_Ai6fWNf0PniMtzKex3IajueFp9SLLnjn62cwHSECA1w_bp5P1HcspflXPA-TPVl9nomLL64ruHbPSVWdfdooAzibQFLasjnpNnk9XnoA8BhRuJwkzJX81ahJWBg&DisplayName=Srishti+VERMA))
- `Emotional_State_and_Social_Media.ipynb`: Full code for model building, evaluation, and visualization
- `Beyond_Posts_and_Likes.pdf`: Final research paper
- 

##  Citation
If you use this project, please cite:  
**Verma, Srishti.** *"Beyond Posts and Likes: Predicting Emotions from Social Media Usage with Supervised Machine Learning"* (2025)

## Contact
Made by  [Srishti Verma](mailto:verma.srishtee@gmail.com)
