# Payment Application 

## Summary

This project is an application that makes use of professional profiles to remit payments for hourly wages in **ETH**. This is a python application developed using the **streamlit** library for the user interface.

To run this application clone this repo to a local directory. 

### Step 1: Clone Repo
Open Terminal and run the following command.
```Terminal
git clone git@github.com:mmsaki/blockchain-payment-app.git
```

Get into the `blockchain-payment-app/` folder through your terminal

```
cd blockchain-payment-app
```

### Step 2: Running the application

The application requires streamlit installed so run `pip install streamlit` and then proceed.

Using streamlit run the app `blockchain_payment_app.py` using the following command.
```
streamlit run blockchain_payment_app.py
```

> **Note**
I rely on **Ganache** for my blockchain environment. Copy a mnemonic phrase into a `.env` file in the same directory. Create a varible `MNEMONIC = '<insert mnemonic phrase here>'` and save the `.env` file. Open the `blockchain_payment_app.py` and update the `candidate_database` with new customer account addresses.

## Example

Here is a screenshot of the app running on `http://localhost:8501`.

![Screen Shot](./images/blockchain_app_demo.gif)
