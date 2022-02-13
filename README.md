# Housing Rental Analysis for San Francisco

This Jupyter notebook visualizes and analyzes San Francisco real-estate data in order  
to find properties in the San Francisco market that are viable investment opportunities.

This notebook:

* Calculates and plots the housing units per year.

* Calculates and plots the average prices per square foot.

* Compares the average prices by neighborhood.

* Builds an interactive neighborhood map for visual data analysis.

### Compares the Average Sale Prices by Neighborhood

Interactive visualizations and widgets explore the average sale price per square foot by neighborhood.

![A screenshot depicts an example of the resulting plot.](Images/pricing-info-by-neighborhood.png)

### Builds an Interactive Neighborhood Map

Observe the geospatial relationships in the data by using interactive visualizations with hvPlot and GeoViews.

![A screenshot depicts an example of a scatter plot created with hvPlot and GeoViews.](Images/6-4-geoviews-plot.png)


## Technologies
This notebook requires:

![Jupyter Logo](https://docs.jupyter.org/en/latest/_static/jupyter.svg)
<br>This notebook requires Jupyter lab
<br>Installation:
```
pip install jupyterlab
````

This applications uses pandas<br>
![pandas Logo](https://pandas.pydata.org/docs/_static/pandas.svg)

```
pip install pandas
```
This application uses Pathlib<br>
```
pip install pathlib
```

![PyViz Logo](https://pyviz.org/_static/logo.png)
<br>This application uses pyviz and the associated hvplot and geoviews
```
conda install -c pyviz hvplot geoviews
```


## Contributors

Brought to you by Rachel Bates.

---

## License

MIT