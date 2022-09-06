

# Project: Wrangle and Visualize WeRateDogs Twitter dataset
> Three different sets of data all gotten from weratedogs account were used for this analysis. The first was the enhanced tweet archive which contained 2356 samples of data. The second is image prediction dataset that had 2075 samples. In this report, I will refer to them as archive dataset, tweet dataset and prediction dataset. 

After careful assessment using both visual and programmatic approach, data quality and tidiness issues are discovered within the datasets. Under quality issues, we have:

## Quality issues 
- Missing records (2327 instead of 2356) in tweet dataset
- Non original tweets and Unwanted columns 
- Wrong column data type 
- 9/11 event mistaken as rating (archive dataset)
- Non 10 rating denominator value ( archive)
- Incorrect value for dog stages (archive)
- Underscore used instead of space to seperate words (p1, p2 and p3 columns) (prediction)
- No uniform character case in p1, p2 and p3 values (prediction)
- Erroneous datatypes (p1_dog, p2_dog, p3_dog) (prediction)

## Tidines issues
Same column bearing different title in another table (timestamp/created_at, id/tweet_id, text/full_text)
Tweet text duplicated in tweet and archive table
Dog stages in four columns instead of one column in archive table
