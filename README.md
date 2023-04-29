# Crypto Data Puller using Coin Market Cap API
This project aims to automate the process of pulling the latest cryptocurrency data from the Coin Market Cap API and storing the data in a CSV file. The project also includes data cleaning and visualization for selected cryptocurrencies.

## Requirements
- Python 3.6 or above
- Pandas
- Seaborn
- Matplotlib
- Requests
## Installation
- To install the necessary libraries, run the following command in the terminal:

      pip install pandas seaborn matplotlib requests
    
# Usage
1. Clone this repository or download the code.
2. Open a terminal window and navigate to the directory where the code is located.
3. Run the following command to execute the code:

        python CryptoDataPuller.py

4. The script will pull the latest cryptocurrency data every 60 seconds and store it in a CSV file named Crypto_Dataset.csv.
5. After pulling the data, the script will clean and visualize the data for selected cryptocurrencies (Bitcoin, Ethereum, Dogecoin, and Solana).
