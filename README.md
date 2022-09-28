# Forest-Cover-Classification

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
Develop one or more classifiers for this multi-class classification problem.
Use TensorFlow with Keras to build my classifiers.
Use my knowledge of hyperparameter tuning to improve the performance of my models.
Test and analyze performance.
Create clean and modular code.
