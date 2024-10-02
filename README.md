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
- **pandas**: For data manipulation, cleaning, and analysis.
- **matplotlib**: For data visualization.
- **scipy**: For statistical testing (Chi-square test).

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
- Summed up the observations of species in parks to understand the distribution of protected and non-protected species.
- Found statistically significant differences between species protection levels across parks using the Chi-square test.
