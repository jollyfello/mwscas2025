# Biosensor Patent Analysis - MWSCAS 2025

## Overview

This project analyzes **biosensor patents** using data from the [PatentsView API](https://www.patentsview.org/). The notebook automates the process of **querying, categorizing, and visualizing** biosensor-related patents.

## Features

- **Patent Data Retrieval**: Queries the PatentsView API to fetch relevant biosensor patents.
- **Data Processing**: Cleans and structures the dataset for further analysis.
- **Categorization**: Classifies patents into specific biosensor-related categories.
- **Visualization**:
  - Stacked bar chart: Patents per year by category.
  - Bubble chart: Patent trends across different technologies.
  - Other exploratory data insights.

## Installation

To run this notebook locally, make sure you have the following dependencies installed:

```bash
pip install pandas requests matplotlib seaborn json
```

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/biosensor-patents.git
   cd biosensor-patents
   ```
2. Run the Jupyter Notebook:
   ```bash
   jupyter notebook Query_and_Visualizations.ipynb
   ```
3. Modify API parameters in the notebook to adjust search criteria.

## Data Sources

- **[PatentsView API](https://www.patentsview.org/)**: Used for retrieving patent metadata.

## Contributing

If you’d like to contribute, feel free to open an issue or submit a pull request.

## License

This project is released under the **Creative Commons CC0 (CC Zero) License**, which means you can copy, modify, distribute, and perform the work, even for commercial purposes, all without asking permission.
