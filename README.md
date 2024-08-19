# Yoga Pose Detection and Correction

## Abstract
The primary aim of this project is to ensure proper yoga postures using computer vision techniques, reducing the risk of injuries from incorrect poses. By leveraging PoseNet and a KNN classifier, the system offers real-time guidance for various yoga poses, helping users practice yoga safely at home. The model identifies discrepancies between actual and target poses and provides corrective feedback with high accuracy.

## Introduction
Yoga, an ancient practice, requires precise postures to be effective and safe. Incorrect poses can lead to injuries, making the presence of a trainer crucial. However, not everyone has access to personal trainers, leading to the development of an AI-based application that detects and corrects yoga poses using real-time feedback.
The proposed system uses a dataset of 1,578 images representing five yoga poses. The KNN classifier, trained on this dataset, detects significant keypoints using PoseNet. The system then provides real-time feedback by comparing the user's pose with the trained model, displaying an instructor video for guidance.

## [Read the Research Paper](https://www.irjet.net/archives/V9/i4/IRJET-V9I4223.pdf)
