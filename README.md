# Banking Marketing Campaign Analysis

This repository contains data and analysis related to direct marketing campaigns of a Portuguese banking institution. The dataset includes details such as client demographics, campaign specifics, and subscription outcomes, with the goal of predicting whether a client will subscribe to a term deposit.

# Dataset Overview

The dataset (Banking_data.csv) contains 45,211 rows and 18 columns, ordered by date from May 2008 to November 2010. Each row represents a client contacted during a marketing campaign, with columns including:

    age: Age of the client
    job: Type of job the client has
    marital: Marital status of the client
    education: Level of education of the client
    default: Whether the client has credit in default
    balance: Average yearly balance in euros for the client
    housing: Whether the client has a housing loan
    loan: Whether the client has a personal loan
    contact: Type of communication used to contact the client
    day: Last contact day of the month
    month: Last contact month of the year
    duration: Duration of the last contact in seconds
    campaign: Number of contacts performed during this campaign for this client
    pdays: Number of days since the client was last contacted from a previous campaign
    previous: Number of contacts performed before this campaign for this client
    poutcome: Outcome of the previous marketing campaign
    y: Target variable indicating whether the client subscribed to a term deposit (yes/no)

# Repository Structure

    Banking_data.csv: The dataset used for analysis
    banking.ipynb: Jupyter notebook containing the analysis code
    README.md: This file providing an overview of the repository

# Usage

To replicate the analysis:

    Clone this repository to your local machine
    Install the necessary libraries listed in requirements.txt
    Run the banking.ipynb notebook in a Jupyter environment
