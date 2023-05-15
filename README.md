# Mars Data Analysis Challenge

This repository contains the code and analysis for the Mars Data Analysis Challenge. The challenge involved analyzing a dataset of Martian weather data and performing various tasks using pandas and matplotlib.

## Dataset

The dataset used for this analysis consists of Martian weather data, including the terrestrial date, sol (Martian day), ls (Martian season), month, minimum temperature, and pressure. The dataset spans several Martian years.

## Tasks

1. Determining the number of months on Mars: In the initial analysis, we found that there are 12 months on Mars based on the unique values in the 'month' column of the dataset.

2. Calculating the number of Martian days' worth of data: By counting the number of rows in the dataset, we determined the number of Martian days' worth of data available.

3. Finding the average low temperature by month: Using the 'groupby' function in pandas, we calculated the average low temperature for each Martian month.

4. Identifying the coldest and hottest months in Curiosity's location: We identified the coldest and hottest months by sorting the average low temperature values and extracting the corresponding months.

5. Determining the length of a Martian year in Earth days: While the code provided for plotting the temperature data against Earth days does not calculate the length of a Martian year, we discussed an alternative approach using Kepler's third law to calculate it based on Mars' orbit.

## Code and Visualizations

The code for the analysis tasks is available in the Jupyter Notebook file 'Mars_Data_Analysis.ipynb'. It includes the pandas and matplotlib code used for data manipulation, calculations, and plotting.

The visualization of temperature variation in Martian years is presented in the plot shown below:
[Insert the image of the plot or provide a link to it]

## Conclusion

This challenge allowed me to analyze Martian weather data and perform various tasks using pandas and matplotlib. By exploring the dataset, I gained insights into the Martian climate and learned about different aspects of analyzing scientific data. The code and analysis provided in this repository can serve as a starting point for further exploration and study of Martian weather patterns.

