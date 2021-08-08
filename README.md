# Crime Rate Prediction with Machine Learning.

This repository contains code and all files for the crime rate prediction research project.

### File Descriptions

| File | Description |
| :- | :-: |
| data/ | Contains the train dataset |
| images/ | images used for illustration purposes in the README. |
| crime-pred.ipynb | Contains the code for the project |
| report.pdf | Project report/final writeup |
| report.zip | Latex source files for the report |

### Code Execution & Environment
* The project code is executed using the Kaggle notebooks environment. In order to execute this code locally, change the `DATA_PATH` within the notebook here;
```
DATA_PATH = '../input/crime-dataset/communities-crime-clean.csv'
# Load data
def load_data(filename: str):
..
..
..
```
to a new data path where the dataset is stored and ensure all dependecies are installed. For instance, if you clone this repository, and want to run the notebook locally your new data path would be 
`./data/communities-crime-clean.csv`


### Models
* Three models are trained for this task and evaluated on the accuracy score metric. Results are presented as below;
![image.png]('./images/results.png')

