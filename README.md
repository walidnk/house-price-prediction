# 🏚️ House price predition - 

In this Notebook we will use a dataset provided by Kaggle, to predict the prices of the houses according with the features of each one in the dataset.

Kaggle [link.](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data)

### Dataset Description

#### File descriptions

* **train.csv** - the training set.
* **data_description.txt** - full description of each column, originally prepared by Dean De Cock but lightly edited to match the column names used here.

#### Data fields

Here's a brief version of what you'll find in the data description file.

* **SalePrice**: The property's sale price in dollars. This is the target variable that you're trying to predict.
* **MSSubClass**: The building class.
* **MSZoning**: The general zoning classification.
* **LotFrontage**: Linear feet of street connected to property.
* **LotArea**: Lot size in square feet.
* **Street**: Type of road access.
* **Alley**: Type of alley access.
* **LotShape**: General shape of property.
* **LandContour**: Flatness of the property.
* **Utilities**: Type of utilities available.
* **LotConfig**: Lot configuration.
* **LandSlope**: Slope of property.
* **Neighborhood**: Physical locations within Ames city limits.
* **Condition1**: Proximity to the main road or railroad.
* **Condition2**: Proximity to the main road or railroad (if a second is present).
* **BldgType**: Type of dwelling.
* **HouseStyle**: Style of dwelling.
* **OverallQual**: Overall material and finish quality.
* **OverallCond**: Overall condition rating.
* **YearBuilt**: Original construction date.
* **YearRemodAdd**: Remodel date.
* **RoofStyle**: Type of roof.
* **RoofMatl**: Roof material.
* **Exterior1st**: Exterior covering on the house.
* **Exterior2nd**: Exterior covering on the house (if more than one material).
* **MasVnrType**: Masonry veneer type.
* **MasVnrArea**: Masonry veneer area in square feet.
* **ExterQual**: Exterior material quality.
* **ExterCond**: Present condition of the material on the exterior.
* **Foundation**: Type of foundation.
* **BsmtQual**: Height of the basement.
* **BsmtCond**: General condition of the basement.
* **BsmtExposure**: Walkout or garden level basement walls.
* **BsmtFinType1**: Quality of the basement finished area.
* **BsmtFinSF1**: Type 1 finished square feet.
* **BsmtFinType2**: Quality of the second finished area (if present).
* **BsmtFinSF2**: Type 2 finished square feet.
* **BsmtUnfSF**: Unfinished square feet of basement area.
* **TotalBsmtSF**: Total square feet of basement area.
* **Heating**: Type of heating.
* **HeatingQC**: Heating quality and condition.
* **CentralAir**: Central air conditioning.
* **Electrical**: Electrical system.
* **1stFlrSF**: First Floor square feet.
* **2ndFlrSF**: Second floor square feet.
* **LowQualFinSF**: Low-quality finished square feet (all floors).
* **GrLivArea**: Above-grade (ground) living area square feet.
* **BsmtFullBath**: Basement full bathrooms.
* **BsmtHalfBath**: Basement half bathrooms.
* **FullBath**: Full bathrooms above grade.
* **HalfBath**: Half baths above grade.
* **Bedroom**: Number of bedrooms above the basement level.
* **Kitchen**: Number of kitchens.
* **KitchenQual**: Kitchen quality.
* **TotRmsAbvGrd**: Total rooms above grade (does not include bathrooms).
* **Functional**: Home functionality rating.
* **Fireplaces**: Number of fireplaces.
* **FireplaceQu**: Fireplace quality.
* **GarageType**: Garage location.
* **GarageYrBlt**: Year the garage was built.
* **GarageFinish**: Interior finish of the garage.
* **GarageCars**: Size of garage in car capacity.
* **GarageArea**: Size of garage in square feet.
* **GarageQual**: Garage quality.
* **GarageCond**: Garage condition.
* **PavedDrive**: Paved driveway.
* **WoodDeckSF**: Wood deck area in square feet.
* **OpenPorchSF**: Open porch area in square feet.
* **EnclosedPorch**: Enclosed porch area in square feet.
* **3SsnPorch**: Three-season porch area in square feet.
* **ScreenPorch**: Screen porch area in square feet.
* **PoolArea**: Pool area in square feet.
* **PoolQC**: Pool quality.
* **Fence**: Fence quality.
* **MiscFeature**: Miscellaneous feature not covered in other categories.
* **MiscVal**: $Value of miscellaneous features.
* **MoSold**: Month Sold.
* **YrSold**: Year Sold.
* **SaleType**: Type of sale.
* **SaleCondition**: Condition of sale.
