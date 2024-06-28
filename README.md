
# Cryptocurrency Data Analysis

This repository contains a Python script for analyzing cryptocurrency data. The script reads two CSV files containing minute-by-minute cryptocurrency trading data from Bitstamp and Coinbase, and performs various data visualization tasks, including plotting the distribution of column values and displaying correlation matrices.

## Table of Contents

- [Project Structure](#project-structure)
- [Data Sources](#data-sources)
- [Setup](#setup)
- [Usage](#usage)
- [Functions](#functions)
  - [plotPerColumnDistribution](#plotpercolumndistribution)
  - [plotCorrelationMatrix](#plotcorrelationmatrix)
- [Output](#output)

## Project Structure

```
cryptocurrency-data-analysis/
├── README.md
├── analysis.py
└── data/
    ├── bitstampUSD_1-min_data_2012-01-01_to_2019-08-12.csv
    └── coinbaseUSD_1-min_data_2014-12-01_to_2019-01-09.csv
```

## Data Sources

- `bitstampUSD_1-min_data_2012-01-01_to_2019-08-12.csv`: This file contains minute-by-minute trading data from the Bitstamp exchange from January 1, 2012, to August 12, 2019.
- `coinbaseUSD_1-min_data_2014-12-01_to_2019-01-09.csv`: This file contains minute-by-minute trading data from the Coinbase exchange from December 1, 2014, to January 9, 2019.

## Setup

1. Clone this repository to your local machine:

    ```sh
    git clone https://github.com/your-username/cryptocurrency-data-analysis.git
    ```

2. Navigate to the project directory:

    ```sh
    cd cryptocurrency-data-analysis
    ```

3. Install the required Python libraries:

    ```sh
    pip install matplotlib numpy pandas sklearn
    ```

4. Place the CSV data files in the `data/` directory.

## Usage

Run the analysis script:

```sh
python analysis.py
```

This script will read the data files, display the structure of the data, and generate visualizations for data distribution and correlation matrices.

## Functions

### plotPerColumnDistribution

```python
def plotPerColumnDistribution(df, nGraphShown, nGraphPerRow):
    # Function to plot the distribution of each column in the dataframe.
```

- **df**: The dataframe containing the data.
- **nGraphShown**: Number of graphs to show.
- **nGraphPerRow**: Number of graphs per row.

### plotCorrelationMatrix

```python
def plotCorrelationMatrix(df, graphWidth):
    # Function to plot the correlation matrix of the dataframe.
```

- **df**: The dataframe containing the data.
- **graphWidth**: Width of the correlation matrix graph.

## Output

- **Data Summary**: Prints the number of rows and columns in each dataset.
- **Distribution Graphs**: Displays the distribution of values in each column.
- **Correlation Matrices**: Shows the correlation matrix of the data.

---

By following the steps in this README, you will be able to analyze the cryptocurrency trading data and visualize important aspects of the dataset. If you have any questions or encounter any issues, please feel free to open an issue in this repository.
```

### Key Sections Explained:
1. **Project Structure**: Shows the layout of the project files and directories.
2. **Data Sources**: Describes the data files used in the analysis.
3. **Setup**: Provides instructions for cloning the repository, installing dependencies, and preparing the data files.
4. **Usage**: Explains how to run the script.
5. **Functions**: Documents the main functions used in the script.
6. **Output**: Describes the expected output of the script.
