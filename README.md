# Functionality Prediction 

![Title-Slide](Images/tanzania.jpg)

#
### Project File Summary
   - <b>[README.md](README.md)</b> - summary of project.
   - <b>[Images](/Images)</b> - Images used.
   - <b>[Jupyter_Notebooks](/Jupyter_Notebooks)</b> - All Jupyter Notebooks for this project.
   - <b>[Project_Prompt](/Project_Prompt)</b> - Project guidelines.
   - <b>[Final_Presentation](/Final_Presentation)</b> - A non-technical presentation of the project.

#
### Project Members

   - <b>[Alphonso Woodbury](https://github.com/a-woodbury)</b>
   - <b>[Rashid Baset](https://github.com/rashidbaset)</b>

#
### Project Scenario

In Tanzania, only approximately 50% of the Tanzanian population have access to safe water. According to 2015 Tanzania Water Point Mapping data, about 29 percent of all water points are non-functional, out of which 20 percent failed within the first year. Using data from Taarifa and the Tanzanian Minisitry of Water, we were interested in predicting which pumps in Tanzania are functional and which pumps need repair. An understanding of which waterpoints will fail can improve maintence operations and ensure that portable, clean water is available to communities across Tanzania.

#
### Project Goals

1. Which waterpoint features ensure waterpoint success?
2. Who should fund and install waterpoints?
3. How well can we identify (predict) waterpoints that need repair?


#
### Methodology

- Perform data cleaning on datasets.
- Perform train, test split on cleaned data, standardization, and categorical encoding.
- Use training data to fit various models (Decision Tree, KNN, Logistic, Random Forest).
- Perform hypterparameter tuning on train data and finalize models using test data.

#
### Reccomendations

Waterpoint functionality are more dependent to some features/variables than others. When working on repair and maintence we reccomend focusing on 'Total Static Head', 'Permittance', 'Population', and 'Public Meetings', per our model and EDA. 

### Next Steps

- Improve our model recall score.
- Collect additional data on water quality and maitenence costs. 























