# Project Title - Fintech Finder

## Introduction
The primary goal of our team is to build a Fintech Finder application that customers can use to search and choose from a list of fintech professionals for hire and to pay them for their services.  As the lead developer of this project, our team will be tasked with integrating the Ethereum blockchain network into the application in order to enable customers to instantly pay the fintech professionals whom they hire with crytpocurrency.  

## Technologies
**Python Libraries**

`bip44==0.1.3`<br>
`python-dotenv==1.0.0`<br>
`Requests==2.31.0`<br>
`streamlit==1.23.1`<br>
`web3==5.17.0`

## Installation Guide

[Install Anaconda](https://www.anaconda.com/download/)

[Install Git](https://git-scm.com/downloads) 

[Install Ganache](https://trufflesuite.com/ganache/)

To clone and run this application, you'll need Git installed on your computer.
From your command line:
```
# Create a new conda environment
conda create -n whatever_your_name python=3.7 anaconda

# Activate the new environment with the following command
conda activate whatever_your_name

# Iniitlaize git (skip if git is installed)
git init

# Browse to your directory and clone the repository below on your local machine
git clone https://github.com/AlexanderValenzuela/fintech_finder

# Install Python modules and libraries in the new conda environment
pip install web3==5.17 - A Python library for connecting to and performing operations on Ethereum-based blockchains###

pip install eth-tester==0.5.0b3 - A Python library that provides access to the tools we’ll use to test Ethereum-based applications.

pip install mnemonic - A Python implementation for generating a 12- or 24-word mnemonic seed phrase based on the BIP-39 standard.

pip install bip44 - A Python implementation for deriving hierarchical deterministic wallets from a seed phrase based on the BIP-44 standard.

pip install streamlit - Python library for building web interfaces for your Python applications.


# In the conda environment, launch your preferred source code editor and browse to your directory

# Alternatively, browse to your directory and launch fintech_finder.py and crypto_wallet.py.

```

## Usage

Now it's time to put it all together and test the Fintech Finder application with the newly integrated Ethereum wallet. We will send a test transaction by using the application’s web interface, and then look up the resulting transaction in Ganache. 

1. From your terminal, navigate to the project folder that contains your `.env` file and the `fintech_finder.py` and `crypto_wallet.py` files. Be sure to activate your Conda dev environment if it is not already active.

2. To launch the Streamlit application, type `streamlit run fintech_finder.py`.
![Screenshot 2023-07-29 at 1 16 48 AM](https://github.com/AlexanderValenzuela/fintech_finder/assets/111409358/04be9b8c-589e-43f1-bd8d-c088422ba3f7)

3. On the resulting webpage, select a candidate that you would like to hire from the appropriate drop-down menu. Then, enter the number of hours that you would like to hire them for.

![Screenshot 2023-07-29 at 1 27 12 AM](https://github.com/AlexanderValenzuela/fintech_finder/assets/111409358/7e7a918c-fd98-4f33-a888-a9c4c8f33f9e)


4. Click the Send Transaction button to sign and send the transaction with your Ethereum account information. 

![Screenshot 2023-07-29 at 1 35 54 AM](https://github.com/AlexanderValenzuela/fintech_finder/assets/111409358/fa2cc828-e272-4827-92e3-27258e4f64cb)

- Screenshot of address balance and history on Ganache

![Screenshot 2023-07-29 at 1 40 31 AM](https://github.com/AlexanderValenzuela/fintech_finder/assets/111409358/463fb973-3055-463c-9621-a0fa869e0b7f)

- Screenshot of the transaction details on Ganache

![Screenshot 2023-07-29 at 1 45 37 AM](https://github.com/AlexanderValenzuela/fintech_finder/assets/111409358/f70a9bba-2fd4-4d82-ab4c-224aab8ba972)

- Screenshot of the recipient’s address balance and history in the Ganache application

![Screenshot 2023-07-29 at 1 45 20 AM](https://github.com/AlexanderValenzuela/fintech_finder/assets/111409358/84d15538-c40b-4530-985c-89ca93bab8f7)



## Contributors
- Firas Obeid, UC Berkeley FinTech Instructor
[GitHub](<https://github.com/firobeid>)

- Hasan Mehommod, Central Tutor Support

- Alexander Valenzuela<br>
[LinkedIn Profile](<https://www.linkedin.com/in/alex-valenzuela-97826842/>)


## License
Licensed under the MIT License

