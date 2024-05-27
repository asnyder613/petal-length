# Petal Length
A project illustrating my ability to import a dataset and predict the type of flower based on the length and width.

### Assigned Tasks:
1. Set up a shareable repo to structure your project
2. Load iris.csv training set into a database of your choice
3. Insure your load process addresses invalid or missing data
4. Generate summary statistics (e.g., min, max, avg, uniques, etc.) for each attribute received
5. Build a model that will predict the type of flower based on the length and width
6. Assess the performance of the model using typical data science techniques.  Explain why you chose the algorithm that you did.

### Process
I started by creating this git repo to contain the project materials. I uploaded the provided .csv file to the repo and created a Python jupityr notebook, where I completed exploratory data analysis in order to see any invalid/missing values, as well as to generate summary statistics. There were two observations where the data appeared to be invalid, which I dropped from the dataframe. The data that remained was evenly split between the three species of flower. 

### Model Selection
I tested four different classification models, all of which performed extremely well (leading to concerns regarding the size of the dataset and potential overfitting), but chose to recommend the logistic regression model due to its simplicity and interpretability. 
