# building-permit-predictions
For this project, we were tasked in building a model that would estimate how long permit finalizations would take for Chicago buildings based on characteristics in the dataset. 

Out of 119 columns including: ID, Permit #, Permit Type, Review Type, Application Start Date, Issue Date, Processing Time, Street Number/Direction/Name, Work Description, Building Fees, Waived Fees, Zoning Fees, Contact information, Pins, Community Area, Ward, Census Tract, Coordinates, Latitude, Longitude to name a few, six variables of interest were chosen.

These six variables were **Permit Type, Review Type, Application Start Date, Processing Time (Y), Total Fee, Subtotal Waived.**  

The overall process is shown and explained through the code in this repository. Findings and analysis is found in the "Building Permit Predictions" file of this repository.

It should be known that improvements could be made for the future. For example, for data cleaning removing records with missing values may bias or "hurt" the model. This is because some permits may naturally not have some data information, and the model will not be able to predict on them- which is undesirable. Additionally, one of the challenges that I faced with this project was with computing/memory issues. Due to this, the number of methods I could have chosen were limited. In the future, I would try building different models (for e.g. RandomForest or Lasso model) and only use a 10-20% sample of the training dataset. This, in turn, would provide a glimpse into determining whether these methods provide better predictions. In the future, I would try subsampling the model.
