# challenge_19_072723
---
# Fintech Finder 
### Using ganache and python to create an app that allows a user to transfer funds between two crypto wallets
---
## Objective

The purpose of this assignment is to create an app that allows customers to review fintech professionals rating, and enables the customer to send cryptocurrency payments to the fintech professionals.

To accomplish this and test it in a practice environment. **Ganache** is a program that allows to quickly set up a local blockchain, which you can use to test and develop smart contracts. was used to create a crypto wallet for myself as a simulated user. I could then determine how many hours I wanted the fintech professional to work, and then calculate how much ethereum crypto I needed to pay that professional.

---
## Technologies
        1. python
        2. Ganache (https://trufflesuite.com/ganache/)
        3. Streamlit - User interface to select a fintech professional and determine the hours to pay that professional
        4. Web3 - a python library for connecting to and performing operations on Ethereum-based blockchains
        5. Mnemonic - used within an .env file to connect to the Ethereum wallet

---
## Run Instructions
Once you've downloaded the file, you'll have a few things to do for setup.

        1. Download and install Ganache
        2. Install Web3 
        3. Install Streamlit
        4. Install bip44 

Once you've installed the required packages, you need to change the URL contained within the 'fintech_finder.py' file to inlcude your Ganache server. 

Finally, at your command prompt, navigate to where you've cloned the file, then type in the following command:
```
streamlit run fintech_finder.py
```
---
## Results

The following images show how an examples where I selected and then paid three individual fintech professionals. I was able to successfully transfer funds from my etherum wallet to their etherum wallet. 

The following image shows the inital stremlit app page

![streamlit_image](\Images\streamlit_transaction.png)

The image below shows the blockchain transactions in ganache

![ganache_blockchain_transaction](\Images\gnache_blockchain.png)

Image showing the transaction history from ganache

![ganache_transaction_history](\Images\gnache_transactions.png)

Finally the image showing the balance in my Ethereum wallet
![ganache_account](\Images\gnache_account.png)
