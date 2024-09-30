# Cars Sales Insights
This project aims to predict the selling price of cars using various features such as year, month, odometer reading, condition, make, body type, trim, model, transmission, and color. The project uses a linear regression model to make predictions.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Data](#data)
- [Model](#model)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/PolaOssama/Cars_Sales_insights.git
    cd Cars_Sales_insights
    ```

2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Place your dataset (`car_prices.csv`) in the root directory of the project.

2. Run the script:
    ```bash
    python cars_selling_price_prediction.py
    ```

3. The script will output the evaluation metrics and a predicted selling price for a sample input.

## Project Structure
car-selling-price-prediction/
│
├── cars_selling_price_prediction.py # Main script for prediction
├── requirements.txt # List of required packages
├── README.md # Project documentation
└── car_prices.csv # Dataset (not included in the repository)

## Data

The dataset should be a CSV file named `car_prices.csv` with the following columns:
- `saledate`: Date of sale
- `year`: Year of the car
- `month`: Month of the sale
- `odometer`: Odometer reading
- `condition`: Condition of the car
- `make`: Make of the car
- `body`: Body type of the car
- `trim`: Trim of the car
- `model`: Model of the car
- `transmission`: Transmission type
- `color`: Color of the car
- `sellingprice`: Selling price of the car

## Model

The project uses a linear regression model to predict the selling price of cars. The features are one-hot encoded and standardized before training the model.

## Results

The model's performance is evaluated using the following metrics:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R^2 Score

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
