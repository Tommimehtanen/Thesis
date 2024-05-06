# Overview of the program
<img width="446" alt="image" src="https://github.com/Tommimehtanen/Thesis/assets/93819335/4b0fc11a-f7dc-4b3e-9b3b-6cad97409b6a">





# Instructions

1.	Make sure you have Python 3 installed on your computer.

2.	You should also have an environment to be able to run jupyter notebooks.

3.	Go to Github (https://github.com/Tommimehtanen/Thesis) and clone the repository.

4.	Download the following libraries:
# Basic libraries for data manipulation and analysis
!pip install pandas

# Libraries for data visualization
!pip install matplotlib
!pip install seaborn
!pip install wordcloud

# Libraries for time-related operations and regular expressions
!pip install python-dateutil

# Libraries for deep learning and transformers
!pip install torch
!pip install transformers

# Libraries for web scraping and related utilities
!pip install requests
!pip install beautifulsoup4
!pip install selenium
!pip install spacy
!pip install advertools

# Libraries for machine learning and evaluation
!pip install scikit-learn  # Includes train_test_split, Random Forest, and metrics


# Different options for user of the program

5.	Using the artifact there are two options. The first option is that the user runs the whole process from the beginning till the end including the time-consuming parts. The second option is that the user only executes the “Exploratory data analysis.ipynb” code and only focuses on the analysis part.


Option one: After cloning the repository and making sure that the environment is setup correctly and able to run jupyter notebooks and the libraries above are also installed it is time to run the first part of the process. First “Data scraper Inderes.ipynb” file should be run to collect the data from the Inderes website. Check step 7 for enabling data collect-ing with selenium library.

After running that code, which might take some time it is time to run “Preprocessing fo-rum data.ipynb”. After that run “Yahoo Finance data collector.ipynb” file to collect data from Yahoo finance. Finally, after all the data collecting and preprocessing you can run the “Exploratory data analysis.ipynb” file to do some data analytics. Feel free to make your own modifications on that file based on your needs and wants.

Option two: If you are interested in only the data analysis part you should choose this option because it saves time. After cloning the repository, you can run the “Exploratory data analysis.ipynb2” file and do your own modifications into that file based on your needs and wants.

7.	To be able to run the “Data Scraper Inderes.ipynb” code you need to have Google Chrome browser installed which can be installed from here: https://www.google.com/chrome/ . You also need chrome driver installed which can be installed from here: https://chromedriver.chromium.org/downloads. Your Google chrome browser version and the chrome driver version need to be compatible.

