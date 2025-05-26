# APP-Store-Analysis

This project is based on the Kaggle - Mobile App Store Dataset (https://www.kaggle.com/datasets/ramamet4/app-store-apple-data-set-10k-apps), using Python (Pandas + Seaborn) for exploratory data analysis (EDA). The goal is to uncover insights into user behavior across various dimensions, including app ratings, engagement levels, retention tendencies, and category structures.

# Overview of Analyses

1. Rating Influencing Factors
   
Explored how app ratings relate to variables such as price, app size, and total number of ratings to identify key drivers of higher user ratings.

2. Performance Analysis by App Category
   
  Grouped apps by prime_genre (primary category)
  
  Calculated for each category:
    Average user rating
      Median number of user ratings
    Average app price
      Identified categories with highest and lowest user ratings

3. Visualizations: Bar charts and boxplots

  Key Findings:
    Shopping and Business apps have the highest median rating counts — indicating higher user engagement.
    Medical and Business apps have the highest average prices — significantly higher than most mainstream free categories.
 
  Free vs Paid App Comparison
    Dataset overview:
      Free apps: 4,054
      Paid apps: 3,141
    In general, free apps slightly outnumber paid apps
    Games is the largest category, with nearly a 50/50 split between free and paid
    Certain categories, such as Education, show a much higher share of paid apps

  Key comparison insights:
    Free apps tend to have more user ratings (greater engagement)
    Paid apps have slightly higher average ratings (possibly due to higher quality or expectations)
  
  Visuals:
      Boxplot comparison of ratings
      Stacked bar chart showing Free vs Paid app share by category
