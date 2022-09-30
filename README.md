# Module-Challenge-19

## Step 1:
-  Import Ethereum Transaction Functions into the Fintech Finder ApplicationFintech Finder


## Step 2: 
- Sign and Execute a Payment Transaction


## Step 3: 
- Inspect the Transaction


#Streamlit App Screenshot Screenshot and recording:

<img width="957" alt="image" src="https://user-images.githubusercontent.com/105945472/193333401-a3060134-d36d-415d-881f-eaaf0862b55a.png">


https://user-images.githubusercontent.com/105945472/193333806-928602b4-5839-4472-8b8d-10b249e889c2.mp4



# Ganache Screenshot:

<img width="971" alt="image" src="https://user-images.githubusercontent.com/105945472/193332539-a902d105-8969-4c59-981c-6155419cf6a6.png">


<img width="961" alt="image" src="https://user-images.githubusercontent.com/105945472/193333287-968de60c-e21f-4e6b-83e4-b22b6634163f.png">



# Fintech Finder Application
## Imports
* import streamlit as st
* from dataclasses import dataclass
* from typing import Any, List
* from web3 import Web3
w3 = Web3(Web3.HTTPProvider('HTTP://127.0.0.1:7545')) *Ganache RPC SERVE

# Crypto Wallet Application
## Imports
* import os
* import requests
* from dotenv import load_dotenv
* load_dotenv()
* from bip44 import Wallet
* from web3 import Account
* from web3 import middleware
* from web3.gas_strategies.time_based import medium_gas_price_strategy
w3 = Web3(Web3.HTTPProvider('HTTP://127.0.0.1:7545')) *Ganache RPC SERVER
