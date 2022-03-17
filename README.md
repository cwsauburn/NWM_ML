This project contains the following underlying data : 


    •0-30 day Lead data folder : It contains 0 to 30 day lead Streamflow forecast data grouped individually. These files are stored in CSV format and read as input to train the ML models.

    •Graphs Folder : It contains the script for the final graphs and the raw data which is used to generate these graphs.

    •ML_Models Folder** : It contains trained machine learning models for 0 to 30 forecast day lead data.

    •Data_setup_scripts : It contains the scripts which were used to set up the input data to train the ML model for 0 to 30 days lead streamflow data.

    •train&predict_scripts : This folder contains Different Machine Learning scripts which were used to train the model and predict the streamflow of ungauged sites for all the 30 day lead data.

NOTE: Due to large size of the Input data, it can be obtained on request by contacting the authors of the paper. Primary contact: szk0139@auburn.edu.

To run the scenario use the NWM_ML/train&predict_scripts/final_neural_script_10day.ipynb and the raw data at NWM_ML/out_lead_10day_data.csv. 
