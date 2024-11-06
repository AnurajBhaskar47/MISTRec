# Recommender System Comparison on Amazon Pantry Dataset

This repository contains a comparative analysis of various sequential recommendation models—**UniSRec**, **SASRec**, and **MISSRec**—using the **Amazon Pantry** dataset. The project focuses on evaluating each model's performance using metrics such as **HIT** and **NDCG**, with data preprocessing facilitated by the **RecBole** framework.

## Project Overview

In this project, we explore the effectiveness of UniSRec, SASRec, and MISSRec models in providing personalized recommendations. The Amazon Pantry dataset, chosen for its rich user interaction data, enables robust analysis and benchmarking of these models.

## Models Overview

- **UniSRec (Unified Sequential Recommendation)**: UniSRec is designed to capture both short-term and long-term user interests by combining recent and past user behaviors, thus enhancing recommendation relevance.

- **SASRec (Self-Attention Sequential Recommendation)**: SASRec utilizes self-attention mechanisms to model sequential dependencies in user interactions. By focusing on recent actions, SASRec aims to deliver relevant recommendations in a dynamic context.

- **MISSRec (Multi-Modal Interest-Aware Sequential Recommendation)**: MISSRec leverages multi-modal signals to understand user preferences, aiming to improve accuracy in recommendations by capturing complex user-item interactions.

## Dataset

The **Amazon Pantry dataset** was used in this project, consisting of user interactions with various products. The raw data was downloaded and processed using the **RecBole** framework to ensure compatibility with the models.

### Data Processing

1. **Data Download**: The raw data was sourced from the Amazon Pantry dataset.
2. **RecBole Framework**: RecBole was used to process and transform the data into the required format, including data cleaning, user-item interaction filtering, and other preprocessing tasks essential for model training.

## Model Evaluation

After training each model on the processed dataset, we evaluated their performance using the following metrics:

- **HIT (Hit Rate)**: This metric measures the accuracy of the recommended items by checking if the relevant item is present in the top-N list.
- **NDCG (Normalized Discounted Cumulative Gain)**: This metric evaluates the quality of recommendations by assigning higher relevance to items appearing at the top of the recommendation list.

## Results

The performance of each model—UniSRec, SASRec, and MISSRec—is compared in terms of HIT and NDCG. The results provide insights into each model's strengths and suitability for the Amazon Pantry dataset.

## Conclusion

This comparison highlights the strengths of each model in sequential recommendation tasks:

- **UniSRec** captures both recent and long-term user interests.
- **SASRec** excels in modeling sequential dependencies.
- **MISSRec** improves accuracy by leveraging multi-modal signals.

Each model demonstrates unique advantages, and their performance on the Amazon Pantry dataset provides valuable insights for future advancements in recommendation systems.

---

## Getting Started

### Prerequisites

- Python 3.x
- RecBole framework

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/recommender-system-comparison.git
