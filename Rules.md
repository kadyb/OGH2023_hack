# Hackathon rules

1. You can submit the results individually or in pairs
2. You must be registered on [Kaggle](https://www.kaggle.com/)
3. Finally, you must send the results as a `.csv` file and a reproducible notebook
4. *Notebooks will be available to the public after the hackathon (??????)*
5. Maximum of three submissions per day are allowed
6. Three notebooks with the highest validation metric are subject to final evaluation. The best work is selected by the jury

## Notes

1. Set the randomness seed in the script
2. Make sure your model returns all land cover categories
3. Make sure you use the same coordinate reference systems:
    * Polish National Geodetic Coordinate System 1992 (`EPSG:2180`)
    * Universal Transverse Mercator Coordinate System Zone 34N (`EPSG:32634`)
4. State of the art classification algorithms (generally pixel-based):
    * random forest
    * gradient boosting
    * support vector machine
5. Do not waste time on tuning the model that improves the score by 0.00001; focus more on feature engineering
