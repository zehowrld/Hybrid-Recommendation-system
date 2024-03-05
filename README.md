# Recommendation System Project

## Overview
This project focuses on building a recommendation system using deep neural network (DNN) models, particularly softmax, to address the limitations of matrix factorization. The recommendation system aims to provide personalized recommendations to users based on their preferences and interactions with items.

## Key Features
- Utilizes DNN models to incorporate query features and item features, enhancing the relevance of recommendations.
- Implements softmax DNN model architecture, treating the recommendation problem as a multiclass prediction task.
- Handles input features including dense features (e.g., watch time) and sparse features (e.g., watch history).
- Introduces the concept of softmax embeddings to represent items and queries.
- Addresses issues such as folding and scalability through techniques like negative sampling and approximate nearest neighbors.
- Discusses various considerations including freshness, diversity, fairness, and positional bias in recommendation systems.
- Provides insights into candidate generation, scoring, and re-ranking stages of the recommendation pipeline.

## Results
- **Training Loss**: 5.486163
- **Test Loss**: 5.653057
- **Test Precision at 10**: 0.013340
  
![output](https://github.com/zehowrld/Hybrid-Recommendation-system/assets/69119826/14e3bf63-5a95-43a7-9aab-1f4a79275cc2)

## Contents
- **Softmax DNN for Recommendation**: Explanation of the softmax DNN model architecture, input features, model training, loss function, embeddings, and comparison with matrix factorization.
- **Softmax Training**: Details on the training data, negative sampling, folding phenomenon, and strategies for handling large-scale retrieval.
- **Scoring**: Discussion on candidate generation, scoring, and the importance of choosing an appropriate objective function.
- **Re-ranking**: Overview of re-ranking strategies and considerations for improving recommendation quality.
- **Topics Covered**: Summary of the technical topics covered in the project, including building and training softmax models, visualizing embeddings, and using TensorFlow for recommendation systems.

## Usage
To use the recommendation system:
1. Set up the necessary environment with TensorFlow and required dependencies.
2. Preprocess the data and prepare input features including dense and sparse features.
3. Choose the appropriate model architecture (softmax DNN) based on the project requirements.
4. Train the model using training data, incorporating techniques like negative sampling and folding reduction.
5. Evaluate the model performance and tune hyperparameters as needed.
6. Deploy the trained model for recommendation purposes, considering scalability and efficiency.

## Credits
This project is based on the comprehensive understanding of recommendation systems and deep learning techniques derived from various sources, including online tutorials, research papers, and practical experience in building recommendation systems.
