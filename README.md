# Project 1 Read Me

*You are a Rice Fintech Bootcamp student tasked with a group project on showcasing the skills you've learned thus far in class. Below is what your readme file might look like for your first project.*

# Group 2 - Street Smarts: Beating the Used Car Salesman
![used_car_salesman](https://user-images.githubusercontent.com/85652410/129506201-ce92dedd-5ae0-4e39-8f15-cc552311e47c.jpg)


####
#### The used car market is currently experiencing an all time high with prices rising by 45% during the last 12 months. This activity in the market corresponds to threats of rising inflation and potential increase in interest rates, alongside news of ongoing supply shortages in automotive electronics. Our project focuses on analyzing used car sales data to navigate the best buying and selling opportunities in the current market. We examine current geographical trends across vehicle type, specifications, mileage, and units sold as well as compare changes in the economic landscape.
####
#### Our business case is aiming to establish a best deal service to support car evaluations and discover regional hotspots best overall sellers. The opportunities with our project can lead to facilitating existing markets, possible market dominance, and advertisements with dealership/individual shopping tools.
---

## Technologies

The programming language for this project is Python. This project was run in VSCode with Jupyter Notebook extension. Additionally, we used QGIS 3.16.9 to plot out over 80,000 data points on a map of the United States. 

The link to download QGIS 3.16.9 can be found here:
https://qgis.org/en/site/forusers/download.html

Additional resources to work with QGIS 3.16.9 can be found here, including how to add in your own CSV files to points on a map:
https://www.qgis.org/en/site/about/index.html

---

## Installation Guide

*In this section, you should include detailed installation notes containing code blocks and screenshots.*

It is extremely important that you install the dependencies listed below, before running this application.

The installations for this application are as follows:
```python
pip install pandas
pip install pathlib
pip install pytest
pip install numpy
pip install seaborn
pip install simulation
```

---

## Examples

What the cleaned CSV data showed look like when imported into the Jupyter Notebook.
![vehicles_used_pd head()](https://user-images.githubusercontent.com/85652410/129505432-0266a389-c358-4e9a-9e50-5a0c778a24da.png)

Comparison of specific vehicle type by region based on specific odometer range, vehicle condition, & manufacturer.
![vehicle_comparison_ex](https://user-images.githubusercontent.com/85652410/129506008-1d3c1331-fe17-4c6b-af9b-9c8c2f76f355.png)

---

## Usage

How our QGIS looked after plotting all 80,000+ data points using the given latitudes and longitudes of the cleaned CSV data.
![qgis_plotted_map](https://user-images.githubusercontent.com/85652410/129507759-f15cfcbe-685b-4392-81e8-6640694f510b.jpg)

Vehicles for sale by region and condition between 75,000 to 100,000 miles. The regions are Houston and San Diego for the scope of this project.
![vehicle_region_condition](https://user-images.githubusercontent.com/85652410/129511777-b3133fea-4831-4f3e-a8a2-f996aa693cf8.png)


---

## Contributors

This current project was a combined effort of the Rice University Fintech Bootcamp Group 2 members: Ashley Guidot, Vishwanath Subramanian, and Forrest Surles. This project was also unofficially sponsored by used cars for sale in the greater Houston Area.

---

## License

The license for this project is MIT. The MIT License requires copyright and license notices must be preserved.
