# Sentiment-Analysis


Sentiment Read me

Requirements
Python 3.x
Pandas: pip install pandas
Transformers: pip install transformers
Tkinter: typically included with Python’s standard library
Scipy: pip install scipy
Instructions
Setup Your Environment:
Ensure Python is installed on your machine and the necessary libraries are installed via pip.

Prepare Your Data:
Your input should be a CSV file where text data for analysis is present in a column named 'Review'.

Run the Script:
Execute the script by running python sentimentAnalysis.py from your command line.

Select Input and Output Files:

The script will open a file dialog box asking you to select your input CSV file.
After processing, it will ask where to save the output CSV file. This output file will include original data along with three new columns: 'Negative', 'Neutral', and 'Positive', representing the sentiment scores.
Review the Results:
Open the output CSV file with any spreadsheet software to view the sentiment analysis results.

Notes:
The script uses a model specifically trained for sentiment analysis on Twitter data. If your data significantly differs from Twitter text, the accuracy might be lower.
The script includes a preprocessing function that replaces usernames and URLs in the text, which helps in normalizing the data for better analysis results.
