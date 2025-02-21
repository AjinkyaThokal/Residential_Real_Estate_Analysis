

## Introduction

The goal of this project is to analyze residential property characteristics and their impact on pricing. By leveraging a rich dataset encompassing various features such as square footage, number of rooms, age, amenities (e.g., pools, fireplaces), and location-specific attributes (e.g., waterfront access), we aim to provide valuable insights into the housing landscape. This analysis serves as a foundation for informed decision-making in the residential real estate domain.

---

## Dataset Overview

The dataset used in this project contains information about residential properties, including:

- **Price**: The sale price of the property.
- **Square Footage**: Total area of the property.
- **Bedrooms and Bathrooms**: Number of bedrooms and bathrooms.
- **Age**: Age of the property in years.
- **Amenities**: Presence of pools, fireplaces, and other features.
- **Architectural Style**: Categorical variable indicating the style of the house.
- **Waterfront Access**: Binary variable indicating whether the property has waterfront access.
- **Days on Market (DOM)**: Number of days the property was listed before being sold.

---

## Analysis Highlights

### 1. **Descriptive Statistics**
   - Explored central tendencies and distributions of key variables (e.g., price, square footage, bedrooms).
   - Identified outliers and calculated trimmed means to mitigate their influence.

### 2. **Correlation Analysis**
   - Examined relationships between variables (e.g., square footage, number of rooms, amenities) and house prices.
   - Found strong positive correlations between square footage, number of rooms, and price.

### 3. **Probability and Hypothesis Testing**
   - Calculated probabilities and confidence intervals for key metrics.
   - Conducted a two-sample t-test to compare house prices for waterfront vs. non-waterfront properties.
   - Performed a chi-squared test to assess the association between the presence of pools and fireplaces.

### 4. **Regression Modeling**
   - Built simple and multiple linear regression models to predict house prices based on property characteristics.
   - Used stepwise regression to simplify the model and retain only the most relevant predictors.
   - Evaluated model performance using k-fold cross-validation.

---

## Key Findings

1. **Square Footage and Price**: Larger homes tend to have higher prices, with square footage being a significant predictor of price.
2. **Waterfront Properties**: Houses with waterfront access command significantly higher prices compared to those without.
3. **Amenities**: Properties with pools are more likely to have fireplaces, suggesting a potential association between these features.
4. **Model Performance**: The reduced regression model explains approximately 73.8% of the variation in house prices, with lower RMSE and higher R-squared values compared to the full model.

---

## Tools and Technologies

- **Programming Language**: R
- **Libraries**:
  - `dplyr`, `ggplot2` for data manipulation and visualization.
  - `stats` for statistical analysis.
  - `MASS` for stepwise regression.
  - `caret` for cross-validation.
- **Version Control**: Git and GitHub.

---

## How to Run the Code

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/Residential-Real-Estate-Analysis.git
   cd Residential-Real-Estate-Analysis
   ```

2. **Install Required Libraries**:
   Ensure you have R installed. Then install the required libraries:
   ```R
   install.packages(c("dplyr", "ggplot2", "MASS", "caret"))
   ```
---

