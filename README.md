# Data_Wrangling
Details all the stages of data wrangling
The data wrangling process consists of the gather,assess and clean stage. In this project i am gathering data from three sources:

Downloadable "twitter_archive_enhaced.csv" file provided by Udacity for manual download.
Url provided by Udacity for programmatic download of the "image-predictions.tsv" file.
Querying twitter api for tweet infomations not available in the "twitter_archive_enhaced.csv" file.For example favorite count of a tweet and saving it into a "tweet_json.txt" file
My wrangling process for this project started by manually downloading the "twitter_archive_enhaced.csv" file provided by Udacity, and then using code on the jupyter notebook to download the "image-predictions.tsv" file programmatically and finaly applying to twitter for a developer account which was used to query the extra data i needed and stored in "tweet_json.txt" file.

After gathering all my data needed for the project i read all three files into df_twits_en,df_predictions and df_tweets tables respectively. I then proceeded to the next stage of assessing the data for both quality issues and tidiness issues of which i discovered 11 quality issues and 4 tidiness issues clearly detailed in the wrangle_act file.I did visual assessments using the dataframe in the jupyter notebook and also in an excel spreadsheet.It was in the excel sheet i discovered incorrect dog names and rating_numerator vales amongst other errors. The programmatic assessement on the other hand made me discover incorrect and inconsistent datatypes in the timestamp and tweet_id columns respectively. Finaly at the cleaning stage i first copied all three dataframes and then proceeded to apply the relevant changes documented in the assessment stage.
