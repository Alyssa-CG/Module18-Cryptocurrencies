# Cryptocurrencies and Unsupervised Machine Learning

## Project Overview

Unsupervised Machine Learning was used to inspect Cryptocurrency data to identify trends and information.

## Resources
#### Language and Packages
* Python v 3.7.6
* Pandas v 1.0.3
* hvPlot v 0.6.0
* Plotly v 4.9.0
* Scikit-learn v 0.22.1

#### Data
* [crypto_data.csv](https://github.com/Alyssa-CG/Module18-Cryptocurrencies/blob/master/Resources/crypto_data.csv)

## Summary and Visualizations

Data was analysed by means of unsupervised machine learning. An elbow curve was used to determine clusters for data to be broken into, from which it was decided that six clusters would be used as the line turns quite horizontal at that point.

![Elbow Curve](https://github.com/Alyssa-CG/Module18-Cryptocurrencies/blob/master/Visualizations/elbow_curve.png)

After this, a both a 2D model and a 3D model were created to visualize the clusters, as shown below.

![2D](https://github.com/Alyssa-CG/Module18-Cryptocurrencies/blob/master/Visualizations/2D_scatter.png)

![3D](https://github.com/Alyssa-CG/Module18-Cryptocurrencies/blob/master/Visualizations/3D_scatter.png)

A hvplot.table table, wherein columns could be sorted was also created. It is shown below, sorted alphabetically by Algorithm.
![hvplot.table](https://github.com/Alyssa-CG/Module18-Cryptocurrencies/blob/master/Visualizations/hvplot.table.png)




