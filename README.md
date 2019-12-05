# Sentiment_Analysis
This project is done as part of my Master's course work

All the project code files are in code folder
Step 1:
Run preprocess.py using command line as /Dataset/tweets.csv 
output file is /Dataset/tweets-processed.csv
Step 2:
Set the test_file = "False"
and run the preprocess.py using command line arguement as /Dataset/tweets-test.csv
output file is /Dataset/test-processed.csv

Step 3:
to know the stats of the tweets run the stats.py using command line argument as /Dataset/tweets-processed.csv
output files are .pkl unigrams and bigrams bytestreams.
ranks will also be assigned to unigrams and bigrams to form sparse and dense vectors.

Step 4:
Usig the plots.py and .pkl files in Dataset folder generated during Step 3 see the top 20 unigrams and bigrams

Step 5:
Run the Naivebayes.py using .pkls and tweets-processed.csv and test-processed.csv for newly labeling to change the number of batches set
the batch number.
