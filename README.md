> [!NOTE]
> Solution for days [1](https://github.com/atlas-github/nih_time_series_nlp/blob/main/nih_time_series_nlp_day1.ipynb), [2](https://github.com/atlas-github/nih_time_series_nlp/blob/main/nih_time_series_nlp_day2.ipynb), and [3](https://github.com/atlas-github/nih_time_series_nlp/blob/main/nih_time_series_nlp_day3.ipynb) will be posted here. Code-CV is [here](https://docs.google.com/document/d/1HFhnGH9d2zWqIK2C2l1nDAw-PNwm05Z-dFQRSw1LsEQ/edit?usp=sharing). 

> [!TIP]
> Wide pivot table can be found [here](https://github.com/atlas-github/nih_time_series_nlp/blob/main/wide_pivot_table.ipynb).

> [!TIP]
> Concatenating two dataframes code can be found [here](https://github.com/atlas-github/nih_time_series_nlp/blob/main/concat_example.ipynb).

<details open>
<summary> Day 1 </summary>

### 08:45 am: Introduction
[Here's](https://docs.google.com/presentation/d/e/2PACX-1vRbfvQpTP4ARbARRWhOL6WZ6koCKSHvf5OxFyHcJjn8GHXG3OpuneEH6uMYlpxKX0H_sEfHB6KAKrkq/pub?start=true&loop=false&slide=id.g29007063b8d_0_118) what I achieved so far.

### 09:00 am: Introduction to Python
  1. Using either your new Google account or your personal account, open [Google Colab](https://colab.research.google.com/) in another tab
  2. Google Colab's interface and functions:
     - Tools >> Settings >> 
       - Editor >> Show line numbers (check if you prefer)
       - Miscellaneous >> Corgi mode, Kitty mode (turn on if you like)
     - Test with some basic code:
       - Click Connect at top right
       - Write simple definition	
       - Test simple math problem
     - Runtime settings
       - Run cells
       - Reset
     - Code and text cells
     - Save
  3. More about Colab’s Markdown here
  4. Open a new notebook on [Google Colab](https://colab.research.google.com/)
  5. Data Visualization:
     - [matplotlib](https://matplotlib.org/)
     - [plotly](https://plotly.com/python/)
  6. Machine Learning and AI
     - [scikit-learn](https://scikit-learn.org/stable/)
     - [tensorflow](https://www.tensorflow.org/learn)
     - [pytorch](https://pytorch.org/)
  7. Scientific Computing
     - [scipy](https://scipy.org/)
     - [sympy](https://www.sympy.org/en/index.html)
  8. Automation and Web Scraping
     - [BeautifulSoup](https://beautiful-soup-4.readthedocs.io/en/latest/)
     - [Scrapy](https://scrapy.org/)
  9. Database Access
     - [sqlalchemy](https://www.sqlalchemy.org/)
     - [psycopg2](https://www.psycopg.org/docs/)
  10. Natural Language Processing (NLP)
      - [nltk](https://www.nltk.org/)
      - [SpaCy](https://spacy.io/)
  11. Image Processing
      - [pillow](https://realpython.com/image-processing-with-the-python-pillow-library/)
      - [opencv](https://opencv.org/)
  12. Data Analysis and Manipulation
      - [pandas](https://pandas.pydata.org/)
      - [numpy](https://numpy.org/)

### 09:45 am: Practical session 1
  1. [pandas](https://pandas.pydata.org/)
     - Series
       - Series Creation: Create a Pandas Series from a list of integers.
       - Indexing and Slicing: Access specific elements and slices from the Series.
       - Operations: Perform basic arithmetic operations on the Series.
       - Filtering: Filter the Series to include only elements greater than a certain value.
       - Missing Data: Introduce NaN values into the Series and handle them (e.g., fill with a value or drop).
     - DataFrame
       - DataFrame Creation: Create a DataFrame from a dictionary where the keys are column names and the values are lists of column data.
       - Exploring Data: Display the first few rows, summary statistics, and data types of the DataFrame.
       - Indexing and Selection: Select specific columns, rows, and subsets of the DataFrame.
       - Adding Columns: Add a new column to the DataFrame based on existing columns.
       - Handling Missing Data: Introduce NaN values and demonstrate methods to handle missing data (e.g., fillna, dropna).
     - Data Manipulation
       - Reading Data: Read a CSV file into a Pandas DataFrame.
       - Filtering Data: Filter rows based on a condition.
       - Sorting Data: Sort the DataFrame by a specific column.
       - Grouping Data: Group the DataFrame by a column and compute aggregate statistics.
       - Merging DataFrames: Merge two DataFrames on a common column.
  3. [numpy](https://numpy.org/)
     - Basic operations
       - Array Creation: Create a 1D NumPy array of integers from 0 to 9.
       - Reshape: Convert the 1D array into a 2D array with 2 rows and 5 columns.
       - Slicing: Extract the first row and the second column of the 2D array.
       - Arithmetic Operations: Create another 2D array of the same shape and perform element-wise addition, subtraction, multiplication, and division.
       - Statistical Operations: Compute the mean, median, and standard deviation of the elements in the 2D array.


___

### 10:45 am: Break
___

### 11:00 am: Introduction to time series data
  1. Understanding time series data
  2. Common time series patterns and terminology
  3. Loading and exploring time series data with Python

### 12:00 pm: Basic data cleaning techniques
  1. Handling missing values, imputation and interpolation
  2. Removing duplicates
  3. Data type conversion and validation

___

### 1:00 pm: Lunch
___

### 2:00 pm: Practical session 2
  1. Download the dengue csv file
  2. Filter to only relevant columns
  3. Convert date to datetime format
  4. Identify postcodes with most complete/missing data
  5. Create a pivot table
  6. Visualize case counts data

### 3:00 pm: Advanced data cleaning techniques
  1. Detecting and handling outliers
  2. Smoothing time series data
  3. Handling seasonal and trend components

### 4:00 pm: Practical session 3
  1. Apply moving average smoothing and visualize
  2. Use a for loop to run the code for a few postcodes

</details>


<details open>
<summary> Day 2 </summary>

### 09:00 am: Feature engineering for time series data
  1. Creating lag features
  2. Rolling statistics (moving average)
  3. Fourier transform and other feature extraction

### 09:45 am: Time series data normalization and scaling
  1. Normalization technique
  2. Standardization technique
  3. Effects of scaling on time series analysis

___

### 10:45 am: Break
___

### 11:00 am: Practical session 4
  1. Cretae a plot showing the number of cases for a selected location, with a lag
  2. Overlay external weather data

### 12:00 pm: Time series decomposition
  1. Decomposing time series into trend, seasonality, and residuals
  2. Additive vs. multiplicative decomposition

___

### 1:00 pm: Lunch
___

### 2:00 pm: Practical session 5
  1. Machine learning [cheat sheet](https://machinelearningmastery.com/time-series-forecasting-methods-in-python-cheat-sheet/)
  2. Facebook [Prophet](https://facebook.github.io/prophet/)

### 4:00 pm: Resampling and time series frequency conversion
  1. Downsampling
  2. Upsampling
  3. Resampling with aggregation
  4. Frequency conversion

</details>

<details open>
<summary> Day 3 </summary>

### 09:00 am: Practical session 6
  1. Split data into training and testing sets
  2. Time series cross-validation techniques

### 09:45 am: Introduction to NLP data preprocessing
  1. Tokenization
  2. Stopword removal
  3. Stemming
  4. Lemmatization
  5. Text normalization 

___

### 10:45 am: Break
___

### 11:00 am: Text cleaning techniques
  1. Removing special characters and numbers
  2. Handling case sensitivity
  3. Removing stopwords and punctuation

### 12:00 pm: Practical session 7
  1. Geocoding using Google Cloud Platform
  2. Compare Google Cloud Platform's address details with original dataset

___

### 1:00 pm: Lunch
___

### 2:00 pm: Text normalization techniques
  1. Converting text to lowercase
  2. Expanding contractions
  3. Handling special characters and numbers
  4. Normalizing workspace
  5. Removing non-ASCII characters
  6. Remalizing tect using lemmatization  


### 3:00 pm: Feature extraction for NLP
  1. Bag of Words
  2. Term Frequency-Inverse Document Frequency (TF-IDF)
  3. Word Embeddings (Word2Vec)
  4. Document Embeddings (Doc2Vec)
  5. N-grams


### 4:00 pm: Practical session 8
  1. Geocode with OpenStreetMap
  2. Geocode places with missing postcodes

</details>
