Required packages:
    -----------------------
    packages      version
    -----------------------
    pandas         1.4.2
    numpy          1.22.4
    seaborn        0.11.2
    matplotlib     3.5.2
    sklearn        1.1.1
    re             2.2.1
    gensim         4.2.0
    bs4            0.0.1
    catboost       1.0.6
    -----------------------
    
Python version: 3.10.3


Running files:
  - There are a total of 3 python files: Foodcom Web Scraping.ipynb, Data Cleaning.ipynb, Modelling.ipynb
  - 4 datasets are used for this project: all_recipes.csv, out-of-sample.csv, cleaned_data.csv, test_data.csv
  - Depending on individual need, the file direcotry may be changed when reading data and saving output.
    1. Foodcom Web Scraping.ipynb includes crawling recipes from https://www.food.com and returning a csv file, 'all_recipes.csv', which contains the 
       raw data for NLP model training.
    2. Data Cleaning.ipynb contains data exploratory, data cleaning and vectorization on 'all_recipes.csv', The clean data is saved as 'cleaned_data.csv'.
       The same data cleaning process is performed on 'out-of-sample.csv' which is an off-the-shelf data downloaded from 
       https://www.kaggle.com/datasets/sarthak71/food-recipes. This kaggle dataset is used for out-sample testing purposes. The clean kaggle dataset 
       is saved as 'test_data.csv'.
    3. Modelling.ipynb involves model training and testing and using both in-sample data (Food.com), 'cleaned_data.csv', and out-sample data(Kaggle),
      'test_data.csv'. Consine similarity meausres between cuisines is performed based on prediction results.
       
