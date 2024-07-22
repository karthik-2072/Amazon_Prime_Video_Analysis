# Amazon Prime Video Data Analytics Project

## Project Overview
This project involves analyzing Amazon Prime Video data and developing an interactive dashboard using Power BI. The data includes information about movies and TV shows, their ratings, genres, directors, release dates, and country of origin. 

## Steps Involved

### 1. Data Collection
- The dataset was collected from an open-source platform. It includes details about titles available on Amazon Prime Video.

### 2. Data Preprocessing
- **Null Value Removal**: We performed an initial data cleaning to remove null values. This step ensures that our analysis is accurate and not skewed by missing data.
- **Data Transformation**: Several transformations were applied to the data to prepare it for analysis. These transformations included:
  - Converting data types where necessary (e.g., dates and numerical values).
  - Creating new calculated columns to facilitate better analysis (e.g., extracting year from release dates).
  - Standardizing categorical variables to ensure consistency.

### 3. Data Analysis
- **Descriptive Statistics**: Initial analysis was conducted to understand the distribution of data, including the number of titles, ratings, genres, and directors.
- **Exploratory Data Analysis (EDA)**: Visualizations were created to explore the data and identify patterns and insights.

### 4. Dashboard Development
- **Power BI**: An interactive dashboard was created using Power BI. The dashboard includes the following visualizations:
  - **Total Titles**: Displays the total number of titles available on Amazon Prime Video.
  - **Total Ratings**: Shows the different ratings and their counts.
  - **Total Genres**: Highlights the various genres and their counts.
  - **Total Directors**: Provides a count of unique directors.
  - **Start and End Dates**: Indicates the range of release dates in the dataset.
  - **Ratings by Total Shows**: Bar chart showing the number of shows for each rating category.
  - **Total Shows by Country**: Map visualization displaying the number of shows by country.
  - **Movies and TV Shows**: Pie chart differentiating between movies and TV shows.
  - **Total Shows by Release Year**: Line chart showing the trend of releases over the years.
  - **Genres by Total Shows**: Bar chart showing the number of shows for each genre.

## How to Run the Project
1. **Clone the Repository**: Clone the project repository to your local machine.
    ```bash
    git clone <repository_url>
    ```
2. **Install Power BI**: Ensure you have Power BI Desktop installed on your machine.
3. **Open the Power BI File**: Open the provided Power BI file (`Amazon_Dashboard.pbix`) in Power BI Desktop.
4. **Explore the Dashboard**: Interact with the various visualizations to explore the data.

## Conclusion
This project demonstrates the process of data cleaning, transformation, analysis, and visualization using Power BI. The interactive dashboard provides valuable insights into the content available on Amazon Prime Video, including trends in ratings, genres, and release dates.

