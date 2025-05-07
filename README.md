# Savings / Investment Simulator

## Project Objective

This program was developed to provide a simple and accessible tool to better understand the principles of long-term saving and investing.  
It is intended primarily for individuals who want to plan their finances over time, such as regular savers or students looking to visualize the power of compound interest.

The simulator models how a capital investment grows over time when monthly contributions are made and interest is compounded. It helps users see how time and consistency can impact overall returns.

## How It Works

The user can easily modify three key parameters in the code:

- `monthly_saving`: amount saved each month (in euros)
- `annual_interest_rate`: annual interest rate (as a percentage)
- `years`: investment duration (in years)

Once the parameters are set, the program:

1. Calculates capital growth month by month, using compound interest.
2. Displays the **final capital** after the investment period.
3. Generates a **graph** showing capital progression over time.

## Dependencies

This program requires only one external library:

- [`matplotlib`](https://matplotlib.org/): used to generate the capital growth chart

If it's not already installed, you can install it with:

```bash
pip install matplotlib

