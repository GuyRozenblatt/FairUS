# FairUS - UpSampling Optimized Method for Boosting Fairness
This document introduces an novel pre-processing upsampling technique designed for effective bias mitigation. Leveraging the capabilities of Conditional Generative Adversarial Networks (CTGAN), this method revolutionizes the process of addressing bias in machine learning models.

The increasing application of machine learning (ML) in critical areas such as healthcare and finance highlights the importance of fairness in ML models, challenged by biases in training data that can lead to discrimination. 
We introduce 'FairUS,' a novel pre-processing method for reducing bias in ML models utilizing the Conditional Generative Adversarial Network (CTGAN) to synthesize upsampled data. Unlike traditional approaches that focus solely on balancing subgroup sample sizes, FairUS strategically optimizes the quantity of synthesized data. This optimization aims to achieve an ideal balance between enhancing fairness and maintaining the overall performance of the model.
We carried out extensive evaluations of our method using several canonical datasets and benchmarked our results against other related works. The results show that the proposed method enhances fairness by 2.7 times more than the related work while simultaneously preserving the performance of the ML model. Moreover, less than a third of the amount of synthetic data was needed on average. Uniquely, the proposed method enables decision-makers to choose the working point between improved fairness and model’s performance according to their preferences.


## Getting Started:
Follow these steps to utilize the FairUS technique effectively:

Select a Dataset: Navigate to the “Datasets & Params” section (cell 1) and choose the experiment you wish to run. Modify the DATASET_NAME variable to match your selected dataset. You have the freedom to pick from various experiments such as COMPAS, ADULT, CREDIT, BANK, and RECRUIT.

Run in Google Colab: For optimal results, it is recommended to run FairUS in a Google Colab environment. This cloud-based platform provides the necessary resources and infrastructure to execute your bias mitigation experiments seamlessly.

## Example:
Follow this example to witness the FairUS technique in action:

In the “Datasets & Params” section (cell 1), set DATASET_NAME to your preferred dataset. For instance, you can choose to experiment with COMPAS_RACE_AM.
Execute the code to initiate the bias mitigation process using FairUS.

## Assess the Results:
Once the code execution is complete, examine the accuracy and equalized odds metrics of the upsampled dataset. Compare these metrics with those of the original dataset to gauge the effectiveness of the FairUS
technique.

## Note
Please note that the code assumes you have the required packages installed ( there are pip install commands in the code) and the specified datasets available in the ‘FairUs datasets’ folder. The code is designed to demonstrate the FairUS technique for achieving bias mitigation.
