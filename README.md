# Swiss Daily Commute Data Visualization

This repository contains a data visualization project that focuses on the daily commute of people in Switzerland, segmented by each region. The primary goal of this project is to visualize and analyze the daily kilometers traveled by individuals in different Swiss regions, using a choropleth map and a stacked bar graph. The data used for this project is sourced from [insert data source here].

## Table of Contents
- [Introduction](#introduction)
- [Project Details](#project-details)
- [Technologies Used](#technologies-used)
- [Data Sources](#data-sources)
- [Results](#results)
- [License](#license)

## Introduction
The daily commute is a critical aspect of people's lives, and understanding commuting patterns can provide valuable insights into transportation infrastructure, environmental impact, and regional disparities. This project visualizes Swiss daily commute data using a choropleth map and a stacked bar graph to give viewers a comprehensive overview of daily commuting patterns in Switzerland.

## Project Details
### Choropleth Map
The choropleth map displays the amount of kilometers traveled in a day by residents in different Swiss regions. It uses color intensity to represent the volume of daily commute, with darker colors indicating higher values. The map is created using the [Folium](https://python-visualization.github.io/folium/) library in Python.

![image](https://github.com/disanza-franck/Swiss-Commute/assets/146677173/f1377187-97f3-48c3-a638-1cc385d56d6e)

### Stacked Bar Graph
The stacked bar graph provides a breakdown of daily commute distances by different modes of transportation, such as car, public transport, cycling, and walking. It allows viewers to see the distribution of commute methods across Switzerland. The graph is generated using the [Matplotlib](https://matplotlib.org/) library in Python.

![image](https://github.com/disanza-franck/Swiss-Commute/assets/146677173/d208fefa-4d09-46c3-a3bc-e1a73575b64d)

## Technologies Used
- Python
- [Folium](https://python-visualization.github.io/folium/)
- [Pandas](https://pandas.pydata.org/)
- [Matplotlib](https://matplotlib.org/)

## Data Sources
### GeoJSON File for Swiss Regions
The GeoJSON file for Swiss regions can be obtained from [Cartography Vectors](https://cartographyvectors.com/map/1522-switzerland-with-regions). Download and place the GeoJSON file in the appropriate directory of this project.

### Daily Commute Dataset
The dataset containing daily commute information is obtained from the Swiss Federal Statistical Office (BFS) and can be found at [BFS Dataset](https://www.bfs.admin.ch/bfs/fr/home/statistiques/catalogues-banques-donnees/tableaux.assetdetail.24025445.html). Download the dataset and place it in the data directory of this project.

## Results
The visualizations in this project offer valuable insights into Swiss daily commuting patterns, providing an easy-to-understand representation of regional differences and the modes of transportation preferred by residents.

## License
This project is licensed under the [MIT License](LICENSE). You are free to use and modify this project for your own purposes, but please ensure that you adhere to the terms of the license and give appropriate credit.
