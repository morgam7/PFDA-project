# Weather Data Analysis Project

## Project Overview
This project analyzes historical wind speed data from Met Éireann weather stations in Ireland. The primary goal is to explore trends and potential applications for wind energy projects, such as wind farms. 

This repository contains:
- Jupyter Notebook(s) with data analysis and visualizations.
- Weather data files sourced from Met Éireann.
- Documentation detailing the project's methodology and results.

## Prerequisites
To run the code, ensure the following libraries are installed:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `jupyter`

Use the following command to install them:
```bash
pip install pandas numpy matplotlib seaborn jupyter
```

## Files and Structure
- `wind_farm_analysis.ipynb`: Main Jupyter Notebook containing the analysis and visualizations.
- `data/`: Directory containing weather data files.
- `README.md`: This file, describing the project structure and usage.


## References

There were a lot of weather stations but I wanted the ones with windspeed so found a list of the bigger weather stations 
and downloaded 19 of the bigger weather station data. Was a bit clumsy having to download and unzip all the files individually - wonder if there is a better workflow for this.

List of weather stations with windspeed: 
https://www.met.ie/climate/weather-observing-stations

The following resources were used in this project:
- [Met Éireann Historical Weather Data](https://www.met.ie/climate/available-data/historical-data)
- Additional resources will be documented in the notebook where applicable.

## Notes
This is a work-in-progress project with a goal of completing a passable version as soon as possible, followed by iterative improvements over time.