# ml-svm-spam-classifier
This is a jupyter notebook application that fits a Support Vector Machine model to a dataset of 5172 randomly picked emails labeled spam or not-spam.

---

## Setup and Usage

- Clone this repo to your desktop.
- Create a new anaconda environment with all the requirements using the following command:

      conda env create -f environment.yml

- Activate the environment using (windows)

      activate spam-classifier-env

  or if you are on a linux machine

      source activate spam-classifier-env

- Run `jupyter notebook` from the root directory to open up the notebook in your browser.

## Things to note

The dataset for this code is provided as a zip file in the 'data' folder. The 'model.ipynb' file includes the code to extract that dataset as a csv file automatically.

## About the dataset

> The csv file contains 5172 rows, each row for each email. There are 3002 columns. The first column indicates Email name. The name has been set with numbers and not recipients' name to protect privacy. The last column has the labels for prediction : 1 for spam, 0 for not spam. The remaining 3000 columns are the 3000 most common words in all the emails, after excluding the non-alphabetical characters/words. For each row, the count of each word(column) in that email(row) is stored in the respective cells. Thus, information regarding all 5172 emails are stored in a compact dataframe rather than as separate text files.
[Source](https://www.kaggle.com/balaka18/email-spam-classification-dataset-csv)
