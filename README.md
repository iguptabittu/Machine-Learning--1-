# Mushroom Classification: Poisonous vs. Non-Poisonous

## Overview
This project is designed to classify mushrooms as poisonous or non-poisonous based on various features. Using a dataset of mushroom attributes, the model employs machine learning techniques to predict the toxicity of mushrooms, which can be critical for foragers, scientists, and food safety.

## Features
The project uses various mushroom characteristics, such as:
- Cap shape, surface, and color
- Gill size and spacing
- Stalk shape, root, and surface
- Habitat and population

These features are processed to train a classification model to distinguish between poisonous and non-poisonous mushrooms.

## Dataset
The dataset used for this project is a cleaned and preprocessed version of the popular **Mushroom Dataset** available on [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/mushroom). It contains categorical data describing 22 different attributes of mushrooms.

### Target Variable
- **Poisonous (p)** or **Edible (e)**

## Project Structure
- **Data Preprocessing:** Handles missing values and encodes categorical variables.
- **Exploratory Data Analysis (EDA):** Visualizes relationships between features and the target variable.
- **Modeling:** Uses machine learning algorithms (e.g., Decision Trees, Random Forests) to build a classification model.
- **Evaluation:** Assesses the model using metrics like accuracy, precision, recall, and F1-score.

## Installation
### Prerequisites
Ensure you have the following installed:
- Python 3.7+
- Jupyter Notebook or Jupyter Lab
- Required Python libraries: pandas, numpy, matplotlib, seaborn, scikit-learn

### Setup
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/mushroom-classification.git
   ```
2. Navigate to the project directory:
   ```bash
   cd mushroom-classification
   ```
3. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Open the Jupyter notebook:
   ```bash
   jupyter notebook Untitled22.ipynb
   ```
2. Run the cells step by step to preprocess the data, train the model, and evaluate performance.

## Results
The final classification model achieves high accuracy, making it reliable for distinguishing between poisonous and non-poisonous mushrooms. The notebook provides detailed insights into model performance and feature importance.

## Limitations
- The model's performance is limited to the dataset's features and quality. It may not generalize well to unseen mushroom types.
- The dataset assumes perfect identification of mushroom features, which may not be realistic in field conditions.

## Contributing
Contributions are welcome! If you'd like to improve the model or add new features, feel free to open a pull request.

## License
This project is licensed under the MIT License.

## Acknowledgments
- UCI Machine Learning Repository for the dataset
- Scikit-learn for machine learning tools
- Matplotlib and Seaborn for visualization

---
**Disclaimer:** Do not rely solely on this model to determine mushroom safety. Always consult an expert when identifying mushrooms in the wild.

