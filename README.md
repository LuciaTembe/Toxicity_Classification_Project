# Toxicity_Classification_Project

## 🚀 Project Overview

With the rise of online interactions, ensuring a safe and inclusive digital space is more important than ever. This project focuses on detecting toxic content in social media comments, classifying them into multiple categories to help platforms moderate harmful discussions effectively.

## 🔍 Dataset

The dataset used for this project is sourced from Kaggle's Jigsaw Unintended Bias in Toxicity Classification. It consists of labeled comments from a social media platform, identifying whether a comment contains any toxic content.

## 🏷️ Classification Categories

Each comment is assessed for toxicity and classified into one or more of the following categories:

Toxic 🛑

Severely Toxic ⚠️

Obscene 🤬

Threat 🔪

Insult 😡

Identity Hate 🚫

## 🧠 Models Used

To build an effective classification system, we experimented with three different models:

SDG Regressor 📊 (for probabilistic predictions)

Decision Tree 🌲 (for interpretable rule-based classification)

LSTM (Long Short-Term Memory) 🧠 (for deep learning-based text analysis)

## 📈 Performance & Insights

The LSTM model outperformed traditional machine learning models in detecting nuanced toxic content.

Decision Tree provided quick and interpretable results but lacked accuracy for complex toxic language.

SDG Regressor was useful for weighted classification but struggled with highly imbalanced data.

## 🎯 Future Work
Implement ensemble learning to combine the strengths of multiple models;
Fine-tune hyperparameters for improved accuracy;
Experiment with transformer-based models like BERT for better text comprehension;
Implement ensemble learning to combine the strengths of multiple models.
