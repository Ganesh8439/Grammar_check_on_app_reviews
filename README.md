# Grammar_check_on_app_reviews
# Summary
To perform grammar check on the reviews from the given dataset using any pre-trained model or text from open datasets
# Methods
## Pre-processing
* Since we are doing grammar check on the reviews other columns are not required and hence dropped
* Checking for null values and dropping them
* Removing non english words using **nltk** library because these words can generate wrong results when checking for grammar
* Removing any empty rows after taking only english words
## Grammar check
* Calculating the number of grammatical errors in each sentence using **Language tool python** library
* Using this error to calculate accuracy(%) of a particular text
## Result
![Screenshot](/grammar_check_result.png)
