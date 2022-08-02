# Blockchain Application 

## Table of Contents

This project is an application that makes use of professional profiles to remit payments for hourly wages in **ETH**. This is a python application developed using the **streamlit** library for the user interface.

To run this application clone this repo to a local directory. 

```Terminal
git clone git@github.com:mmsaki/blockchain-payment-app.git
```

Get into the `blockchain-payment-app/` folder through your terminal

```
cd blockchain-payment-app
```

The application requires streamlit so run `pip install streamlit`

Using streamlit run the app `blockchain_payment_app.py`
```
streamlit run blockchain_payment_app.py
```

> **Note**
I rely on **Ganache** for my blockchain environment. You must copy a mnemonic phrase into a `.env` file into the same directory. Create a varible `MNEMONIC = '<insert mnemonic phrase here>'` and save it in the `.env` file. Inside the `blockchain_payment_app.py`, update the `candidate_database` dictionary with new customer accounts addresses.

Here is a screenshot of the app running on `http://localhost:8501`.

![Screen Shot](./images/blockchain_app_demo.gif)