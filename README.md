# vtu32999.A-NEW-CORPUS-A-NEW-GOLD-REWARD# Weather Reward AI — A New Corpus and a New Gold Reward

**Author:** K. Kusuma  
**Student ID:** VTU32999

## Project Overview

This project demonstrates a weather-report corpus, a word-transition reference model, and a gold reward function that prefers short reports containing numeric temperatures.

## Objectives

- Create a domain-specific weather corpus.
- Build a reference model using observed word transitions.
- Generate weather reports through random sampling.
- Calculate reward scores for generated sentences.
- Visualize reward results through an interactive web interface.

## Technologies Used

- Python
- Google Colab
- Gradio
- Pandas
- Matplotlib

## Gold Reward Formula

`R(s) = I(temperature in s) - 0.1 × L(s)`

Here, `I` equals 1 if a numeric token is present, otherwise 0. `L(s)` is the number of words excluding special tokens.

## Features

- Weather corpus analysis
- Weather report generation
- Gold reward calculator
- Word transition explorer
- Reward comparison table
- Reward distribution graph

## How to Run

1. Open the notebook in Google Colab.
2. Install the required packages:

   `!pip install -q gradio pandas matplotlib`

3. Run the project code cells.
4. Open the Gradio sharing link to interact with the application.

## Limitations

The model uses a small corpus and observed word transitions. It is an educational demonstration, not a production weather forecasting system.

## Author

K. Kusuma — VTU32999
