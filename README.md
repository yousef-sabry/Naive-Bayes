# NaiveBayes Gender Classification

This project implements a gender classification model using the Naive Bayes algorithm. The dataset contains facial features such as `long_hair`, `forehead_width_cm`, `forehead_height_cm`, `nose_wide`, `nose_long`, `lips_thin`, and `distance_nose_to_lip_long`.

## Project Structure

- **NaiveBayes.ipynb**: Jupyter Notebook containing the implementation of the Naive Bayes model, data visualization, and evaluation metrics.
- **gender_classification_v7.csv**: Dataset used for training and testing the model.

## Features

- Data preprocessing and visualization.
- Implementation of Naive Bayes classification.
- Model evaluation using accuracy and classification report.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yousef-sabry/Naive-Bayes.git
   ```
2. Open `NaiveBayes.ipynb` in Jupyter Notebook or Google Colab.
3. Run all cells to train the model and view the results.

## Dataset

The dataset includes the following features:
- `long_hair`: Binary (1 for long hair, 0 otherwise).
- `forehead_width_cm`: Forehead width in centimeters.
- `forehead_height_cm`: Forehead height in centimeters.
- `nose_wide`: Binary (1 for wide nose, 0 otherwise).
- `nose_long`: Binary (1 for long nose, 0 otherwise).
- `lips_thin`: Binary (1 for thin lips, 0 otherwise).
- `distance_nose_to_lip_long`: Binary (1 for long distance, 0 otherwise).
- `gender`: Target variable (`Male` or `Female`).

## Results

The model achieved an accuracy of **95.70%** on the test set.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
