# Stock Price Prediction using LSTM and Sentiment Analysis

This project explores the use of deep learning (LSTM) for predicting NASDAQ stock price trends. We enhance the model with sentiment scores generated from financial news using FinBERT.

## 💡 Project Highlights

- Combined historical price data with sentiment analysis
- Used FinBERT for extracting sentiment scores from financial news
- Built a Long Short-Term Memory (LSTM) neural network
- Focused on predicting short-term to medium term stock prices (index)

## 🧠 Skills Demonstrated

- Deep Learning (LSTM, Sequential Models)
- Time Series Forecasting
- Sentiment Analysis using FinBERT
- Feature Engineering (Technical Indicators)
- Data Visualization

## 📁 Structure

- `stock-price-prediction-lstm.ipynb` - Full notebook with LSTM model
- `data/` - Directory for processed CSV datasets
- `sentiment_scores/` - Directory for FinBERT-generated scores

## 📊 Results

- LSTM performed incredibly well on test accuracy and trend prediction
- Other models (GRU, Bi-LSTM, Attention) were explored and will be added later after optimization.
## ⚙️ Tools Used

- Python, Keras, TensorFlow, FinBERT, Pandas, Matplotlib

## 🔮 Future Work

- Add benchmarking with Transformers and TCN
- Improve sentiment-time alignment
- Explore Transformer-based models (like BERT+MLP)

## 🧾 License

MIT License
