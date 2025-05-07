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

Once this data is entered, the program automatically calculates the capital evolution month by month. At the end of the simulation, it displays the total capital obtained after the specified duration and generates a graph showing the capital progression over time.

## Dependencies

This program requires only one external library:

- [`matplotlib`](https://matplotlib.org/): used to generate the capital growth chart

If it's not already installed, you can install it with:

```bash
pip install matplotlib


The code can be used in environments such as Google Colab, Jupyter Notebook, Spyder, or any graphics-enabled Python editor. It doesn't require a database connection or complex configuration.
