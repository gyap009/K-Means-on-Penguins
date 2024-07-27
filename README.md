# K-Means Model on Penguins

## Overview
This project demonstrates the use of K-Means clustering on the Palmer Archipelago (Antarctica) penguin dataset. The goal is to identify patterns and effectively group the data based on various features such as species, island, bill length, bill depth, flipper length, and body mass. This project was completed as part of the NTU-Google Scholarship - Google Advanced Data Analytics course.

## Dataset
The dataset used in this project is the Palmer Archipelago (Antarctica) penguin dataset, which includes the following columns:
- `species`: Penguin species (Adelie, Gentoo, Chinstrap)
- `island`: Island in the Palmer Archipelago (Dream, Torgersen, Biscoe)
- `bill_length_mm`: Bill length (mm)
- `bill_depth_mm`: Bill depth (mm)
- `flipper_length_mm`: Flipper length (mm)
- `body_mass_g`: Body mass (g)
- `sex`: Gender (Male, Female)
- `year`: Year of data collection (2007, 2008, 2009)

## Data Exploration and Cleaning
Initial data exploration and cleaning steps included:
- Loading the dataset
- Handling missing values
- Encoding categorical variables
- Standardizing numerical features

## Data Visualization
Data visualization was conducted to gain insights into the dataset:
- Elbow method (clustering)
- Silhouette
- Bar graphs

## Data Preprocessing
The preprocessing steps involved:
- Handling missing values
- Encoding categorical variables
- Standardizing numerical features

## Clustering with K-Means
The K-Means clustering algorithm was applied to the dataset to identify patterns and group the data into clusters. Key steps included:
- Finding the optimal number of clusters using the elbow method and silhouette scores
- Fitting the K-Means model to the data
- Analyzing and visualizing the resulting clusters

## Conclusion
Key takeaways from this project:
- The clusters are mostly differentiated by species and sex, as shown by the groupby results and corresponding graphs.
- The elbow plot and silhouette scores suggest that 6 clusters are optimal for this data.
- Having 6 clusters makes sense because the study suggests that there is sexual dimorphism (differences between the sexes) for each of the three species (2 sexes * 3 different species = 6 clusters).

Summary for stakeholders:
- The K-Means clustering enabled this data to be effectively grouped. It helped identify patterns that can educate team members about penguins.
- The success of the cluster results suggests that the organization can apply clustering to other projects and continue augmenting employee education.

## References
NTU-Google Scholarship - Google Advanced Data Analytics
