# Stock Price Prediction using HMM, LSTM, and RNN

This repository contains an implementation of stock price prediction models using Hidden Markov Models (HMM), Long Short-Term Memory (LSTM), and Recurrent Neural Networks (RNN). The models are applied to the NIFTY 50 index for time-series forecasting and performance comparison.

## Features
- **Data Preprocessing**: Handles stock price data with necessary transformations.
- **Multiple Models**:
  - **HMM** for pattern recognition in stock movements.
  - **LSTM** for capturing long-term dependencies.
  - **RNN** for sequential forecasting.
- **Performance Metrics**:
  - Absolute Percentage Error (APE)
  - Average Absolute Error (AAE)
  - Average Relative Percentage Error (ARPE)
  - Root Mean Squared Error (RMSE)
  - Model efficiency and accuracy scores

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/stock-price-prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd stock-price-prediction
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. **Prepare Data**: Ensure the dataset is available in the required format.
2. **Run the script**:
   ```bash
   python main.py
   ```
3. **View Results**: Performance metrics will be displayed after model execution.

## File Structure
```
├── data/                  # Stock price dataset
├── models/                # HMM, LSTM, RNN implementations
├── results/               # Output predictions and analysis
├── main.py                # Entry point for running models
├── requirements.txt       # Dependencies
└── README.md              # Project documentation
```

## Contributing
Feel free to fork this repository and contribute by submitting pull requests. Any improvements, optimizations, or additional features are welcome.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
- Financial data sources
- Libraries used: NumPy, Pandas, Scikit-learn, TensorFlow, etc.

---

**Author:** Your Name  
**Contact:** your.email@example.com  

