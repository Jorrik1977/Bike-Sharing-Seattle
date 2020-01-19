# Pronto Bike-Sharing-Seattle

This project is an data analysis and prediction (based mostly on weather data) about the cycling behaviour of users of a bike-sharing system with docking stations in Seattle, USA. The users were either members with an annual subscription or day pass user. 54 Stations provide 500 bikes to all borrower. The dataset includes 236.000 single bike trips between 10/2014 and 09/2016.

**Cleaning Notebooks**
The first three notebooks plus the merging notebook are about cleaning/merging each dataset for EDA and prediction purposes. Finally i merged two datasets: one for the EDA in which all trips are included and one for the predictive modeling where i aggregated all trips for each day because i only had weather data for any whole day - not for each hour that day.

**EDA Notebook**
Than there is the final EDA notebook. Here you will find the detailed analysis of the user behaviour. The locations each user-group uses the most, at what times (hour, day, month) they are the most active, 

**Predictive Modeling Notebooks**
Following are the notebooks with predicitive models, one model each. The XGBoost Regressor had the best results of all. I even tried one classification model for fun, which can predict if a given ride was done by a member or a daypass user. So if we wouldnt have that information in the beginning we could have predicted that with 75% accuracy.

**Business Slides**
Finally the business slides for the presentation. Here you can find a demo slide for quick show-off, the final slide for the business presentation and a much longer slide which includes information about why pronto vanished in the end and what competitors are responsible for that.
