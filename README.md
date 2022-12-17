# Child-Mortality-predictor-using-WHO-API

This is a MAchine LearningModel based on XGBRegressor. The model Try to predict the under five child mortality for the following year of a given country and a given year. The model takes the WHO indicator of under 5 child mortality as target and it is fitted with others  WHO indicators. 

For a requested country and year, the program uses the WHO API to obtaint the data of the fitted indicators and makes a prediction of under 5 mortality using the developed model. 

In the file [WHO_deaths_under_five_predictor](WHO_deaths_under_five_predictor.ipynb) you can find the code to use the model

Indicators: 

### Target: 

Under 5 deaths(CM_01)


### Fit:


*Maternal health interventions:*

    Antenatal care coverage - at least one visit (in the two or three years preceding the survey) (%) (anc1)
    Antenatal care coverage - at least four visits (in the two or three years preceding the survey) (%) (anc4)
    Births attended by skilled health personnel (in the two or three years preceding the survey) (%) (sba)

*Newborn and child health interventions:*

Preventive care:

    Early initiation of breastfeeding (%) (bfearly)
    Children aged 6-59 months who received vitamin A supplementation (%) (vita)

Childhood immunization:

    BCG immunization coverage among one-year-olds (%) (vbcg)
    Measles immunization coverage among one-year-olds (%) (vmsl)
    Polio immunization coverage among one-year-olds (%) (vpolio)
    DTP3 immunization coverage among one-year-olds (%) (vdpt)
    Full immunization coverage among one-year-olds (%) (vfull)
   
Care-seeking for sick children:

    Children aged < 5 years with diarrhoea receiving oral rehydration salts (%) (ors)
    Children aged < 5 years with diarrhoea receiving oral rehydration therapy and continued feeding (%) (ort)
    Children aged < 5 years with pneumonia symptoms taken to a health facility (%)



