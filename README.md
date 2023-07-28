Alphabet Soup, a nonprofit foundation, required a tool to aid in selecting funding applicants with the highest likelihood of success in their endeavors. Leveraging your expertise in machine learning and neural networks, my objective was to utilize the features provided in the dataset to build a binary classifier. This classifier is capable of predicting whether applicants will be successful if funded by Alphabet Soup.
The dataset includes information on over 34,000 organizations that have received funding from Alphabet Soup in the past. Various columns in the dataset capture metadata about each organization.

Steps accomplished:
Preprocessed the Data:
- Created a DataFrame containing the charity_data.csv data and identified the target and feature variables in the dataset.
- Dropped the EIN and NAME columns from the DataFrame.
- Determined the number of unique values in each column.
- For columns with more than 10 unique values, determined the number of data points for each unique value.
- Created a new category called "Other" to contain rare categorical variables.
- Created feature array (X) and target array (y) using the preprocessed data.
- Split the preprocessed data into training and testing datasets.
- Scaled the data using a StandardScaler fitted to the training data.

Compiled, Trained, and Evaluated the Model:
- Created a neural network model with a defined number of input features and nodes for each layer.
- Designed hidden layers and an output layer with appropriate activation functions.
- Checked the structure of the model.
- Compiled and trained the model using the training data.
- Evaluated the model's performance using the test data to determine the loss and accuracy.
- Exported the results to an HDF5 file named AlphabetSoupCharity.h5.

Optimized the Model:
- Repeated the preprocessing steps in a new Jupyter notebook.
- Created a new neural network model, implementing at least 3 model optimization methods.
- Saved and exported the results to an HDF5 file named AlphabetSoupCharity_Optimization.h5.

Wrote a Report on the Neural Network Model:
- Wrote an analysis with a title and multiple sections, labeled with headers and subheaders.
- Formatted images in the report for correct display.
- Explained the purpose of the analysis.
- Answered all 6 questions in the results section.
- Summarized the overall results of the model.
- Described how a different model could be used to solve the same problem and explained the reasons for choosing that model.
