# 📊 S&P100 Analysis with Graph Neural Networks 📈
Welcome to the S&P100 Analysis with Graph Neural Networks project! This project focuses on analyzing the S&P100 stocks, which represent 100 leading U.S. stocks, using the power of Graph Neural Networks (GNNs) for comprehensive insights.

## Overview
The project comprises two main phases:

1. **Data Collection and Pre-processing**: This phase involves collecting historical data, particularly stock prices, and constructing graphs to depict relationships between stocks based on factors like sector and correlation.

2. **Data Analysis**: In this phase, we delve into various analyses and modeling tasks using PyTorch Geometric library for GNNs. This includes variation forecasting, stocks clustering, link prediction, and more.

## Notebooks
To facilitate understanding and execution, the project is organized into several Jupyter notebooks:

1. [Data collection and preprocessing](https://github.com/timothewt/SP100_Analysis_with_GNNs/blob/master/notebooks/1-data_collection_and_preprocessing.ipynb): This notebook provides detailed instructions and code for collecting stock data (sectors, fundamentals, historical prices).

2. [Graph creation](https://github.com/timothewt/SP100_Analysis_with_GNNs/blob/master/2-graph_creation.ipynb): Focuses on the creation of graphs to model relationships between S&P100 stocks based on sector and fundamentals correlation.

3. [PyTorch Geometric custom dataset](https://github.com/timothewt/SP100_Analysis_with_GNNs/blob/master/3-torch_geometric_dataset.ipynb): Demonstrates how to use PyTorch Geometric to create datasets suitable for GNN training and evaluation.

4. [Temporal Graph Neural Network Models](https://github.com/timothewt/SP100_Analysis_with_GNNs/blob/master/5-temporal_gnn_models.ipynb): Implementation of Temporal Graph Convolutional Networks, such as T-GCN and A3T-GCN.

5. [Stock prices forecasting](https://github.com/timothewt/SP100_Analysis_with_GNNs/blob/master/6-stock_prices_forecasting.ipynb): Focuses on using TGCNs for forecasting variations in stock prices, enabling predictive analysis.

6. [TODO] [Stock links prediction](https://github.com/timothewt/SP100_Analysis_with_GNNs/blob/master/6-stock_links_prediction.ipynb): Investigates link prediction, aiming to forecast potential connections or relationships between different stocks within the S&P100 (possible extension to the S&P500 as test dataset).

7. [TODO] [Stocks clustering with Deep Graph Clustering](https://github.com/timothewt/SP100_Analysis_with_GNNs/blob/master/7-stocks_clustering.ipynb): Explores clustering techniques using GNNs to group similar stocks together based on various features (possible extension to the S&P500 as test dataset).

8. [TODO] [S&P100 weights optimization via Deep Reinforcement Learning](https://github.com/timothewt/SP100_Analysis_with_GNNs/blob/master/8-portfolio_optimization.ipynb): Uses Deep Reinforcement Learning to optimize the weights of the 100 stocks in the S&P100 based on historical data and GNN predictions. The goal of the agent is to outperform the equal weights S&P100 index by adjusting its portfolio to the current market.

## Dependencies
Ensure you have the following dependencies (of the `requirements.txt` file) installed to run the notebooks smoothly:
- Matplotlib
- NetworkX
- Jupyter Notebook
- NumPy
- Pandas
- scikit-learn
- ta (Technical Analysis library)
- Tensorboard
- PyTorch Geometric
- tqdm
- Wikipedia
- yFinance

## Getting Started
1. Clone this repository to your local machine.
2. Install the necessary dependencies.
3. Open and run the desired notebook(s) in your Jupyter Notebook environment.
4. Follow the instructions within each notebook to execute the code and explore the analyses.

## Contributions
Contributions and feedback are welcomed!
If you have any suggestions, improvements,
or discover any issues, feel free to submit a pull request or open an issue in the GitHub repository.

Happy analyzing! 📈🔍
