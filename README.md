# Amazon Review Sentiment Analysis NLP Project

## Overview

 - This repository contains the code and resources for a sentiment analysis project focused on Amazon product reviews. The project uses Natural Language Processing (NLP) techniques to analyze sentiment from customer reviews on Amazon.
 - Delves into sentiment analysis using two distinct techniques: VADER (Valence Aware Dictionary and sEntiment Reasoner) employing a Bag of Words approach, and the Roberta Pretrained Model from 🤗 Huggingface Pipeline.

## Table of Contents

1. **Introduction and Data Loading**
   - Imports necessary libraries and loads the dataset.

2. **Quick Exploratory Data Analysis (EDA)**
   - Displays a bar plot indicating the distribution of reviews by different star ratings.

3. **Basic NLTK**
   - Demonstrates NLTK functionalities such as tokenization, part-of-speech tagging, and named entity recognition.

4. **VADER Sentiment Scoring**
   - Utilizes VADER to calculate sentiment scores for the text data.

5. **Roberta Pretrained Model**
   - Implements a transformer model (Roberta) for sentiment analysis.

6. **Comparing Scores between Models**
   - Compares sentiment scores obtained from VADER and the Roberta model.

7. **Review Examples**
   - Displays examples of positive 1-star and negative 5-star reviews, comparing text and model scores.

8. **Extra: The Transformers Pipeline**
   - Demonstrates using a pre-built sentiment analysis pipeline from the Transformers library.

## Technology Stack and Requirements

- **Tech Stack:** Python, NLTK (Natural Language Toolkit), Huggingface's Transformers library, Matplotlib, Seaborn for visualization.
- **Requirements:** NLTK, Transformers libraries.

## Project Objective

The main goal of this project is to:

- **Analyze Sentiment:** Determine sentiment (positive, negative, neutral) from Amazon product reviews.
- **NLP Techniques:** Implement various NLP techniques like tokenization, word embeddings, and machine learning models to perform sentiment analysis.
- **Insights Generation:** Derive insights from the sentiment analysis to understand customer opinions and sentiments regarding Amazon products.

## Features

- **Dataset:** Utilizes a dataset containing Amazon product reviews.
  ##### Checkout : https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews
- **Sentiment Analysis:** Implements sentiment analysis using machine learning and NLP methodologies.
- **Model Training:** Includes code for training, testing, and evaluating sentiment analysis models.
- **Visualizations:** Provides visual representations of sentiment analysis results and insights.

## Conclusion

This comprehensive analysis showcases the application of different methods for sentiment analysis in textual data. The notebook offers a structured approach to understanding and implementing sentiment analysis techniques in Python.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create your feature branch: `git checkout -b feature/YourFeature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin feature/YourFeature`
5. Submit a pull request.

## Acknowledgments

This project utilizes various libraries, resources, and datasets. Acknowledgments go to the contributors, dataset creators, and libraries used.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
