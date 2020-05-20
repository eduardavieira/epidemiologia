# Mapping of COVID-19 (coronavirus) data, Statistical Analysis and Parametric Curve Fitting

This project is a collection of Jupyter notebooks:

🗂️ [Mapping of COVID-19 data (.ipynb)](https://github.com/eduardavieira/epidemiologia/blob/master/COVID19-Project/Maps.ipynb)

🗂️ [Statistical Analysis of COVID-19 data and Parametric Curve Fitting(.ipynb)](https://github.com/eduardavieira/epidemiologia/blob/master/COVID19-Project/Stats.ipynb). 

Due to rendering issues we advise the use of [`nbviewer.jupyter.org`](https://nbviewer.jupyter.org/github/eduardavieira/epidemiologia/blob/master/COVID19-Project/Stats.ipynb) to visualize all graphics or to consult the [Figures link](https://github.com/eduardavieira/epidemiologia/tree/master/COVID19-Project/Figures). 

**Still a Project in Progress**


## Dataset

The Dataset is part of the [Our World in Data](https://github.com/owid/covid-19-data/tree/master/public/data/) repository on GitHub.

For a full variables description consult ([`owid-covid-data-codebook.md`](https://github.com/owid/covid-19-data/tree/master/public/data/owid-covid-data-codebook.md)).

## Motivation

One of the goals of this project was to understand how the economy, medical preparedness and population ageing influenced the number of cases of COVID-19 and consequent deaths.
Thus a dataset with the GDP per data of each country, extreme poverty levels, number of hospitals beds per 100K and share of population over 65 years old was used.

The Statistical Analysis allowed us to achieve this goal.

## Results


### Mapping

In the [Maps.ipynb notebook](https://github.com/eduardavieira/epidemiologia/blob/master/COVID19-Project/Maps.ipynb) was created the Map in the Figure below, where it is possible to consult the a map that contains COVID-19 death cases across the world.

![death map](https://github.com/eduardavieira/epidemiologia/blob/master/COVID19-Project/Figures/death_cases_map.png)


### Statistical Analysis

In the Figure below it is possible to consult the Top 15 countries with the highest share of population 65 years and older.

![Top_65](https://github.com/eduardavieira/epidemiologia/blob/master/COVID19-Project/Figures/top_15_aged_65.png)

In Figure below a bubble chart containing the 60 countries with the highest share of population 65 years and older and the number of deaths per million of each country can be consulted.

The countries with most prevalent population ageing, such as Belgium, Spain, United Kingdom, Italy, France and Sweden, have also the highest values of death cases per million.

It is also worth noting that countries such as Portugal (second most population aged country) and Germany (fourth most population aged country) do not have such high values of death cases per million, mostly due to severe policies regarding quarentine.

![bubble_65](https://github.com/eduardavieira/epidemiologia/blob/master/COVID19-Project/Figures/bubble_aged65_deaths_per_million.png)

### Parametric Curve Fitting of Iceland Cases

![Prediction Iceland](https://github.com/eduardavieira/epidemiologia/blob/master/COVID19-Project/Figures/prediction_parametric_fitting.png)