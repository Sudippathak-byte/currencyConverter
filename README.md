Currency Converter App

This is a currency converter app built with React. The app allows users to convert an amount from one currency to another using real-time exchange rates fetched from an API.

Features
Currency Selection: Choose currencies to convert between.
Amount Input: Enter the amount for conversion.
Swap Function: Swap the "From" and "To" currencies with a button.
Real-Time Conversion: Convert the entered amount based on current exchange rates.


Components
InputBox: A reusable component to input the amount and select currency.
App: The main app that integrates the InputBox components and handles the conversion logic.


Hooks
useCurrencyInfo: A custom hook that fetches the latest exchange rates from an API based on the selected "From" currency.
useState, useEffect: Used to manage state for amount, currencies, and converted amount.


Why I Created This App
This project helped me:

Practice using React hooks, especially custom hooks (useCurrencyInfo).
Learn how to fetch data from an API and manage asynchronous data.
Understand how to manage form inputs and create reusable components.