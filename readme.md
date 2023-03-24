# Warfarin Dosage Prediction

This project aims to predict the optimal dosage of warfarin for patients using a Contextual Multi Arms Bandit Reinforcement Learning algorithm. The project achieved an accuracy of 68.09 percent, which is comparable to other state-of-the-art methods, such as Pharmacogenetic Dosage Algorithm with an accuracy of 68.75 percent, Clinical Dosage Algorithm with an accuracy of 66.11 percent, and Baseline Fixed Algorithm with an accuracy of 61.17 percent.

## Problem Statement

Warfarin is an anticoagulant medication used to prevent blood clots. The optimal dosage of warfarin varies among patients due to genetic and clinical factors. Determining the correct dosage is challenging and requires multiple blood tests to monitor the patient's response to the medication.

In this project, we aim to develop a machine learning model that can predict the optimal dosage of warfarin for individual patients based on their clinical and genetic information.

## Dataset

The dataset used in this project is the Warfarin Dosing dataset, which contains clinical and genetic information of 5,700 patients who were prescribed warfarin. The dataset contains 65 features, including age, gender, race, weight, height, and genetic information such as VKORC1 and CYP2C9 variants.

## Approach

We used a Linear UCB Contextual Multi Arms Bandit Reinforcement Learning algorithm to predict the optimal dosage of warfarin. The algorithm considers the patient's clinical and genetic features as contextual information and learns from the patient's response to the medication to update the dosage recommendation.

We compared our algorithm's performance with other state-of-the-art methods, such as Pharmacogenetic Dosage Algorithm, Clinical Dosage Algorithm, and Baseline Fixed Algorithm.

## Results

Our algorithm achieved an accuracy of 68.09 percent, which is comparable to other state-of-the-art methods. The Pharmacogenetic Dosage Algorithm had an accuracy of 68.75 percent, the Clinical Dosage Algorithm had an accuracy of 66.11 percent, and the Baseline Fixed Algorithm had an accuracy of 61.17 percent.

## Conclusion

In this project, we developed a machine learning model that can predict the optimal dosage of warfarin for individual patients based on their clinical and genetic information. Our algorithm's performance is comparable to other state-of-the-art methods and can help clinicians make better-informed decisions about the dosage of warfarin to prescribe.

## References 
https://web.stanford.edu/class/cs234/CS234Win2019/default_project/default_project.pdf
