# Machine Learning for IoT Traffic Analysis

Using machine learning to detect malware and DDoS attack stages in IoT network 
traffic.

<p align="center">
  <img src="https://user-images.githubusercontent.com/78480767/185649037-38d093e2-369e-4e1e-a86d-a002bc948b0c.jpeg" width="300" height="300">
</p>
 
## Overview

IoT devices connect over networks to provide a wide range of services, but 
vulnerabilities in their implementation constantly open the door to cyberattacks 
and unauthorized access. This project applies machine learning techniques to 
detect malware and identify specific stages of DDoS attacks within IoT network 
traffic.


## Dataset

The project uses the **IoT-23 dataset** — a labeled dataset of malicious and 
benign IoT network traffic containing over 23 capture scenarios, with executed 
malware including Mirai, Torii, and IRCBot.

## Approach

- Combined and cleaned data from multiple network traffic captures
- Applied the **Pearson correlation coefficient** for feature selection — 
  improving data quality, reducing computation time, and increasing accuracy
- Trained and evaluated machine learning models to classify malicious vs. 
  benign traffic and detect attack stages

## Tech Stack

- **Python**
- **scikit-learn / pandas / NumPy** — data processing and modelling
- Matplotlib for visualization

## Results

Achieved 99.99% accuracy in classifying malicious 
IoT traffic using decision tree classifiers
