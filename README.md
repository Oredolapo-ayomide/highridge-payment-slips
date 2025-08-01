# Highridge Construction Company – Worker Payment Slip Generator

## Overview

This project generates payment slips for 400 dynamically created workers using both Python and R. Each worker has a randomly assigned name, gender, ID, and salary.

## Features

- Dynamically creates 400 worker profiles.
- Assigns salary and gender randomly.
- Applies rules for Employee Level:
  - `A1`: Salary > $10,000 and < $20,000.
  - `A5-F`: Female and salary > $7,500 and < $30,000.
- Exception handling to catch and report errors.
- Outputs weekly payment slips in both Python and R.

## Files

- `payment_slips.py`: Main Python script.
- `payment_slips.R`: Translated R script.
- `README.md`: Instructions and project overview.

## How to Run

### Python
Ensure you have Python 3.13 installed.

File: python payment_slips.py


### R Version
File: payment_slips.R

#### Requirements
R (version 3.6 or higher recommended)

Can be run in RStudio or base R console

#### How to Run:

Open R or RStudio.

Set the working directory to the folder containing payment_slips.R.

Run the script using:

```bash
source("payment_slips.R")
