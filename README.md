# earthquake_temporal_prediction_kaggle_data

## Introduction

We are going to dive in to the Kaggle "LANL Earthquake Prediction" data set and see what we can figure out about predicting the timing of earthquakes in a synthetic laboratory environmentr based on a provided seismic data stream. 

For all of the details of the Kaggle compettion, check out the official site,

        https://www.kaggle.com/c/LANL-Earthquake-Prediction

![The homepage of Kaggle's LANL Earthquake Prediction competition. ](/img/page_capture_kaggle.png)

Note up front that the official competition ended on June 3, 2019, so we are not going to win any money as we sit here working on this in July 2019. Despite the lack of direct monetary reward, there is still a ton of value to be gained by diving into this facinating dataset. And maybe even more so now that all of the official entries are in and we can learn from what has been tried and what approaches had the most sucess in the official competition.          

The data for this earthquake prediction challenge is huge. The training data is 9.83 GB on my machine. Go get the data yourself from the Kaggle site,

        https://www.kaggle.com/c/LANL-Earthquake-Prediction/data

and put it somewhere and update the "data_path" variable in the notebooks so that the code here will work. 

## Test Data Viz

![6 randomly selected test data segments. ](/img/test-data-pic.png)
