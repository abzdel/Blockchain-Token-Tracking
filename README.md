# Blockchain-Token-Tracking

## Project Overview
This is a smaller project that I did to assist a professor in his project to predict the "success" of ERC721 tokens (during my Blockchain course). Unfortunately, the professor never proceeded with the remainder of the project, but I still wanted to show what I did.

These are two Jupyter Notebooks which scrape data about tokens on the Ethereum network from Etherscan. The first notebook (retrieve-account-data) retrieves various data about an Ethereum address - wallet balance, transactions (to and from), value of each transaction, etc. The other notebook (ERC721-Tracking) retrieves data about ERC721 tokens and their paths (where they're coming from and where they're going).

## Programs & Packages
- **Python**: Version 3.7
- **Packages**: pandas, requests
- **Etherscan**: For requesting data about transactions and tokens
