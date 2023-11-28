# Datasets in Blockchain Address Label Repository

This document lists and describes the datasets included in the `blockchain_address_label_repository`. It provides essential information about each dataset in a tabular format to facilitate ease of use for researchers and developers.

## Dataset Table
| Dataset Name | Source | Author | Description | Size   | Dimensions | Scope | Format | Language | Year of Creation | Usage | Original Dataset Reference |
|----|----|-----|----|----|----|----|----|-----|----|----|----|
| Labelled Ethereum Addresses                 | [Kaggle Dataset](https://www.kaggle.com/datasets/hamishhall/labelled-ethereum-addresses) | Hamish Hall           | Collection of Ethereum addresses with labels for exchanges, wallets, etc. | Static | Address, Label, Category     | Ethereum address classification                 | CSV                 | English  | Unknown          | Blockchain analytics, address classification                              | N/A                        |
| Ethereum Task Type Prediction (Chartalist)  | [Chartalist ETH Dataset](https://chartalist.org/eth/TaskTypePrediction.html) | Victor et al., 2021 | Dataset for machine learning models to predict Ethereum transaction types. | Static | Labeled Ethereum transaction data | Ethereum transaction analysis                  | CSV | English  | 2021             | ML models for Ethereum transaction classification                        | @inproceedings{victor2021alphacore,
  title={Alphacore: Data Depth based Core Decomposition},
  author={Victor, Friedhelm and Akcora, Cuneyt G and Gel, Yulia R and Kantarcioglu, Murat},
  booktitle={Proceedings of the 27th ACM SIGKDD Conference on Knowledge Discovery \& Data Mining},
  pages={1625--1633},
  year={2021}
}   |
| Etherscan Label Cloud                       | [Etherscan.io](https://etherscan.io/labelcloud)           | Etherscan             | Labeled Ethereum addresses for on-chain analysis.                         | Dynamic | Ethereum Address, Label     | Ethereum network analysis                       | Web Page (Scrapable) | English  | Unknown          | On-chain data analysis, wallet identification                            | N/A                        |
| BSCscan Label Cloud                         | [BSCscan.io](https://bscscan.io/labelcloud)               | BSCscan               | Labeled Binance Smart Chain addresses for on-chain analysis.              | Dynamic | BSC Address, Label          | Binance Smart Chain network analysis            | Web Page (Scrapable) | English  | Unknown          | On-chain data analysis, wallet identification                            | N/A                        |
| PolygonScan Label Cloud                     | [PolygonScan.com](https://polygonscan.com/labelcloud)     | PolygonScan           | Labeled Polygon addresses for network transactions analysis.              | Dynamic | Polygon Address, Label      | Polygon network transactions analysis           | Web Page (Scrapable) | English  | Unknown          | Research and analysis of Polygon network transactions                    | N/A                        |
| FTMScan Label Cloud                         | [FTMScan.com](https://ftmscan.com/labelcloud)             | FTMScan               | Labeled Fantom addresses for blockchain transactions analysis.           | Dynamic | Fantom Address, Label       | Fantom blockchain transactions analysis         | Web Page (Scrapable) | English  | Unknown          | Analysis of Fantom blockchain transactions                                | N/A                        |


