# H1B Geospatial Analysis

## Overview
This repository contains a Jupyter Notebook focused on analyzing H1B visa data using geospatial techniques. The primary goal is to explore and visualize the geographic distribution of H1B visa applications, including the prevailing wages and case statuses across different states in the United States.

## Features
- **Geospatial Analysis:** Visualization of H1B visa data across different states, focusing on metrics like prevailing wage and case status.
- **Data Visualization:** Uses various Python libraries such as Seaborn and Matplotlib to create heatmaps, scatter plots, and other visualizations.
- **Clustering and Analysis:** Includes techniques like clustering to group states based on similar metrics (e.g., prevailing wage).

## Project Structure
- `H1B_Geospatial.ipynb`: The main Jupyter Notebook containing the data analysis, visualizations, and code.

## Installation
To run the notebook, you need to have Python installed along with the necessary libraries. Follow the steps below to set up your environment:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your_username/H1B_Geospatial.git
   cd H1B_Geospatial
   ```

2. **Set up a virtual environment (optional but recommended):**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install the required packages:**
   ```bash
   pip install -r requirements.txt
   ```

   *If a `requirements.txt` file is not provided, install the necessary libraries manually:*
   ```bash
   pip install pandas matplotlib seaborn
   ```

4. **Run the Jupyter Notebook:**
   ```bash
   jupyter notebook H1B_Geospatial.ipynb
   ```

## Usage
After running the Jupyter Notebook, you can follow along with the analysis, which includes:

- Loading and exploring H1B visa data.
- Visualizing the distribution of H1B visa applications across various states.
- Analyzing the relationship between prevailing wages and case statuses (CERTIFIED vs. DENIED).

## Sample Visualizations
The notebook generates various visualizations, including:

- **Heatmaps:** To display the average prevailing wage across states.
- **Scatter Plots:** To compare prevailing wage with the binary case status (CERTIFIED = 1, DENIED = 0).
- **Clustering:** To group states based on similarities in the H1B visa data.

## Contributions
Contributions to this project are welcome. If you encounter any issues or have suggestions, please feel free to create an issue or submit a pull request.

## License
This project is licensed under the Apache License - see the [LICENSE](LICENSE) file for details.
