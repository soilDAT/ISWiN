# Use Cases

## Use Case 1: Get soil moisture content data

Users who want to use this local soil moisture data. These users are interested in the **output of our ML model** (and not the input). This includes users who only want to view the output (i.e. not download) and users who want to download and work with the output (i.e. download). These users generally want to query a location and a time period and get back a soil moisture timeseries.

### User List:

### Use case 1a: download output for analysis
1. Alisha (AMY 2)
    - use data to train ML
2. Philip (AMY 4)
    - use data for thesis project
3. KK (AMY 5)
    - use data for climate modelling
4. Eirik (AMY 7)
    - has a friend who wants to use the data for climate modelling
5. Caleb (LILA 1)
    - use data (simple interface to download)
6. Tara (CALEB 1)
    - well documented soil moisture data with uncertainty (local/regional)
7. Groig (CALEB 2)
    - data in a format that very easy comparable to other datasets (domain standard presentation)
8. Felice (CALEB 9)
    - wants to be able to look at broad regions and as long as possible time series
9. Bryce (LILA 6)
    - wants to compare our data with his own sensors (local)

### Use case 1b: view/visualize the output directly, not download for further analysis
1. Adity (LILA 2)
    - remotely access data (not downloaded)
2. Balthazar (CALEB 5)
    - very skeptic of our data so he would like the documentation to be very clear in terms of what we are doing/not doing with the data
3. Leopold (CALEB 6)
    - wants to be able to put in a location and get time series soil moisture accross seasons
4. Perry (CALEB 10)
    - wants a visualization of the data
5. Ema (ADITY 2)
    - use soil moisture data for research on local farms in Seattle
6. Daniel (ADITY 4)
    - use our data to understand where there are gaps in soil moisture data
        - (idea - heatmap of number of images as a 'confidence' metric by location)
7. Rachel (ADITY 5)
   - needs data with photo locations, observation dates and a way to match with historical weather data


## Use Case 2: Input user-submitted photos and get local soil moisture content out

These users have their own datasets and would like to use the model to infer soil moisuture content. These users are interested in both the **input and the output** of our ML model. They require the model to be small enough so that it can be run on laptop-level compute.    

### User List:
1. Stefan (AMY 1)
    - wants to estimate moisture level of his home plants
2. Naoko (AMY 8)
    - wants to use her own dataset, similar to the iNaturalist, to expand the soil moisture data. 
3. Crow (CALEB 3)
    - wants to use their photos of their farm to evaluate their watering protocol. 
4. Vera (CALEB 7)
    - wants to see what the iNaturalist dataset can be used for. 
5. Sophia (ADITY 3)
    - wants to use iNaturalist photos and soil moisture data to understand relationship between plant type and regional moisture levels. 
    - She wants to input her own images of Lila's plants 

## Use Case 3: Model Evaluation

These users are interested in the quality of the ML model used to predict soil moisture, and would like to be able to evaluate the performance of different versions(?) of the model.

### User List

### Use case 3a: help
1. Payton (AMY 6)
    - wants to help with this project (i.e. help improve the ML model)
2. Lila (LILA 3)
    - wants full access to training and test data to evaluate our model
3. Amy (LILA 4)
   - wants to improve the ML model
4. Rhea (LILA 5)
   - wants to be able to fix user submitted issues to the project
5. Clara (CALEB 4)
   - wants to be able to understand our full implementation to try and replicate it herself
6. Tabitha (CALEB 8)
   - wants to include the tool in her hydrology data products

### Use case 3b: hurt
1. Lila C. (AMY 3)
    - wants to corrupt the model to output incorrect moisture levels
2. Griffin (LILA 7)
    - wants to be able to make our model less accurate
3. Jake (ADITY 1)
    - wants the system to have weak security and authentication to modify out data and model







