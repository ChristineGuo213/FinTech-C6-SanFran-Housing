# Challenge6

# Housing Markets Buy and Rent Strategies

This python command-line interface application is designed to  offer an instant, one-click service for people to buy properties and then rent them, using San Francisco as an example. The application works by reading in a csv file and analyzing the data by using interactive visualizations with Plotly and the Mapbox API. Based on the plot results, it gives a clear picture of how the gross rent and sale price correlates to each other and helps make recommendations on the potential one-click, buy-and-rent strategy. 

---

## Technologies

This project leverages Python 3.7 with the following packages and dependencies:

* [pandas](https://pandas.pydata.org/) - An open-source data analysis and manipulation tool.

* [os](https://docs.python.org/3/library/os.html) - For accessing the API key from the environment file

* [dotenv](https://pypi.org/project/python-dotenv/) - To use the env functionality for accessing the API key from the environment file
 
* [plotly.express](https://plotly.com/python/plotly-express/) -  Contains functions that can create entire figures at once, and is referred to as Plotly Express or PX

* [hvplot.pandas](https://hvplot.holoviz.org/user_guide/Introduction.html) - Creates modern and interactive plots and makes it easier to explore the properties of the data

* [pathlib](https://docs.python.org/3/library/pathlib.html) - Instantiates a concrete path for the platform the code is running on

---

## Installation Guide

Python 3.7, GitBash, and JupyterLab are required to be installed before running the application.

---

## Usage

To use the Housing Markets Buy and Rent Strategies application simply clone the repository and run the **san_francisco_housing.ipynb** with:

```python
san_francisco_housing.ipynb
```

Attached screenshots below show the different plots

![zoomed_housing_units_by_year](SanFran_Housing_Markets/Images2/zoomed_housing_units_by_year.png)

![avg_sale_px_sq_foot_gross_rent](SanFran_Housing_Markets/Images2/avg_sale_px_sq_foot_gross_rent.png)  

![pricing_info_by_neighborhood](SanFran_Housing_Markets/Images2/pricing_info_by_neighborhood.png)

![mapbox_plot](SanFran_Housing_Markets/Images2/mapbox_plot.png)


---

## Contributors

Brought to you by Trilogy and Christine Guo (www.linkedin.com/in/christine-guo)

---

## License

NoNe