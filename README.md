# Creating Cohorts of Songs

#### By Tara Danneman

## Project Overview

In a bid to improve song recommendations for its users, Spotify seeks to create distinct groups, or cohorts, of songs based on various features. By clustering songs into cohorts with similar characteristics, Spotify aims to enhance user engagement by delivering more relevant content tailored to individual preferences. This project involves exploratory data analysis and cluster analysis to identify patterns in song attributes and group them accordingly, thus improving the overall music recommendation experience for Spotify users.

## Table of Contents

- [Project Overview](#project-overview)
- [Data Analysis and Cleaning](#data-analysis-and-cleaning)
- [Feature Engineering and Visualization](#feature-engineering-and-visualization)
- [Dimensionality Reduction](#dimensionality-reduction)
- Clustering
- Conclusion
- Dependencies
- [How to Run](#how-to-run)

## Data Analysis and Cleaning

### Step 1: Analyze and Clean the Data

1. **Import necessary libraries for analytics.**
2. **Get an idea of the columns, values, data types, and descriptions by performing various methods from pandas.**
3. **Check for null values, duplicate values, irrelevant entries, or outliers.**

### Step 2: Refine the Data for Further Processing

1. **Check for missing values and handle any if needed.**
2. **Drop duplicates or unnecessary columns if needed.**
3. **Convert categorical data into integers for plotting using [`get_dummies`](command:_github.copilot.openSymbolFromReferences?%5B%22%22%2C%5B%7B%22uri%22%3A%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2Fc%3A%2FUsers%2Ftarad%2FOneDrive%2FDocuments%2FAI%20ML%20Class%2FNotebooks_Machine_Learning%2FMusic%20Project%2Ffinal_music_project.ipynb%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%2C%22pos%22%3A%7B%22line%22%3A641%2C%22character%22%3A68%7D%7D%5D%2C%22125caef4-3501-4de0-ae1b-481b2bdd5e48%22%5D "Go to definition"). Other methods, such as label encoding, can be used if needed for varying types of analysis.**

## Feature Engineering and Visualization

### Step 3: Perform Data Analysis and Feature Engineering

1. **Utilize suitable visualizations to identify the two albums that should be recommended to anyone based on the number of popular songs in each album.**
2. **Conduct exploratory data analysis to delve into various features of songs, aiming to identify patterns.**
3. **Examine the relationship between a song's popularity and various factors, exploring how this correlation has evolved.**
4. **Provide insights on the significance of dimensionality reduction techniques. Share your ideas and elucidate your observations.**

## Dimensionality Reduction

### Principal Component Analysis (PCA)

- **Apply PCA to reduce the dimensionality of the dataset while retaining most of the variance.**

## Clustering

### K-Means Clustering

- **Apply K-Means clustering to group songs into cohorts based on their features.**
- **Evaluate the clustering performance using silhouette scores.**

## Conclusion

- **Summarize the findings from the exploratory data analysis and clustering.**
- **Discuss the potential impact of these findings on Spotify's recommendation system.**

## Dependencies

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## How to Run

1. **Clone the repository:**
   ```sh
   git clone <repository-url>
   ```
2. **Navigate to the project directory:**
   ```sh
   cd <project-directory>
   ```
3. **Install the required dependencies:**
   ```sh
   pip install -r requirements.txt
   ```
4. **Run the Jupyter Notebook:**
   ```sh
   jupyter notebook FINAL_MUSIC_PROJECT.ipynb
   ```

Feel free to explore the notebook and modify the code as needed to further analyze and visualize the data.
