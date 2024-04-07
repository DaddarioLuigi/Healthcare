
# EEG Signal Classification for Epilepsy

## Overview
This project presents a machine learning approach to classify EEG signals from patients with epilepsy. By focusing on distinguishing between mild (class 3) and mild-severe (class 4) cases of epilepsy, it contributes to the precision medicine efforts in neurological studies. The classification employs a Support Vector Machine (SVM), a powerful method for handling complex classification tasks.

## Objective
To classify EEG signals into two categories:
- **Class 3**: Patients with mild epilepsy.
- **Class 4**: Patients with mild-severe epilepsy.

## Data Description
The EEG signals used in this project are categorized based on the severity of seizures, with levels ranging from 1 to 5. This project specifically focuses on classes 3 and 4.

## Methodology
1. **Data Preparation**: Pre-processing steps are applied to the EEG signals to make them suitable for machine learning models.
2. **Feature Extraction**: Relevant features from the EEG signals are extracted to characterize the patterns associated with different epilepsy levels.
3. **Model Training**: A Support Vector Machine (SVM) classifier is trained on the extracted features to distinguish between classes 3 and 4.
4. **Evaluation**: The model's performance is evaluated using appropriate metrics to ensure reliability and effectiveness in classification.

## Requirements
- Python 3.x
- Libraries: scikit-learn, numpy, scipy, matplotlib, pandas, seaborn (Specific installation commands and versions are detailed within the notebook).

## Usage
To replicate this study or apply the methodology to new data, follow the instructions and code provided in the notebook. Adjustments to the pre-processing and feature extraction steps may be necessary depending on the characteristics of the new dataset.

## Contribution
Contributions are welcome, especially in the areas of model optimization, feature engineering, and expanding the classification to other classes of epilepsy severity.

## License
[MIT License](https://opensource.org/licenses/MIT)
