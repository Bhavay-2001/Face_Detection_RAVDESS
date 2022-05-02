# Face_Detection_RAVDESS


In this project, I used the RAVDESS dataset which is an Audio-Visual Database of 24 professional actors vocalizing two-lexically matched statements. I read the paper "A proposal for Multimodal Emotion Recognition using aural transformers and Action Units on RAVDESS dataset" in which the authors used the OpenFace Library to extract Action Units from the videos of the actors. The OpenFace library is a software developed by CMU to extract facial features. I took external help of extracting the AUs by using the code written AUsFeatureExtractor.py The Action Units were then processed and stored in the form of a dataframe. The data was then used to train two machine learning algorithms - SVM and Random Forest and their precision, recall and f1 score were calculated. 
