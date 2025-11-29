# EE8230---Machine-Learning-Final-Project
White Wine Multiclass Classification model for quality metric
Abstract
The goal of this project is to develop a machine learning pipeline designed to perform a multiclass classification model trained for white wine quality assessment. This model was trained using the UCI machine learning repository accessed using the Pycaret database. The training data had removed all of the red wine data and had also removed the type column during the preprocessing stage to accurately target the desired task. Using Pycaret, a random forest classification model was proven to be the optimal choice that contained the following results: accuracy 0.666, AUC 0.3417, recall 0.666, precision 0.6741, f1 0.6527,  f1 0.6527, kappa 0.4778, MCC 0.4855. These findings had shown that machine learning models can be used to predict different white wine inputs using fewer data points compared to deep learning models. Additionally, Pycaret has shown to be useful, due to its capabilities to ease the workload for developing machine learning models; however, due to incompatibility issues, the model specifications must be retrained using scikit learn to allow for website/gradio integration, which can also handle the training and prediction requirements.
YouTube link:
https://youtu.be/Y_XAnU3_nms?si=OFqqJH7dWglux3uB
Hugging face space link:
https://huggingface.co/spaces/kppham/EE8230-Machine-Learning-Project
