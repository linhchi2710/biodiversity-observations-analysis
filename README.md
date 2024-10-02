# Biodiversity Conservation Analysis

## Project Overview
This project focuses on analyzing the conservation status of bat species across various national parks. Using Python, we process, clean, and analyze the dataset to understand the relationship between species protection status and their observations across parks. Statistical methods are used to test for significant differences in protection levels between species.

## Key Features
- Data cleaning and aggregation to prepare the dataset for analysis.
- Analysis of species protection status in different national parks.
- Chi-square statistical testing to check for significant differences in species protection.
- Visualization of data using pandas for insight generation.
- Pivot tables for clear representation of species protection across parks.

## Tools & Libraries
- **Python**: Main programming language.
- **Pandas**: For data manipulation, cleaning, and analysis.
- **Matplotlib**: For data visualization.
- **Scipy**: For statistical testing (Chi-square test).

## Dataset
The dataset used in this project contains observations of bat species in various national parks and their conservation status. It includes information about species names, conservation statuses, and the number of observations per park.

## Analysis Process
1. **Data Cleaning**:
- Removed duplicate entries and cleaned species names.
- Checked for missing or incorrect values in the dataset.
   
2. **Exploratory Data Analysis (EDA)**:
   - Grouped the data by national park and protection status.
   - Summed the number of observations across parks and species.
   
3. **Chi-square Test**:
   - Applied the Chi-square test to determine if there are statistically significant differences in protection status between different species.
   
4. **Data Visualization**:
   - Created pivot tables to show the number of observations of protected vs. not protected species in each park.
   - Visualized the results using pandas for better insight.

## Key Results
- **Distribution of Conservation Status for Species**:  
  The vast majority of species were not part of any conservation efforts (5,633 vs. 191 species).

- **Likelihood of Certain Types of Species Being Endangered**:  
  Mammals and birds had the highest percentage of being under protection compared to other species.

- **Statistical Significance in Species Conservation Status**:  
  While mammals and birds did not show a significant difference in conservation percentages, mammals and reptiles exhibited a statistically significant difference in their protection status.

- **Prevalence and Distribution of Bats Amongst Parks**:  
  Bats were found to be the most frequently observed species, with the highest occurrences in Yellowstone National Park.
