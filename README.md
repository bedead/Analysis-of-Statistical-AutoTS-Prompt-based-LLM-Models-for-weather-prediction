# Comparative Analysis of Statistical, AutoTS, and Prompt-based LLM Models for Temperature Forecasting

## Abstract

This project presents a comparative study of three distinct approaches to temperature forecasting: traditional statistical models, automated time series (AutoTS) frameworks, and prompt-based large language models (LLMs). We evaluate the predictive performance, interpretability, and computational efficiency of each method using real-world temperature datasets. Our findings provide insights into the strengths and limitations of each approach, guiding practitioners in selecting appropriate models for temperature forecasting tasks.

## Introduction

Accurate temperature forecasting is crucial for various sectors, including agriculture, energy, and disaster management. Traditional statistical models such as ARIMA have long been used for time series forecasting, but recent advances in automated machine learning (AutoML) and large language models (LLMs) offer new possibilities. This project investigates and compares:

- **Statistical Models:** Classical approaches like ARIMA and Exponential Smoothing.
- **AutoTS Frameworks:** Automated pipelines that select and tune time series models.
- **Prompt-based LLMs:** Leveraging large language models (e.g., GPT) with tailored prompts for forecasting.

The goal is to assess each method's accuracy, interpretability, and resource requirements.

## Methodology

### Data

We use publicly available temperature datasets, preprocessed to handle missing values and outliers. The data is split into training and testing sets to evaluate model generalization.

### Models Evaluated

1. **Statistical Models:**  
   - ARIMA  
   - Exponential Smoothing

2. **AutoTS Frameworks:**  
   - AutoTS (Python library)  

3. **Prompt-based LLMs:**  
   - GPT-based models with custom prompts for time series forecasting

### Evaluation Metrics

MSE  - Mean Squared Error (lower is better)
RMSE - Root Mean Square Error (lower is better)
MAE  - Mean Absolute Error (lower is better)
MAPE - Mean Absolute Percentage Error (lower is better)

### Experimental Procedure

- Each model is trained on the same training set and evaluated on the same test set.
- Hyperparameters for statistical and AutoTS models are optimized using grid search or built-in AutoML routines.
- LLM prompts are engineered to maximize forecasting accuracy.

## Results Summary

- **Statistical Models:**  
  Achieved strong baseline performance with low computational cost and high interpretability, but struggled with non-linear patterns.

- **AutoTS Frameworks:**  
  Outperformed statistical models in most scenarios, automatically selecting optimal models and parameters. Slightly higher computational requirements.

- **Prompt-based LLMs:**  
  Demonstrated competitive accuracy, especially in capturing complex patterns. However, results were sensitive to prompt design and required significant computational resources.

## Discussion

The comparative analysis reveals that while LLMs can match or exceed the accuracy of traditional models, their interpretability and computational demands may limit practical deployment. AutoTS frameworks offer a balanced trade-off, automating model selection and tuning while maintaining reasonable resource requirements.

## Conclusion

This study highlights the evolving landscape of temperature forecasting, demonstrating the potential of prompt-based LLMs and AutoTS frameworks alongside established statistical methods. Future work will explore hybrid approaches and further optimize LLM prompt engineering for time series tasks.

## How to Run

1. Clone this repository.
2. Install dependencies:  
   `pip install -r requirements.txt`
3. Run indivual notebook based on requirement  
