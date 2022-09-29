# Forest-Cover-Classification

![forest covers photo](https://github.com/jaimeggb/Forest-Cover-Classification/blob/main/other_resources/forest%20cover.png)

## Description: 
In this project, I use deep learning to predict forest cover type (the most common kind of tree cover) based only on cartographic variables. The actual forest cover type for a given 30 x 30 meter cell was determined from US Forest Service (USFS) Region 2 Resource Information System data. The covertypes are the following:

1. Spruce/Fir
2. Lodgepole Pine
3. Ponderosa Pine
4. Cottonwood/Willow
5. Aspen
6. Douglas-fir
7. Krummholz

Independent variables are derived from data obtained from the US Geological Survey and USFS. The data original data is raw and has not been scaled or preprocessed. It contains binary columns of data for qualitative independent variables such as wilderness areas and soil type.

This study area includes four wilderness areas located in the Roosevelt National Forest of northern Colorado. These areas represent forests with minimal human-caused disturbances, so existing forest cover types are mainly a result of ecological processes rather than forest management practices.

Project Objectives:
- Develop a classifiers for this multi-class classification problem.
- Use TensorFlow with Keras to build my classifier
- Use my knowledge of hyperparameter tuning to improve the performance of my model
- Test and analyze performance
- Create clean and modular code

What I learned from the projects:
- How to build a multi-class classifier
- How to analyse performance of a model and improve it through manual hyperparameter tuning
- How to use Github for version control

## How to use: 
1. Fork the repository. 
2. Open the 'CoverType-classification.ipynb' notebook file
3. Run the file. 
4. Use model.predict(your_data) to predict forest cover type for your unclassified data
5. Use the suggestions given to improve the model and get even better predictions (current metrics are: precision: recall: accuracy: )

## Technologies: 
- python: main language
- jupyter notebooks: main computing platform
- pandas and numpy: for exploratory data analysis (EDA)
- tensorflow: main machine learning library to create data pipeline and model
- scikit-learn: secondary machine learning library used to create performance metrics at the end
- seaborn and matplotlib: for plotting graphs

## Collaborators: 
None

## License: 
None
