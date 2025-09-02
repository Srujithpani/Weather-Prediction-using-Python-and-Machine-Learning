# Project Overview

In this project, we'll predict tomorrow's temperature using historical data.  We'll start by downloading a dataset of local weather.  You can customize this to your own location.  Then, we'll clean the data and get it ready for machine learning.  We'll build a system to make historical predictions.  Then, we'll add more predictors to improve the model.  We'll end with how to make next-day predictions.

**Project Steps**
* Download weather data
* Clean and graph data
* Create a testing framework
* Improve model accuracy


File overview:

* `prediction.ipynb` - predict the temperature

# Local Setup

## Installation

To follow this project, please install the following locally:

* JupyerLab
* Python 3.8+
* Python packages
    * pandas
    * scikit-learn

## Data

We'll download our dataset from NOAA, a US government agency.  You can follow these instructions to download the data:

* Go to [NOAA Search](https://www.ncdc.noaa.gov/cdo-web/search)
* Enter the years you want data for, and search for the closest airport to you.
* Click add to cart on the airport you want.
    * If there is no airport near you, try your city or country name instead.
* Go to the [cart](https://www.ncdc.noaa.gov/cdo-web/cart)
* Select the csv format and click continue
* Select all of the checkboxes for data types.
* Enter your email and click continue.
* You'll get an email with a link to download the data.
