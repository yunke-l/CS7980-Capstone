# A Comparative Study of SLMs and LLMs in Customer Review Analysis
More results of this study can be found in [[Poster]](/poster.pdf) and the code.

## Overview
This study conducts a comprehensive comparison of the performance trade-offs between Small Language Models (SLMs) and Large Language Models (LLMs) on two critical tasks in customer review analysis: **sentiment polarity classification** and **correlation analysis with product categories**. 

### Selected Models
- SLMs: DistilBERT, ELECTRA
- LLMs: Flan-T5, Flan-UL2

### Dataset
[Amazon US Customer Reviews Dataset](https://www.kaggle.com/datasets/cynthiarempel/amazon-us-customer-reviews-dataset/data)

### Methods
We employed three distinct approaches for each task:
1. Utilizing SLMs
2. Utilizing LLMs 
3. Deploying hybrid methods 


Hybrid System on Sentiment Polarity Classification

![Hybrid System on Sentiment Polarity Classification](/assets/task1.png)


Methods on Correlation Analysis

![Correlation Analysis](/assets/task2.png)


## Key Findings
Our findings reveal that:
- LLMs excel in sentiment polarity classification, outperforming SLMs in accuracy but incurring significantly higher computational costs.
- SLMs demonstrate superior performance and efficiency for the more domain-specific task of correlation analysis.
- To balance accuracy and efficiency in sentiment polarity classification, we propose a hybrid system integrating SLMs and LLMs through a tiered processing strategy.



Comparative Results of Sentiment Polarity Classification Task

<img src="assets/bubblechart-task1.png" alt="results-task1" width="400"/>


Comparative Results of Correlation Analysis Task

<img src="assets/bubblechart-task2.png" alt="results-task2" width="400"/>





