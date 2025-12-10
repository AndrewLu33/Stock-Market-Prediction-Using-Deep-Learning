📈 Deep Learning-based Stock Market Prediction
Using Historical Prices + Topic-Distributed News Sentiment
This research Group Project was developed as part of the Research Methodology course.
The goal was to investigate how deep learning models can predict stock market movements by combining:
🟦 Historical stock price patterns
🟧 Topic-distributed sentiment extracted from financial news
I served as the main developer responsible for building and integrating the complete deep learning pipeline.


🚀 Project Overview
We designed a dual-branch deep learning architecture that processes two different inputs:
1️⃣ Price Branch
Models used:
• LSTM
• GRU
• TCNN (Temporal Convolutional Neural Network)
These models learn temporal patterns in historical price data.

2️⃣ News-Sentiment Branch
• Extracted topic-sentiment vectors using FinBERT
• Applied advanced topic modeling using BERTopic
This branch provides market context from textual data.


📊 Result
![LSTM Prediction Plot](images/lstm_plot.png)
![GRU Prediction Plot](images/gru_plot.png)
![GRU Prediction Plot](images/tcnn_plot.png)

The system was trained and evaluated using historical data from Apple (AAPL) stock.
Model      R² Score
GRU	       ⭐0.9866 (Best)
LSTM	     0.9838
TCNN	     0.9587
GRU outperformed the others due to its ability to capture long-term dependencies efficiently.


🧩 Challenges & Learnings
• This project provided hands-on experience solving real-world ML issues:
• Handling data alignment between price timelines and news events
• Extracting meaningful sentiment signals from text
• Tuning deep learning models for unstable financial data
• Understanding evaluation metrics for regression tasks in finance
• Managing long training times and ensuring reproducibility


👨‍💻 Authors
• Rafi Hazel Tafara, who was responsible for designing the deep learning model architecture.
• Yosepril Zhounggi, for his contributions to the literature review and the paper writing process.
• Muhammad Fikri Hasani and Ayu Maulina, our supervising lecturers, for their invaluable guidance.


📄 **[Read the Research Paper (CC BY-NC-ND 4.0)](https://lnkd.in/e5bCnntw)**
