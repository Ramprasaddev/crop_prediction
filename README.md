# Crop and Fertilizer Recommendation using Machine Learning

This project aims to recommend the most suitable crops and fertilizers based on soil properties, weather conditions, and other parameters using Machine Learning algorithms.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Machine Learning Workflow](#machine-learning-workflow)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Future Improvements](#future-improvements)
- [Contributing](#contributing)
- [License](#license)

---

## Introduction
Agriculture plays a crucial role in feeding the growing population. Recommending the right crop and fertilizer based on various parameters can help optimize yield and reduce costs for farmers. This project utilizes Machine Learning to analyze data and make accurate recommendations.

## Dataset
The dataset contains the following parameters:
- Soil type and pH
- Temperature and humidity
- Rainfall
- Crop growth history

**Source:** [Public agricultural datasets]

## Technologies Used
- Python
- Pandas and NumPy for data manipulation
- Scikit-learn for Machine Learning
- Matplotlib and Seaborn for data visualization
- Flask (optional, for web-based deployment)

## Machine Learning Workflow
1. **Data Collection and Preprocessing**
2. **Exploratory Data Analysis (EDA)**
3. **Feature Selection**
4. **Model Training and Evaluation**
    - Decision Tree
    - Random Forest
    - K-Nearest Neighbors (KNN)
    - Logistic Regression
5. **Recommendation System Development**

## Installation
1. Clone this repository:
    ```bash
    git clone https://github.com/Ramprasaddev/crop_prediction.git
    ```
2. Navigate to the project directory:
    ```bash
    cd crop_prediction
    ```


## Usage
1. Prepare your dataset and place it in the `data` folder.
2. Run the training script:
    ```bash
    python train_model.py
    ```
3. (Optional) Launch the web-based interface:
    ```bash
    python app.py
    ```

## Results
- The recommendation system achieved **85% accuracy** on the test dataset.
- Predicted crops and fertilizers accurately for multiple test cases.

## Future Improvements
- Integrate real-time weather data for dynamic recommendations.
- Deploy a mobile-friendly interface.
- Expand the dataset for better generalization.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or suggestions.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Contact
- **Email:** ramprasaddharmpuri.dev@gmail.com  
- **GitHub:** [github.com/Ramprasaddev](https://github.com/Ramprasaddev)  
- **LinkedIn:** [linkedin.com/in/rammmprasad09](https://www.linkedin.com/in/rammmprasad09)
