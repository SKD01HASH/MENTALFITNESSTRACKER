# Mental Fitness Tracker ML Model
## GLIMPSES


https://github.com/SKD01HASH/MENTALFITNESSTRACKER/assets/94286342/6158767a-e81d-445c-96a9-2edc206bca4d



Welcome to the Mental Fitness Tracker ML Model repository! This project showcases my implementation of a machine learning model for tracking mental fitness. By utilizing the Random Forest Regression algorithm, this model provides valuable insights into mental well-being based on input features.

## Table of Contents

- [About the Mental Fitness Tracker](#about-the-mental-fitness-tracker)
- [Key Features](#key-features)
- [Getting Started](#getting-started)
- [Model Evaluation](#model-evaluation)
- [Usage](#usage)
- [Contributing](#contributing)
- [Acknowledgments](#acknowledgments)
- [License](#license)

## About the Mental Fitness Tracker

The Mental Fitness Tracker ML Model is designed to assess and monitor mental well-being using the Random Forest Regression algorithm. This model analyzes various input features and predicts mental fitness levels based on the provided data.

## Key Features

- Utilizes Random Forest Regression for accurate prediction of mental fitness.
- Provides model evaluation metrics such as Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-Squared (R2) score.
- Offers a pickled model for easy usage and integration into other applications.
- Includes a presentation highlighting the project details and methodology.

## Getting Started

To get started with the Mental Fitness Tracker ML Model, follow these instructions:

1. Clone the repository:
   ```
   git clone https://github.com/SKD01HASH/MentalFitnessTracker.git
   ```

2. Install the required dependencies (such as scikit-learn) using the package manager of your choice.

3. Review the project structure, including the model code, presentation, and pickled model.

## Model Evaluation

The model is evaluated on both the training and testing datasets. The evaluation metrics are calculated using the Random Forest Regression model:

### Training Set Evaluation

```python
# Model evaluation for the training set
ytrain_pred = rf.predict(xtrain)
mse = mean_squared_error(ytrain, ytrain_pred)
rmse = np.sqrt(mean_squared_error(ytrain, ytrain_pred))
r2 = r2_score(ytrain, ytrain_pred)

print("The model performance for the training set")
print("--------------------------------------------")
print('MSE is {}'.format(mse))
print('RMSE is {}'.format(rmse))
print('R2 score is {}'.format(r2))
print("\n")
```

### Testing Set Evaluation

```python
# Model evaluation for the testing set
ytest_pred = rf.predict(xtest)
mse = mean_squared_error(ytest, ytest_pred)
rmse = np.sqrt(mean_squared_error(ytest, ytest_pred))
r2 = r2_score(ytest, ytest_pred)

print("The model performance for the testing set")
print("-------------------------------------------")
print('MSE is {}'.format(mse))
print('RMSE is {}'.format(rmse))
print('R2 score is {}'.format(r2))
```

## Usage

To use the Mental Fitness Tracker ML Model, follow these steps:

1. Load the pickled model from the provided Google Drive link: [Mental Fitness Tracker Pickle Model](https://drive.google.com/file/d/1rM9qf4fBbQ1EQMxRxv5xeWOZDF4ysnwE/view?usp=share_link).
2. Prepare the input data according to the model's requirements.
3. Utilize the model's predict method to obtain mental fitness predictions based on the input data.

### Sample Input and Output

```python
# Sample input
ata = [[0, 1991, 0.228120, 0.719953, 0.126395, 4.821965, 0.447112, 5.116306, 0.444250]]

# Predict the mental fitness quotient
ress = rf.predict(ata)

print("Your Mental Fitness Quotient Is:", ress)
```

## Contributing

Contributions are welcome and greatly appreciated! If you have any suggestions, ideas, or improvements, please submit a pull request. Feel free to open an issue for any bug reports or feature requests.

## Acknowledgments

I would like to express my gratitude to the open-source community and the authors of the scikit-learn library for providing the tools and resources necessary for this project.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use and modify the code for your own purposes.

---

Thank you for your interest in the Mental Fitness Tracker ML Model! I hope this model helps improve mental well-being tracking and understanding. If you have any questions or need further assistance, please don't hesitate to reach out.

Happy tracking!

[Saswata Kumar Dash]

Pickle Model: [Mental Fitness Tracker Pickle Model](https://drive.google.com/file/d/1rM9qf4fBbQ1EQMxRxv5xeWOZDF4ysnwE/view?usp=share_link)

Presentation: [Mental Fitness Tracker Presentation](https://docs.google.com/presentation/d/1ZZ99QMfRMJ6Lbb57NCA4_DLDghP4-CMN/edit?usp=drive_link&ouid=109870843568571470302&rtpof=true&sd=true)
