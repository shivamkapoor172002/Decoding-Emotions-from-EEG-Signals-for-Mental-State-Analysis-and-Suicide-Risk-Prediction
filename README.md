# Decoding-Emotions-from-EEG-Signals-for-Mental-State-Analysis-and-Suicide-Risk-Prediction


This prototype project focuses on leveraging EEG (Electroencephalogram) data to extract and predict emotional states categorized as negative, neutral, or positive. The primary goal is to demonstrate the potential of EEG data in determining mental states and exploring the correlation between theta and delta power with a person's emotional well-being and suicide risk.

## Dataset

The EEG data used in this project is sourced from the [EEG Brainwave Dataset: Feeling Emotions](https://www.kaggle.com/datasets/birdy654/eeg-brainwave-dataset-feeling-emotions) available on Kaggle. Ensure you download and place the dataset appropriately before running the code.

## Code Overview

The code employs a TensorFlow-based neural network to classify emotional states based on EEG features. Here's a brief overview of the key components:

1. **Data Loading and Preprocessing:**
   - EEG data is loaded from the provided CSV file.
   - Labels are mapped to numerical values using a LabelEncoder.
   - Data is split into training and testing sets, and standardization is applied.

2. **Neural Network Architecture:**
   - A sequential neural network with multiple dense layers is created.
   - Dropout layers are incorporated for regularization.

3. **Model Training:**
   - The model is compiled using the Adam optimizer and sparse categorical crossentropy loss.
   - Training is performed for a specified number of epochs.

4. **Evaluation and Prediction:**
   - The model is evaluated on the test set, and accuracy metrics are printed.
   - Predictions are made on the test set, and a classification report is generated.

5. **Further Testing:**
   - The model is tested on new EEG data to assess its generalization capabilities.
   - Confusion matrices and ROC curves are plotted for result visualization.
![image](https://github.com/shivamkapoor172002/Decoding-Emotions-from-EEG-Signals-for-Mental-State-Analysis-and-Suicide-Risk-Prediction/assets/92868323/502b2c79-97d1-43a6-88d0-e7d0a8d9cfaa) ![image](https://github.com/shivamkapoor172002/Decoding-Emotions-from-EEG-Signals-for-Mental-State-Analysis-and-Suicide-Risk-Prediction/assets/92868323/e1b5cd2c-f0b7-4929-b62a-249224910e31)


     

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/your_username/your_project.git
   ```

2. Navigate to the project directory:

   ```bash
   cd your_project
   ```

3. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Run the Jupyter notebook or Python script to train, evaluate, and test the model.

   ```bash
   python your_project_train.py
   ```

## Visualization

The project includes visualizations for model evaluation, such as confusion matrices and ROC curves. These visuals provide insights into the model's performance and its ability to distinguish emotional states.

## Contributing

Contributions to this project are welcome! If you have suggestions, enhancements, or bug fixes, please submit a pull request or open an issue.

## License

This project is licensed under the [MIT License](LICENSE). Feel free to use and modify the code as per your requirements.

---

