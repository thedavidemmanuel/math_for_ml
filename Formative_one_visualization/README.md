## Overview

This project involves an analysis of a vehicle dataset with a focus on understanding the relationships between various vehicle characteristics, fuel efficiency, and CO2 emissions. The aim is to leverage this data for AI purposes, particularly in the context of the recent ASC23 initiative, which considers systems-based tracks including transport.

## Dataset

The dataset contains multiple features such as make, model, year, class, drive type, transmission type, fuel type, number of cylinders, displacement, and various fuel efficiency metrics.

## Methodology

The analysis was performed using Python within a Google Colab notebook environment. The following libraries were utilized for data manipulation and visualization:

- NumPy
- Pandas
- Matplotlib
- Seaborn

## Key Visualizations

Two histograms and a heatmap were generated to visualize the data:

- **Histogram of CO2 Emissions**: Shows the distribution of CO2 emissions across vehicles, highlighting the skewness towards lower emissions.
- **Histogram of Combined Fuel Efficiency**: Illustrates the distribution of combined city and highway fuel efficiency, indicating a trend towards moderate efficiency levels.
- **Heatmap of Feature Correlations**: Reveals the positive correlation between different fuel efficiency metrics and the negative correlation between fuel efficiency and CO2 emissions.

## Interpretations

The key findings from the visualizations suggest that:

- Vehicles with higher fuel efficiency tend to have lower CO2 emissions.
- Engine size (as represented by the number of cylinders and displacement) is inversely related to fuel efficiency and positively related to CO2 emissions.
- Fuel economy scores correlate positively with fuel efficiency and negatively with CO2 emissions, validating their use as indicators of vehicle environmental impact.

## Repository Contents

- `Plotting_Assignment.ipynb`: Jupyter notebook containing the analysis code and visualizations.
- `Plots/`: Directory containing exported PNG files of the plots.
- `fuel_econ.csv`: The dataset used for the analysis.

## Usage

To run the analysis, mount your Google Drive in the Colab notebook, navigate to the dataset, and execute the notebook cells in sequence.

## Contributing

Contributions to this project are welcome. Please fork the repository and submit a pull request with your suggestions.

## License

This project is open-source and available under the [MIT License](LICENSE).
