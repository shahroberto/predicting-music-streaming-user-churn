### Table of Contents

1. [Dependencies](#dependencies)

2. [Project Motivation](#motivation)

3. [File Descriptions](#files)

4. [Results](#results)

5. [Licensing, Authors, and Acknowledgements](#licensing)

## Dependencies <a name="dependencies"></a>

This code requires the Anaconda distribution of Python versions 3.*. and PySpark's SQL & ML libraries:

```

$ conda install pyspark

```

## Project Motivation<a name="motivation"></a>

Sparkify is a hypothetical music streaming service app, similar to Spotify, created by Udacity for the purpose of analyzing customer usage in this space.

We’re going to predict customer churn on the Sparkify music app by leveraging Apache Spark’s ETL and ML libraries to create different models to decide if a user is at risk of cancellation by

1. exploring the difference in features on churned vs. other users.

2. constructing an input dataset where each row is an aggregated representation of a specific user.

3. using the aggregated dataset as input to different classification models to predict churn.

## File Descriptions <a name="files"></a>

There is 1 notebook available here to showcase work related to the above motivation.  Markdown cells were used to assist in walking through the thought process for individual steps.  

1. `PredictingUserChurn.ipynb` provides exploratory analysis, feature engineering, and predictive modelling to determine user churn on the Sparkify streaming app.

## Results<a name="results"></a> 

The main findings of the code can be found at the post available [here](https://robertshaheen.medium.com/predicting-user-churn-in-a-music-streaming-service-9da00c1a133d).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Must give credit to Udacity for the data.  You can find the Licensing for the data and other descriptive information at the Licensing link available [here](https://creativecommons.org/publicdomain/zero/1.0/).
