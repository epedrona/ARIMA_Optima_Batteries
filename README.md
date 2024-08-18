# ARIMA Demand Forecasting for Optima Batteries

## Author

Emanuele Pedrona

For any questions or inquiries, feel free to contact me via GitHub.

## Project Overview

This project is designed to forecast sales of Optima batteries using an ARIMA (AutoRegressive Integrated Moving Average) model. The dataset used in this project contains anonymized italian e-commerce orders over the last 10 years, with details on the order date, product type, and total sales amount. The project also explores the integration of a chatbot to answer questions related to the dataset and the forecasting results, utilizing Google Cloud's Vertex AI.

## Contents

- **arima_optima_batteries.ipynb**: Jupyter Notebook containing the data preprocessing, ARIMA model implementation, and forecasting process.
- **optima_batteries.csv**: Anonymized dataset with e-commerce order data, including columns for order date, product type, and total sales amount.

## Objectives

1. **Data Preprocessing**: Clean and prepare the dataset, ensuring it is suitable for time series forecasting.
2. **ARIMA Model**: Implement an ARIMA model to forecast future sales of Optima batteries.
3. **Chatbot Integration (Future Work)**: Plan to integrate a chatbot that can answer queries about the dataset and the forecasted results.
4. **Google Cloud Vertex AI**: Leverage Vertex AI for model training, deployment, and potentially hosting the chatbot.

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook
- Necessary Python libraries (pandas, statsmodels, matplotlib, etc.)

### Running the Notebook

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ARIMA_Optima_Batteries.git

2. pip install -r requirements.txt

3. Open and run the arima_optima_batteries.ipynb notebook in Jupyter.

## Future Work

	•	**Chatbot Development**: Implement a chatbot using Vertex AI that can interact with users and answer questions about the dataset and the forecast results.
	•	**Model Improvements**: Explore other time series forecasting models like SARIMA, Prophet, or machine learning-based models to compare their performance with ARIMA.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments

This project was inspired by a need to understand and forecast sales trends for Optima batteries using historical e-commerce data. The use of ARIMA for time series forecasting and the potential integration of Vertex AI’s capabilities form the backbone of this work.
