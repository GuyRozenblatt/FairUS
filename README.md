# FairUS
This repository is the implementation of FairUS - UpSampling Optimized Method for Boosting Fairness

The increasing application of machine learning (ML) in critical areas such as healthcare and finance highlights the importance of fairness in ML models, challenged by biases in training data that can lead to discrimination. 
We introduce 'FairUS,' a novel pre-processing method for reducing bias in ML models utilizing the Conditional Generative Adversarial Network (CTGAN) to synthesize upsampled data. Unlike traditional approaches that focus solely on balancing subgroup sample sizes, FairUS strategically optimizes the quantity of synthesized data. This optimization aims to achieve an ideal balance between enhancing fairness and maintaining the overall performance of the model.
We carried out extensive evaluations of our method using several canonical datasets and benchmarked our results against other related works. The results show that the proposed method enhances fairness by 2.7 times more than the related work while simultaneously preserving the performance of the ML model. Moreover, less than a third of the amount of synthetic data was needed on average. Uniquely, the proposed method enables decision-makers to choose the working point between improved fairness and model’s performance according to their preferences.

![image](https://github.com/GuyRozenblatt/FairUS/assets/65950438/d70a8c8d-8c68-4e1d-93ca-bd270cd43396)


