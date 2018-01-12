The goal of this project is to use EDA, visualization, data cleaning, preprocesing, and linear models to predict home prices given the features of the home, and interpret your linear models to find out what features add value to a home! This project is a bit more open-ended than project 1. 

From the Kaggle competition website:

    Ask a home buyer to describe their dream house, and they probably won't begin with the height of the basement ceiling or the proximity to an east-west railroad. But this playground competition's dataset proves that much more influences price negotiations than the number of bedrooms or a white-picket fence.

    With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, this competition challenges you to predict the final price of each home.
    
The best performing model was Lasso regression (1st degree polynomial) with an alpha = 1000. We obtained a testing $R^2$ = 0.88

The most significant features for a home's value were
- GrLivArea(+)
- OverallQual(+) 
- GarageCars(+)
- Neighborhoods(+)
- SaleType_new(+)
- YearBuilt(+)
- BsmtFullBath(+)
- WoodDeckSF(+)
- MSSubClass_160(-)
- BldgType_Twnhse(-)

