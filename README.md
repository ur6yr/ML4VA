# ML4VA
We aimed to predict the economic value loss due to rising sea and waterway levels in Virginia Beach. We used standard machine learning methods for a Virginia Beach property value data set, including data cleaning through a pipeline which standardized the data and quantified its categorical elements. For another data set detailing sea level rise, we used custom transformations to geocode the data and convert it into formats that work well with standard machine learning algorithms. For both data sets, we plotted the relevant features and coordinates using shape files and geodataframes in geopandas. We have used various regression models including Linear Regression and Random Forest Regression. The Linear Regression model has provided very accurate answers with low RMSE so we moved forward with incorporating the predictions from that into a land value loss function. Through this project, we are able to gain valuable insights about the potential economic effects of sea level rise in Virginia Beach.
