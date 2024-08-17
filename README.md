# AI_Model_text_quantitative (MUHAMMAD UMAIR NAZIR)
Economic Policy Sentiment and Correlation Analysis with Transformer Models
Project Overview
This repository contains a Python-based project that uses the Hugging Face Transformers library and TensorFlow to analyze sentiment in economic policy text data. Additionally, it includes quantitative data analysis of key economic indicators and their correlation with different policy classifications. The project demonstrates the integration of deep learning models for sentiment analysis with data analytics techniques for economic research.

Contents
Sentiment Analysis Using Transformers: Uses a pre-trained transformer model from the Hugging Face pipeline to classify the sentiment of economic policy-related text data.
Economic Data Analysis: Includes a dataset with various economic indicators like GDP growth, inflation rates, interest rates, and unemployment rates, as well as policy classifications (Expansionary, Contractionary, Neutral).
Correlation Analysis: Performs correlation analysis to understand the relationships between key economic indicators and policy classifications.
Project Structure
sentiment_analysis.py: Script for running sentiment analysis on economic policy text data using Hugging Face Transformers.
data_analysis.py: Script for analyzing the correlation between economic indicators and policy classifications using pandas and numpy.
README.md: Documentation file for explaining the project and its usage.
requirements.txt: Contains a list of required libraries such as transformers and tensorflow to run the project.
Installation
Clone this repository to your local machine.
bash
Copy code
git clone https://github.com/yourusername/economic-policy-sentiment-analysis.git
Install the required Python packages.
bash
Copy code
pip install -r requirements.txt
Usage
Sentiment Analysis:

Run the sentiment analysis script:
bash
Copy code
python sentiment_analysis.py
This will classify the sentiment of sample economic policy texts, providing an output in the form of positive or negative sentiments.
Quantitative Data and Correlation Analysis:

Run the data analysis script:
bash
Copy code
python data_analysis.py
This will display the quantitative data and compute correlations between economic indicators and policy classifications.
Data
The project includes a small dataset containing key economic indicators for five months in 2024:

GDP Growth (%)
Inflation Rate (%)
Interest Rate (%)
Unemployment Rate (%)
Policy Classification: Expansionary, Contractionary, or Neutral
The correlation analysis provides insights into how these economic factors relate to different policy strategies.

Future Enhancements
Fine-tuning transformer models for more specialized economic sentiment analysis.
Incorporating more complex datasets and longer time series for in-depth economic forecasting.
Introducing machine learning models for predictive economic analytics based on sentiment and quantitative data.
Contributing
Contributions are welcome! Please open an issue or submit a pull request if you have any improvements or new ideas.

License
This project is licensed under the MIT License. See the LICENSE file for details.
