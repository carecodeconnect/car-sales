# Car Sales Analysis

An interactive report and presentation providing:

🚗 Analysis of UK car sales data (2023-2024)

📊 Popularity, price, and unit sales/revenue

🚀 Recommendations for increasing revenue:

1. Investigate sales in Bath
2. Sell Jeep, RAM, Dodge, Mazda, Chevrolet models
3. Start marketing campaign during Q1 (March)

## Usage

To read the report, click [here](https://carecodeconnect.quarto.pub/car-sales-analysis-report/).

To read the presentation, click [here](https://carecodeconnect.quarto.pub/car-sales-analysis-presentation/).

To see my working, see the `PDF` files in the `notebooks` folder.

## Tools

The report and presentation were built using:

* [Quarto](https://quarto.org/) open source scientific and technical publishing system (version 1.5.6)

* [Python](https://www.python.org/) version 3.10.

## Development

To develop with this project, follow these steps:

1. Clone the repository to your local machine:

   ```
   git clone https://github.com/carecodeconnect/car-sales
   ```

2. Navigate to the project directory:

   ```
   cd car-sales
   ```

3. Setup your environment and required dependencies:

   ```
   conda create -n car-sales python=3.10
   pip install -r requirements.txt
   ```

4. Open the notebooks or Quarto files with your chosen text editor.

5. Install Quarto (follow instructions [here](https://quarto.org/docs/get-started/)).

6. To publish on the web with `Quarto`, you will need an account at [Quarto Pub](https://www.quartopub.com), and then run:

   ```
   cd quarto
   quarto publish quarto-pub document.qmd
   quarto publish quarto-pub presentation.qmd
   ```

## Project Structure

Below is the tree structure of the project for quick reference:

```
├── data/                   # Folder containing data files
├── notebooks/              # Folder containing Jupyter notebooks
├── quarto/                 # Folder containing Quarto files 
├── LICENCE                 # MIT licence
├── README.md               # Project overview and setup instructions
└── requirements.txt        # List of dependencies to install
```
