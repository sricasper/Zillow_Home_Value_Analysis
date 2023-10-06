# zillow_home_value_analysis
Analyzing and predicting the value of properties by using KNN Imputer, machine learning, and regression models

## Dataset
'prop_2016.csv' and 'prop_2017.csv' are the original datasets from Zillow, an American real-estate marketplace company. Zillow uses 'Zestimate' to give consumers as much information as possible about homes and the housing market, marking the first time consumers had access to this type of home value information at no cost.
“Zestimates” are estimated home values based on 7.5 million statistical and machine learning models that analyze hundreds of data points on each property. In this notebook, some machine learning techniques will be uesd to estimate the assessed values of the properties.

## Data Dictionary
parcelid: Unique identifier for parcels (lots)

bathroomcnt: Number of bathrooms in home including fractional bathrooms

bedroomcnt: Number of bedrooms in home

buildingqualitytypeid: Overall assessment of condition of the building from best (lowest) to worst (highest)

calculatedfinishedsquarefeet: Calculated total finished living area of the home

finishedsquarefeet12: Finished living area

fullbathcnt: Number of full bathrooms (sink, shower + bathtub, and toilet) present in home

latitude: Latitude of the middle of the parcel multiplied by 10e6

longitude: Longitude of the middle of the parcel multiplied by 10e6

lotsizesquarefeet: Area of the lot in square feet

propertylandusetypeid: Type of land use the property is zoned for

regionidcity: City in which the property is located (if any)

regionidcounty: County in which the property is located

regionidzip: Zip code in which the property is located

roomcnt: Total number of rooms in the principal residence

unitcnt: Number of units the structure is built into (i.e. 2 = duplex, 3 = triplex, etc...)

yearbuilt: The Year the principal residence was built

structuretaxvaluedollarcnt: The assessed value of the built structure on the parcel

taxvaluedollarcnt: The total tax assessed value of the parcel

assessmentyear: The year of the property tax assessment

landtaxvaluedollarcnt: The assessed value of the land area of the parcel

taxamount: The total property tax assessed for that assessment year

ageinyear: The Year the principal residence was built to the inspection year

assessedvalue: The sum of the assessed value of the built structure on the parcel and the assessed value of the land area of the parcel

## Field of Interest
Explore the relationships within the datasets and compare the accuracy score of each model
