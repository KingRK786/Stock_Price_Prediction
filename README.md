# 📈 Stock Price Prediction

![Python](https://img.shields.io/badge/Python-3.10%2B-blue)  
![Flask](https://img.shields.io/badge/Flask-2.0-lightgrey)  
![Deep Learning](https://img.shields.io/badge/Deep%20Learning-LSTM-orange)  

> 🚀 A deep learning-powered web application for predicting stock prices using historical data and LSTM (Long Short-Term Memory) networks, deployed on AWS.

---

## 🌐 Live Demo
🔗 **Deployed App:** [Click Here to Try](http://13.234.31.124:5000)

---

## 📜 Table of Contents
1. [About the Project](#-about-the-project)  
2. [Features](#-features)  
3. [Tech Stack](#-tech-stack)  
4. [Project Workflow](#-project-workflow)  
5. [Installation](#-installation)  
6. [Deployment](#-deployment)  
7. [Screenshots](#-screenshots)  
8. [Future Enhancements](#-future-enhancements)  
9. [Contributors](#-contributors)  
10. [License](#-license)  

---

## 📌 About the Project
The **Stock Price Prediction** project is designed to forecast future stock prices using historical market data.  
We use **LSTM networks** because of their ability to capture long-term dependencies in time-series data.  

The predictions are **visualized** and presented through a **Flask-based web application** for easy user interaction.

---

## ✨ Features
- 📊 **Historical Stock Data** fetching using Yahoo Finance API & Alpha Vantage  
- 🔮 **LSTM-based Deep Learning Model** for price prediction  
- 📈 **Visualization** of actual vs predicted stock prices  
- 🖥 **User-friendly Web Interface** using Flask, HTML, CSS  
- ☁ **AWS EC2 Deployment** for live access  
- 📉 **Evaluation Metrics**: MAE, RMSE  

---

## 🛠 Tech Stack

**Programming Language:** Python 🐍  
**Frameworks:** Flask, Keras, TensorFlow  
**Libraries:** Pandas, NumPy, Matplotlib, scikit-learn, yfinance, requests  
**Deployment:** AWS EC2  
**Frontend:** HTML5, CSS3  

---

## 🔄 Project Workflow
```mermaid
graph TD
A[User Input: Stock Symbol] --> B[Flask Backend]
B --> C[Fetch Data from Yfinance / Alpha Vantage]
C --> D[Data Preprocessing: Cleaning, Scaling]
D --> E[Feature Selection: Close, MA100, MA200]
E --> F[LSTM Model Training & Prediction]
F --> G[Evaluation Metrics: MAE, RMSE]
G --> H[Results Visualization]
H --> I[Output Shown on Web Application]
