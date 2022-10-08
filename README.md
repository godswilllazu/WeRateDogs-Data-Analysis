# WeRateDogs-Data-Analysis


Process 1: Data Gathering

The following datasets were gathered:

    twitter-archive-enhanced.csv
    Image-predictions.tsv
    tweet_json.txt
    
Process 2: Assessing Data

I carried out both visual and programmatic assessments in order to look for both quality and tidiness issues. I documented eight(8) quality issues and three(3) tidiness issues.

For the programmatic assessment , I made use of pandas functions such as .info() , .sample() , .duplicated() , .query and .describe() as well as checking columns , dataset[‘column_name’].

Process 3: Cleaning Data

For this process, I made sure to solved every listed issue in the assessment stage and also merge the three datasets to one (1).

Only original ratings with images (also retweeted set to False) data were assessed and cleaned.

All columns were set to their correct data type and re-arranged, missing and incorrect values (e.g ratings) were filled in correctly although they are some missing values which I couldn’t clean with the data at hand.

I made sure to combine related data columns to one (e.g the dog_stages and breeds).

Process 4 : Storing Data

I stored the final master dataset as a csv file using pandas dataset.to_csv() setting index to False. I also stored it in a sql local database (.db) using the sqlite engine of sqlalchemy library.

Process 5 : Visualiization

Visualizations were done using matplotlib and Tableau (WeRateDogs Analysis.png file)
