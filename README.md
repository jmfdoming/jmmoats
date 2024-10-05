# Moats Analysis App

## Overview
This project is a Streamlit web application designed to analyze the competitive advantages (moats) of different companies. The user can enter the ticker symbol of a company to retrieve detailed information about its competitive advantages, such as cost advantage, efficient scale, intangible assets, network effect, and switching cost.

The data is loaded from an Excel file (`moats.xlsx`), which must be available in the same directory as the application script.

## Features
- Enter a company's ticker symbol to get an analysis of its competitive advantages.
- Displays only relevant moats (e.g., Cost Advantage, Efficient Scale, etc.) if they are significant.
- Includes a rationale summary for the given company.

## Prerequisites
- Python 3.7 or higher
- [Streamlit](https://streamlit.io) library
- [Pandas](https://pandas.pydata.org/) library
- The Excel file (`moats.xlsx`) containing company data

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/moats-analysis-app.git
   ```
2. Navigate to the project directory:
   ```bash
   cd moats-analysis-app
   ```
3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```
   Note: Make sure you have `moats.xlsx` in the project directory.

## Running the App
Run the following command to start the application:
```bash
streamlit run appmoats.py
```

## Usage
- Enter the company's ticker symbol in the provided input field.
- The app will display the company's name, any significant economic moat (e.g., Cost Advantage, Network Effect), and the rationale behind it.

## File Structure
- `appmoats.py`: The main application script.
- `moats.xlsx`: The Excel file containing company data.
- `requirements.txt`: List of required dependencies.

## Example
If you enter `AAPL`, the app will display:
- The company name (e.g., "Apple Inc.")
- The type of economic moat the company has (e.g., "Cost Advantage", "Network Effect")
- A rationale explaining the moat in detail

## Screenshots
![Moats Analysis App Screenshot](screenshot.png)

## License
This project is licensed under the MIT License.

## Author
Developed by José Miguel Fernández

