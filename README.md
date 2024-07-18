# FIFA21 Dataset Cleaning Project

## Overview

This project focuses on the extensive cleaning of the FIFA21 dataset. The dataset contains detailed information about football players, including their physical attributes, contract details, and various performance metrics. The goal of this project was to prepare the dataset for further analysis and modeling by performing several cleaning and preprocessing steps.

## Cleaning Steps

1. **Height Conversion**:
   - Converted player heights from feet and inches to centimeters.

2. **Weight Conversion**:
   - Converted player weights from pounds to kilograms.

3. **Player Value Normalization**:
   - Standardized player values by converting them to thousands of euros.

4. **Contract Duration**:
   - Checked existing contract durations and created new ones where necessary, ensuring consistency across the dataset.

5. **Data Value Formatting**:
   - Stripped out stars and other extraneous characters from certain data values to maintain uniformity.

6. **Label Encoding**:
   - Applied label encoding to categorical variables to convert them into a format suitable for machine learning models.

## Detailed Steps

### 1. Height Conversion
Player heights were originally in feet and inches, which were converted to centimeters using the formula:

Height (cm) = 30.48Feet + Inches*2.54

### 2. Weight Conversion
Player weights were converted from pounds to kilograms using the conversion factor:

kg = 0.453592lb

### 3. Player Value Normalization
To facilitate analysis, player values were standardized by converting them to thousands of euros. This involved dividing the original values by 1000.

### 4. Contract Duration
Contract duration inconsistencies were addressed by:
- Verifying the existing contract lengths.
- Creating new contract duration fields where missing or incorrect.

### 5. Data Value Formatting
Certain data fields contained extraneous characters such as stars. These were removed to ensure data uniformity.

### 6. Label Encoding
Categorical variables were converted into numeric format using label encoding. This step is crucial for preparing the data for machine learning algorithms, which require numeric input.

## Future Work
- **Modeling**: Develop predictive models to leverage the cleaned dataset for various analyses, such as player performance prediction.
- **Data Visualization**: Develop predictive models to leverage the cleaned dataset for various analyses, such as player performance prediction.
