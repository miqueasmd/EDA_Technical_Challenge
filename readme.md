# Exploratory Data Analysis Challenge

Welcome to the Exploratory Data Analysis Challenge on the Melbourne Housing Market dataset! This repository contains the code and analysis for the EDA challenge, where we explore and analyze the Melbourne Housing Market dataset to gain insights and build a simple linear regression model for property price prediction.

## Dataset Description

The Melbourne Housing Market dataset contains information on various properties sold in Melbourne between 2016 and 2018. The dataset has a total of 21 columns, including features such as price, location, property type, land size, and building area, among others.

### Dataset Columns:

- **Suburb**: The suburb where the property is located.
- **Address**: The street address of the property.
- **Rooms**: The number of rooms in the property.
- **Type**: The type of the property (house, townhouse, unit, etc.).
- **Price**: The price at which the property was sold.
- **Method**: The method of sale (auction, private treaty, etc.).
- **SellerG**: The agency or agent who sold the property.
- **Date**: The date on which the property was sold.
- **Distance**: The distance of the property from Melbourne's central business district (CBD) in kilometers.
- **Postcode**: The postcode of the suburb where the property is located.
- **Bedroom2**: The number of bedrooms in the property (other than the master bedroom).
- **Bathroom**: The number of bathrooms in the property.
- **Car**: The number of car spaces in the property.
- **Landsize**: The size of the land on which the property is located in square meters.
- **BuildingArea**: The size of the building on the land in square meters.
- **YearBuilt**: The year in which the building was constructed.
- **CouncilArea**: The local government area in which the property is located.
- **Lattitude**: The latitude coordinate of the property.
- **Longtitude**: The longitude coordinate of the property.
- **Regionname**: The general region in Melbourne (west, north, south-east, etc.).
- **Propertycount**: The number of properties in the suburb.

## Challenge Instructions

1. **Import Required Libraries**: Import the necessary libraries, including pandas, numpy, matplotlib, and seaborn.
2. **Load the Dataset**: Load the Melbourne Housing Market dataset into a pandas DataFrame.
3. **Data Overview**: Provide an overview of the dataset, including the number of rows and columns, and display the first few rows.
4. **Data Cleaning**: Perform data cleaning tasks such as handling missing values, removing duplicates, and correcting data types.
5. **Exploratory Data Analysis**:
   - **Price Distribution**: Visualize the distribution of property prices using histograms and box plots.
   - **Location Analysis**: Analyze the distribution of properties across different locations and visualize it using bar plots and maps.
   - **Property Type Analysis**: Analyze the distribution of different property types and visualize it using bar plots.
   - **Land Size vs. Building Area**: Analyze the relationship between land size and building area using scatter plots.
6. **Statistical Analysis**: Perform statistical analysis to identify significant relationships in the data.
7. **Correlation Analysis**: Calculate and visualize the correlation matrix to identify relationships between different features.
8. **Price Prediction Model**: Build a simple linear regression model to predict property prices based on selected features.
9. **Conclusion**: Summarize the findings and insights gained from the exploratory data analysis and statistical analysis.

## Repository Structure

```
├── eda_challenge.ipynb    # Jupyter Notebook containing the EDA challenge code and analysis
├── README.md              # This README file
```

## How to Run the Notebook

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/eda-challenge.git
   cd eda-challenge
   ```

2. **Install Required Libraries**:
   Ensure you have the required libraries installed. You can install them using pip:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn statsmodels
   ```

3. **Open the Jupyter Notebook**:
   ```bash
   jupyter notebook eda_challenge.ipynb
   ```

4. **Run the Notebook**:
   Follow the instructions in the notebook to run the cells and perform the analysis.

## Conclusion

This repository contains the code and analysis for the Exploratory Data Analysis Challenge on the Melbourne Housing Market dataset. The challenge involves various tasks such as data cleaning, exploratory data analysis, statistical analysis, and building a simple linear regression model for property price prediction. The insights gained from this analysis can help understand the Melbourne housing market better.

Feel free to explore the notebook and provide any feedback or suggestions. Happy analyzing!

## License

This project is licensed under the MIT License - see the LICENSE file for details.

---

**Note**: Replace `your-username` with your actual GitHub username in the clone URL.