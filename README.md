
# Identity Theft Analysis

## Project Overview

This project aims to analyze and visualize trends in identity theft cases over the past 25 years. By examining the dataset, we can identify patterns, peak years, and potential correlations with other socio-economic factors. The insights gained from this analysis can help inform policies and preventative measures against identity theft.

## Technologies Used

- **Python**: The primary programming language used for data analysis and visualization.
- **Pandas**: A powerful data manipulation library for handling and analyzing data in DataFrames.
- **Matplotlib**: A plotting library for creating static, animated, and interactive visualizations in Python.
- **Seaborn**: A statistical data visualization library based on Matplotlib, providing a high-level interface for drawing attractive graphics.
- **Jupyter Notebook**: An open-source web application that allows for the creation and sharing of documents containing live code, equations, visualizations, and narrative text.

## Installation

To set up the project environment, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone <https://github.com/furmak331/IdentityTheftAnalysis.git>
   cd identity-theft-analysis
   ```

2. **Create a virtual environment (optional but recommended):**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install the required packages:**
   ```bash
   pip install pandas matplotlib seaborn
   ```

## Dataset

The dataset used in this project contains records of identity theft cases reported over 25 years. It includes the following columns:

- `Year`: The year the cases were reported.
- `Cases`: The number of identity theft cases reported in that year.

Make sure to place the dataset file in the same directory as your notebook or update the path in the code accordingly.

## Usage

1. Open the Jupyter Notebook file (`identity_theft_analysis.ipynb`).
2. Run the cells sequentially to perform exploratory data analysis (EDA) and generate visualizations.

## EDA Features

- **Trends Over Time**: Visualize the number of identity theft cases reported over the years.
- **Yearly Summary**: Group the data by year to summarize total cases.
  
## Contributing

Contributions are welcome! If you have suggestions for improvements or additional features, please create a pull request or open an issue.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [Matplotlib Documentation](https://matplotlib.org/stable/contents.html)
- [Seaborn Documentation](https://seaborn.pydata.org/)

---
