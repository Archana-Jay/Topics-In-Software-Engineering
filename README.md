# Topics-In-Software-Engineering

# Unanswered Questions Identification in QA Dataset

## Overview
This repository contains the code and dataset for a study proposing a quantitative approach to identify unanswered questions in a QA (Question Answering) dataset using machine learning models. The aim of this project is to develop a recommendation system capable of distinguishing between answered and unanswered questions based on a set of features extracted from the dataset.

## Dataset
The dataset used in this study consists of five CSV files containing Stack Overflow questions and their corresponding answers. Each file contains questions along with their creation dates. For the purpose of this study, questions that have not received responses within the last 5 years or more are considered unanswered. 

## Approach
1. **Data Preparation:** The dataset is combined to show both answered and unanswered questions before splitting it into training and test sets.
2. **Feature Extraction:** Features are extracted from text data, including various linguistic and semantic features.
3. **Model Training:** Machine learning models are applied to estimate the accuracy of detecting unanswered questions. Several models are evaluated to determine the most effective approach.
4. **Evaluation:** The results demonstrate the accuracy of the proposed approach in identifying unanswered questions in a QA dataset.

## Results
The study demonstrates that the proposed method accurately identifies unanswered questions in a QA dataset. The findings suggest that this approach could be valuable for building automated systems to assist in managing large QA databases by highlighting unanswered questions that require attention.

## Repository Structure
- **data:** Contains the CSV files comprising the Stack Overflow questions and answers dataset.
- **code:** Includes the code for data preprocessing, feature extraction, model training, and evaluation.
- **results:** Contains the results of the experiments conducted in the study.
- **README.md:** Provides an overview of the project and instructions for running the code.

## Usage
1. Clone the repository
2. Navigate to the project directory:
3. Install dependencies
4. Run the code files in the colab to preprocess the data, extract features, train models, and evaluate performance.

## Contributors
Archana Jayaraman
Chandrasekaran Subramanian Ravichandran
Hina Sabreen Ahmed 
Arunkumar Sasikumar
