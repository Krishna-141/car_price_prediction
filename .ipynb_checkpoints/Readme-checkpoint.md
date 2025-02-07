# Car Price Prediction using Linear Regression

## Overview
This project builds a **Linear Regression** model to predict car prices based on various features. The dataset is preprocessed by handling missing values, removing outliers, and selecting relevant features before training the model.

## Dataset
- The dataset contains information about various car attributes such as price, mileage, year of manufacture, fuel type, etc.
- Missing values and outliers have been handled to improve model accuracy.

## Steps Involved
1. **Data Preprocessing**  
   - Handling missing values
   - Removing outliers
   - Feature selection
2. **Exploratory Data Analysis (EDA)**  
   - Data visualization using histograms, scatter plots
   - Splitting the data into training and testing sets
   - Applying **Linear Regression** from `scikit-learn`
4. **Model Evaluation**  
   - Metrics used: R-squared score

## Results
- The model provides insights into how different car attributes influence price.
- Performance metrics indicate the model’s accuracy in predicting unseen car prices.

## Installation & Usage
1. Clone this repository:
   ```bash
   git clone https://github.com/krishna-141/car_price_prediction.git
   cd car_price_prediction
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook project_car.ipynb
   ```

## Contributing
Feel free to open issues or submit pull requests if you find areas for improvement!

## License
This project is open-source and available under the [MIT License](LICENSE).

