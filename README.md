

- Predicting Wild Blueberry Yield using streamlit and deploying application on Heroku. 
- Link to Kaggle Notebook: https://www.kaggle.com/code/sadiaanzum/wild-blueberry-yield-prediction 
- Heroku App: https://blueberryyieldpredapp.herokuapp.com/



## About Dataset

The dataset used for predictive modelling was generated by the Wild Blueberry Pollination Simulation Model, which is an open-source, spatially-explicit computer simulation program, that enables exploration of how various factors, including plant spatial arrangement, outcrossing and self-pollination, bee species compositions and weather conditions, in isolation and combination, affect pollination efficiency and yield of the wild blueberry agro-ecosystem. 

The simulation model has been validated by the field observation and experimental data collected in Maine USA and Canadian Maritimes during the last 30 years and now is a useful tool for hypothesis testing and theory development for wild blueberry pollination researches. This simulated data provides researchers who have actual data collected from field observation and those who wants to experiment the potential of machine learning algorithms response to real data and computer simulation modelling generated data as input for crop yield prediction models.


## Problem Statement

The target feature is yield which is a continuous variable. The task is to classify this variable based on the other 17 features step-by-step by going through each day's task. The evaluation metrics will be RMSE score.


## Specifications

Subject:    Computer Science

Specific subject area:  
    Machine Learning, Predictive modelling, Modelling and Simulation

Type of data: Table

How data were acquired:     
    Generated from Simulation Modelling of Wild Blueberry Pollination by an open source GAMA simulation platform V1.7 (http://gama-platform.org) , using GAML modelling programming language   

Data format:    XLSX , Raw

Parameters for data collection:-
    The parameters (i.e., the factors of the simulation model) used to configure the simulation experiments are three-fold: 1) the average size of blueberry clones within a field; 2) foraging density of each bee taxon group; and 3) weather information such as temperature, precipitation and wind speed. 

Description of data collection:	
    A total of 77,700 simulations were conducted to achieve both an extensive and intensive sampling effort and this resulted in a dataset consisting of 777 records, each of which is an average of 100 simulation runs.

Data source location:-
	
    Institution: The University of Maine
    State/Region:  Maine
    Country: USA

Data accessibility:	The data is provided with the paper

Related research article:-
    
    Authors’ names: E.Y. Obsie, H. Qu, F. Drummond
    Title: Wild blueberry yield prediction using a combination of computer simulation and machine learning algorithms
    Journal: Computers and electronics in agriculture
    DOI: In Press
    E.Y. Obsie, H. Qu, F. Drummond, Wild blueberry yield prediction using a combination of computer simulation and machine learning algorithms, Comput. Electron. Agric. In Press.


Value of the Data:-
    
    •	The dataset provides useful information on wild blueberry plant spatial traits, bee species composition and weather conditions. Therefore, it enables researchers to build machine learning models for early prediction of blueberry yield. 
    •	This dataset can be essential for other researchers who have field observation data but wants to test and evaluate the performance of different machine learning algorithms by comparing use of real data against computer simulation generated data as input in crop yield prediction.  
    •	Researchers can use this dataset to benchmark wild blueberry crop yield prediction models comparing to results already known. 
    •	Educationalists at different level can use the dataset for training machine learning classification or regression problems.


## Acknowledgements

 We acknowledge funding by the National Natural Science Foundation of China (61871061) and Program of Basic Research and Frontier Technology of Chongqing Municipal Science Commission (cstc2017jcyjAX0453) to HQ.
 
