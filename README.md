# Fin-Tech-Module-19

This module allow the exploration of Blockchain wallets and the scope of generating and transacting using tools such as Genache and Streamlit.

## Step 5

### Challenge Step 5 - Streamlit Run

<a href="" target="_blank" rel="noreferrer"><img src="Screen Shot 2023-07-25 at 12.28.09 PM.png" width="" height="300" alt="StreamLit UI" /></a>

### Challenge Step 5 - Test

<a href="" target="_blank" rel="noreferrer"><img src="Screen Shot 2023-07-25 at 12.28.51 PM.png" width="" height="300" alt="StreamLit UI" /></a>

### Challenge Step 5 - Validation

<a href="" target="_blank" rel="noreferrer"><img src="Screen Shot 2023-07-25 at 12.30.32 PM.png" width="" height="300" alt="StreamLit UI" /></a>

## Technologies

```
import os
import requests
from dotenv import load_dotenv

load_dotenv()
from bip44 import Wallet
from web3 import Account
from web3 import middleware
from web3.gas_strategies.time_based import medium_gas_price_strategy

import streamlit as st
from dataclasses import dataclass
from typing import Any, List
from web3 import Web3

w3 = Web3(Web3.HTTPProvider("HTTP://127.0.0.1:7545"))
```

## Installation Guide

Run Streamlit pychain.py

---
