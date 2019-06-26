# Exoplanet Exploration


## Background

Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system.
To help process this data, you will create machine learning models capable of classifying whether a record is a candidate exoplanet from the dataset of observed objects.

The following was completed in this project:

1. [Preprocess the raw data](#Preprocessing)
2. [Tune the models](#Tune-Model-Parameters)
3. [Compare two or more models](#Evaluate-Model-Performance)

- - -

## Instructions

ASSUMPTIONS:

The features included in the starter code, and the Stellar Parameters were omitted from this analysis.
This data represents the KOI start, and I assumed the starts characteristics is independent of whether an object is an exoplanet.
As a result, these were omitted.

"rowid", "kepid", 
"kepoi_name", "kepler_name", 
"koi_pdisposition", "koi_score", 
"koi_tce_delivname", 'koi_steff', 
'koi_steff_err1', 'koi_steff_err2', 
'koi_slogg', 'koi_slogg_err1', 
'koi_slogg_err2', 'koi_srad', 
'koi_srad_err1', 'koi_srad_err2', 
'ra', 'dec', 'koi_kepmag'

### Preprocess the Data

* Preprocess the raw dataset prior to fitting the model.
* Perform feature selection and remove unnecessary features. The dataset includes 50 columns-- how many will be sufficient for a healthy model?
* Use `MinMaxScaler` to scale the numerical data.
* Separate the data into training and testing data.

### Tune Model Parameters

* Use `GridSearch` to tune model parameters.
* Tune and compare at least two different classifiers. Three is recommended.

### Evaluate Model Performance

Compare the performance of your tuned classifiers to determine the best-performing model.
