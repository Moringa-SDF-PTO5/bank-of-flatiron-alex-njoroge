# bank-of-flatiron-alex-njoroge
Bank of Flatiron - Recent Transactions Web App
Overview
Bank of Flatiron is a React application designed to display a list of recent bank transactions and provide functionality to add new transactions and filter transactions based on description. This README file provides information on how to set up the application and use its core features.

Setup
To set up the Bank of Flatiron application, follow these steps:

Create a new PRIVATE repository in the [GitHub Organization](Moringa-SDF-PTO5Links to an external site.) with the name format bank-of-flatiron-firstname-lastname (Example: bank-of-flatiron-jane-doe).
Clone the repository to your local machine.
Download the server db.json file from here.
Ensure you have Node.js and npm (Node Package Manager) installed on your machine.
Install json-server globally on your machine by running npm install -g json-server.
Start the backend server by running json-server --watch db.json.
Test your server by visiting the route http://localhost:3000/transactions in your browser.
Core Features
Bank of Flatiron offers the following core features:

Table of Transactions: Displays a table of recent bank transactions.
Add New Transaction: Allows users to fill out and submit a form to add a new transaction. The new transaction is added to the table and posted to the backend API for persistence.
Search Bar: Enables users to filter transactions by typing into the search bar. Only transactions with a description matching the search term are shown in the transactions table.
Adding a New Transaction
To add a new transaction:

Fill out the form with the required details such as description, amount, date, etc.
Submit the form.
The new transaction will be added to the table and posted to the backend API for persistence.
Filtering Transactions
To filter transactions:

Type the desired search term into the search bar.
The transactions table will dynamically update to show only transactions with descriptions matching the search term.
