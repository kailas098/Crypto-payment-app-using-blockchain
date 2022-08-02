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

Using streamlit run the app `fintech_finder.py`
```
streamlit run fintech_finder.py
```

> **Note**
I rely on **Ganache** for my blockchain environment. You must copy a mnemonic phrase into a `.env` file in the same directory. Create a varible `MNEMONIC = '<insert mnemonic phrase here>'`

Here is a screenshot of the app running on `http://localhost:8501`.

![Screen Shot](./images/screenshot_app.jpg)