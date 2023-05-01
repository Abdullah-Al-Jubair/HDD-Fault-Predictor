# HDD-Fault-Predictor

Introduction:
_____________

In the large-scale data centers, the number of hard disk drives(HDD) and solid-state drive (SSD) has reached millions. According to statistics, disk failures account for the largest proportion of all failures. Prediction of disk failures has been an important topic for IT or big data companies.
However, the topic has several challenging data characteristics, such as high data noise, extremely imbalanced classification, and time-varying features. Our target is to spend more time on solving these problems as a goal of finding a reasonable approach to predict disk failures in such a large scale system.  Meanwhile, since stability overwhelms everything, the effectiveness and stability of prediction models will also be considered. As a result of finding reasonable approaches, the IT and big data companies might be able to adopt such approaches to boost prosperity of cloud computing.

Problem Description:
____________________

Given a period of time of daily disk status monitoring data (Self-Monitoring, Analysis, and Reporting Technology; often written as SMART) and fault label data, we need to come up with our own solution, and daily determine whether each disk will fail within the next 30 days. As, failure prediction problem can be transformed into a traditional classification problem or a ranking problem, and we can use a binary classifier or learning to rank to solve it.

We found a suitable dataset from an online contest for disk failure prediction. We can train and evaluate our solutions based on this dataset. Meanwhile, we found a testing dataset as well. We are expected to diurnally determine whether each disk will fail within the next 30 days, and generate a prediction result set.


Input:
______

The input is the dataset containing disk failure information including their serial number, model, fault time etc. 

Output:
_______

The output is the fault_prediction feature that fits all the information of the given input and predicts whether a disk will fail within 30 days or not.


