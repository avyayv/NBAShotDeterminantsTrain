# ShotDeterminantsTrain

If you would like to see how the data is processed please visit the https://github.com/avyayv/ShotDeterminantsData.

You can simply run the `Model.ipynb` notebook, which will handle the training of the XGBoost model directly from the output of the DataProcessing notebook. The output of the DataProcessing notebook is a part of the repository already, so it is unnescassary to run it again, unless you would simply like to reproduce the results.

## File Contents
1. `trainXAll.csv`
  Extracted information for every shot from PBP and Tracking Data (including defender distance, shot distance, player id, and defender id. 
2. `trainYAll.csv`
  For the trainX, was the shot made or missed
3. `bio_data.csv`
  Includes height data for the 2015-16 season, which is an input into the model (defender height - shooter height is the input)
4. `summary_data.csv`
  Includes 3PT% for the players in the 2015-16 season.
  
All of the above files are generated using this repository https://github.com/avyayv/ShotDeterminantsData

5. `Model.ipynb`
  The actual model + interpretation of the model.

