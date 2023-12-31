# Supervised Learning
# Project: Finding Donors for CharityML
CharityML in Silicon Valley wants to send donation letters to potential donors in California. They need an algorithm to identify likely donors among 15 million residents while reducing costs. Evaluate and optimize supervised learners to find the best model.

# Install
This project requires Python 3.x and the following Python libraries installed:
NumPy
Pandas
matplotlib
scikit-learn
You will also need to have software installed to run and execute an iPython Notebook
We recommend students install Anaconda, a pre-packaged Python distribution that contains all of the necessary libraries and software for this project.

# Code
Template code is provided in the finding_donors.ipynb notebook file. You will also be required to use the included visuals.py Python file and the census.csv dataset file to complete your work. While some code has already been implemented to get you started, you will need to implement additional functionality when requested to successfully complete the project. Note that the code included in visuals.py is meant to be used out-of-the-box and not intended for students to manipulate. If you are interested in how the visualizations are created in the notebook, please feel free to explore this Python file.

# Run
In a terminal or command window, navigate to the top-level project directory finding_donors/ (that contains this README) and run one of the following commands:
ipython notebook finding_donors.ipynb
or
jupyter notebook finding_donors.ipynb
This will open the iPython Notebook software and project file in your browser.

# Data
The modified census dataset consists of approximately 32,000 data points, with each datapoint having 13 features. This dataset is a modified version of the dataset published in the paper "Scaling Up the Accuracy of Naive-Bayes Classifiers: a Decision-Tree Hybrid", by Ron Kohavi. You may find this paper online, with the original dataset hosted on UCI.

# Features
age: Age
_____________
workclass: Working Class (Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked)
_____________
education_level: Level of Education (Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool)
_____________
education-num: Number of educational years completed
_____________
marital-status: Marital status (Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, Married-AF-spouse)
_____________
occupation: Work Occupation (Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-fishing, Transport-moving, Priv-house-serv, Protective-serv, Armed-Forces)
_____________
relationship: Relationship Status (Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried)
_____________
race: Race (White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black)
_____________
sex: Sex (Female, Male)
_____________
capital-gain: Monetary Capital Gains
_____________
capital-loss: Monetary Capital Losses
_____________
hours-per-week: Average Hours Per Week Worked
_____________
native-country: Native Country (United-States, Cambodia, England, Puerto-Rico, Canada, Germany, Outlying-US(Guam-USVI-etc), India, Japan, Greece, South, China, Cuba, Iran, Honduras, Philippines, Italy, Poland, Jamaica, Vietnam, Mexico, Portugal, Ireland, France, Dominican-Republic, Laos, Ecuador, Taiwan, Haiti, Columbia, Hungary, Guatemala, Nicaragua, Scotland, Thailand, Yugoslavia, El-Salvador, Trinadad&Tobago, Peru, Hong, Holand-Netherlands)
_________________________
--Target Variable--
income: Income Class (<=50K, >50K)
