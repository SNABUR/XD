# MEXC Coin Tracker

<p align="center">
  <img src="https://github.com/SNABUR/MEXC-Tracker-coins/assets/136861183/a5fcdb74-efb1-48cc-aac6-bb883d4f2e55">
</p>

---

## Overview
MEXC Coin Tracker is a Python script designed to monitor the prices of various cryptocurrencies on the MEXC exchange. It utilizes the MEXC SDK to fetch real-time prices, stores the data in a Pandas DataFrame, and provides functionality to export the data to an Excel spreadsheet. Additionally, it features an alert system that triggers a sound when the price of a specified coin reaches a certain threshold.

---

## Usage
This script can be executed using Jupyter Notebook or Spyder. Simply run the `mexc_coin_tracker.py` script located in the provided directory. Ensure all required files, including the script and any necessary data files, are in the same directory.

<p align="center">
  <img src="https://github.com/SNABUR/MEXC-Tracker-coins/assets/136861183/c3d22089-46b8-4477-ad48-2be4576aeecb">
</p>

---

## Dependencies
- **mexc_sdk:** A Python SDK for accessing the MEXC exchange API.
- **pandas:** A powerful data analysis and manipulation library.
- **openpyxl:** A library for reading and writing Excel files.
- **winsound:** A library for playing sound alerts.
- **tkinter:** A GUI toolkit for Python.
- **sys:** A module for interacting with the Python interpreter.

Make sure to install these dependencies before running the script. You can install them using pip:

