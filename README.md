# Integrated-Project-1
Predicting Video Game Success: Analyzing Trends and Patterns from 2016 Data

# Video Game Sales Analysis

## Project Description

This project involves analyzing video game sales data for the online store Ice, which sells video games worldwide. We aim to identify patterns that determine whether a game succeeds or not, enabling us to spot potential big winners and plan effective advertising campaigns.

### Data Description

The dataset contains the following information:
- **User and expert reviews**
- **Genres**
- **Platforms (e.g., Xbox or PlayStation)**
- **Historical data on game sales** 

The data goes back to 2016, and we'll use it to plan a campaign for 2017. The dataset also includes the ESRB (Entertainment Software Rating Board) ratings, which assign age ratings to games.

### Steps to Complete the Project

#### Step 1: Open the Data File and Study the General Information
- Load the dataset from `/datasets/games.csv`.
- Examine the general structure and contents of the dataset.

#### Step 2: Prepare the Data
- Replace column names with lowercase.
- Convert data to the appropriate types and describe the changes.
- Handle missing values:
  - Explain the method of filling or leaving them blank.
  - Analyze the possible reasons for missing values.
  - Handle the "TBD" (to be determined) cases appropriately.
- Calculate total sales (sum of sales in all regions) for each game and add as a new column.

#### Step 3: Analyze the Data
- Examine the number of games released each year to determine the significance of the data for each period.
- Analyze sales variation across different platforms:
  - Identify platforms with the greatest total sales.
  - Build a sales distribution for each year.
  - Find platforms that were once popular but now have zero sales.
  - Determine the lifespan of platforms.
- Identify relevant data periods to build a model for 2017.
- Focus on data that is relevant for the analysis and disregard older data.
- Identify leading platforms in sales, those growing or shrinking.
- Build a box plot for global sales by platform and describe the findings.
- Analyze the effect of user and professional reviews on sales for a popular platform:
  - Build a scatter plot and calculate the correlation between reviews and sales.
  - Compare sales of the same games on other platforms.
- Examine the distribution of games by genre and identify the most profitable genres.

#### Step 4: Create a User Profile for Each Region
- Determine the top five platforms and genres for each region (NA, EU, JP).
- Describe variations in market shares and genre preferences.
- Analyze the effect of ESRB ratings on sales in each region.

#### Step 5: Test Hypotheses
- Test the following hypotheses:
  - Average user ratings of the Xbox One and PC platforms are the same.
  - Average user ratings for the Action and Sports genres are different.
- Formulate null and alternative hypotheses.
- Choose and explain the significance level for hypothesis testing.

#### Step 6: Write a General Conclusion
- Summarize the findings and insights gained from the analysis.

## Tools and Technologies
- Python
- Jupyter Notebook
- Pandas for data manipulation
- Matplotlib and Seaborn for data visualization
- Scipy for statistical tests


