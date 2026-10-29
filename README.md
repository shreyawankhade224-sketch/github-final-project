# Simple Interest Calculator App

A simple Bash script that calculates simple interest based on user input.

## About

The `simple-interest.sh` script asks for three values and computes the simple interest:

- **Principal** - the initial amount of money
- **Rate of interest** - the annual interest rate in percent
- **Time period** - the duration in years

## Formula

Simple Interest = (Principal x Rate x Time) / 100

## Usage

1. Make the script executable: chmod +x simple-interest.sh
2. Run the script: ./simple-interest.sh
3. Enter the principal, rate of interest and time period when prompted.

## Example

Principal = 1000, Rate = 5, Time = 2

Simple Interest = (1000 x 5 x 2) / 100 = 100

## Requirements

- Bash shell
- bc (basic calculator) command
