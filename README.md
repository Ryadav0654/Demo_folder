To train a model for optimizing sustainable fertilizer usage for higher crop yield, you'd typically require a structured dataset with multiple records (rows), each containing detailed information on soil conditions, climate, crop types, fertilizer usage, and resulting yields. Below is a synthetic dataset sample based on the required data components. This will help you in understanding how to structure the data for training.

### Sample Data Structure

| **Soil Type** | **pH Level** | **Nitrogen (N)** | **Phosphorus (P)** | **Potassium (K)** | **Organic Matter (%)** | **Soil Moisture (%)** | **Crop Type** | **Growth Stage** | **Temperature (°C)** | **Rainfall (mm)** | **Humidity (%)** | **Sunlight (hours)** | **Fertilizer Type** | **Fertilizer Amount (kg/ha)** | **Yield (kg/ha)** | **Cost (USD)** | **Profit (USD)** |
|---------------|--------------|------------------|--------------------|-------------------|------------------------|----------------------|---------------|-----------------|----------------------|-------------------|------------------|----------------------|--------------------|------------------------------|-------------------|----------------|-----------------|
| Loamy         | 6.5          | 50 ppm           | 30 ppm             | 40 ppm            | 2.5                    | 20                   | Wheat         | Vegetative      | 25                   | 100               | 70               | 8                    | Inorganic          | 150                          | 3500              | 200            | 1500            |
| Clay          | 5.8          | 45 ppm           | 35 ppm             | 50 ppm            | 3.0                    | 25                   | Corn          | Flowering       | 28                   | 120               | 75               | 7                    | Organic            | 200                          | 4000              | 250            | 1700            |
| Sandy         | 7.0          | 60 ppm           | 25 ppm             | 30 ppm            | 1.5                    | 18                   | Rice          | Germination     | 30                   | 80                | 65               | 9                    | Mixed              | 180                          | 3000              | 230            | 1400            |
| Loamy         | 6.8          | 55 ppm           | 28 ppm             | 35 ppm            | 2.8                    | 22                   | Soybean       | Fruit development | 26                   | 110               | 80               | 6                    | Inorganic          | 160                          | 3800              | 220            | 1600            |
| Clay          | 6.2          | 40 ppm           | 32 ppm             | 45 ppm            | 3.2                    | 30                   | Maize         | Maturity        | 27                   | 95                | 60               | 8                    | Organic            | 210                          | 4200              | 270            | 1800            |
| Loamy         | 6.0          | 48 ppm           | 29 ppm             | 38 ppm            | 2.6                    | 24                   | Barley        | Vegetative      | 24                   | 105               | 72               | 7                    | Mixed              | 170                          | 3700              | 240            | 1550            |
| Sandy         | 7.2          | 62 ppm           | 26 ppm             | 32 ppm            | 1.7                    | 20                   | Oats          | Flowering       | 29                   | 90                | 68               | 8                    | Inorganic          | 150                          | 3200              | 210            | 1450            |
| Clay          | 6.4          | 43 ppm           | 34 ppm             | 42 ppm            | 3.1                    | 28                   | Wheat         | Germination     | 26                   | 115               | 77               | 6                    | Organic            | 190                          | 3900              | 260            | 1650            |
| Loamy         | 6.7          | 52 ppm           | 31 ppm             | 37 ppm            | 2.9                    | 21                   | Corn          | Fruit development | 27                   | 100               | 73               | 7                    | Mixed              | 175                          | 3600              | 250            | 1600            |
| Sandy         | 7.1          | 58 ppm           | 27 ppm             | 33 ppm            | 1.8                    | 19                   | Rice          | Maturity        | 31                   | 85                | 66               | 9                    | Inorganic          | 160                          | 3100              | 220            | 1400            |

### Data Description

- **Soil Type**: Categorical variable representing the type of soil (e.g., Loamy, Clay, Sandy).
- **pH Level**: Numerical variable representing the soil pH.
- **Nitrogen (N), Phosphorus (P), Potassium (K)**: Numerical variables representing the concentration of key nutrients in the soil (in ppm).
- **Organic Matter (%)**: Numerical variable representing the percentage of organic matter in the soil.
- **Soil Moisture (%)**: Numerical variable representing the soil moisture content.
- **Crop Type**: Categorical variable representing the type of crop (e.g., Wheat, Corn, Rice).
- **Growth Stage**: Categorical variable representing the growth stage of the crop (e.g., Germination, Vegetative, Flowering, Maturity).
- **Temperature (°C)**: Numerical variable representing the average daily temperature.
- **Rainfall (mm)**: Numerical variable representing the total rainfall.
- **Humidity (%)**: Numerical variable representing the average daily humidity.
- **Sunlight (hours)**: Numerical variable representing the hours of sunlight per day.
- **Fertilizer Type**: Categorical variable representing the type of fertilizer (e.g., Inorganic, Organic, Mixed).
- **Fertilizer Amount (kg/ha)**: Numerical variable representing the amount of fertilizer applied per hectare.
- **Yield (kg/ha)**: Numerical variable representing the crop yield per hectare.
- **Cost (USD)**: Numerical variable representing the cost of fertilizer application.
- **Profit (USD)**: Numerical variable representing the profit obtained after considering costs.

### Usage

This dataset can be used to train a machine learning model, such as a regression or decision tree model, to predict the best fertilizer strategy based on soil conditions, crop type, climate, and other factors. The goal is to maximize yield while considering sustainability factors like cost and environmental impact.

### How to Use

1. **Preprocessing**: Normalize or scale the numerical data and encode categorical variables.
2. **Model Training**: Split the data into training and testing sets, then train your model on the training set.
3. **Model Evaluation**: Use the testing set to evaluate model performance using metrics like RMSE (Root Mean Squared Error) or R² (coefficient of determination).
4. **Optimization**: Apply the trained model to predict optimal fertilizer usage under different scenarios to maximize yield and sustainability.

This synthetic dataset should give you a good starting point for developing and training a model aimed at sustainable fertilizer optimization.
