# Friends don't let friends over-fit: Benchmarking open source prediction methods on open building electrical meter data

## Abstract 
Prediction is a common machine learning (ML) models used on sub-hourly building energy consumption data. This process is valuable for anomaly detection, load profile-based control, energy plant systems control, and measurement and verification procedures. Literally hundreds of building energy prediction techniques have been developed over the last three decades, yet there is still no consensus on which techniques are the most effective for various building types. In addition, many of the techniques developed are proprietary and unavailable to the general research community. This paper outlines a library of open source regression techniques from the Scikit-Learn Python library and describes the process of applying them to open hourly electrical meter data from 482 non-residential buildings from data from the [**Building Data Genome Project**](https://github.com/buds-lab/the-building-data-genome-project). 

The results illustrate that there is no one size-fits-all modeling solution and that various types of temporal behavior are difficult to capture using machine learning. This framework and methodology is designed to be a *baseline* implementation for other building energy data prediction methods developed by commercial providers or the wider research community. The benchmark data set can also be expanded with numerous other building performance data from a wider representation of buildings from around the world. The use of a baseline data set in future prediction research results in comparability and reproducibility of techniques in the built environment domain. 

## [Raw Meter Data, Weather, Schedule and Meta Data Input Files](https://github.com/buds-lab/building-prediction-benchmarking/tree/master/input)

## [ML Modeling Jupyter Notebooks](https://github.com/buds-lab/building-prediction-benchmarking/tree/master/model_notebooks)

## [ML Model Raw Data Resuls](https://github.com/buds-lab/building-prediction-benchmarking/tree/master/results)

## [ML Data Visualization Jupyter Notebooks and Graphics](https://github.com/buds-lab/building-prediction-benchmarking/tree/master/visualization_notebooks)

## [Publication Draft](https://github.com/buds-lab/building-prediction-benchmarking/tree/master/publication)
