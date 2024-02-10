
---

## Parkinson's Disease Prediction Project

### Overview

This project aims to develop a machine learning model for predicting the likelihood of Parkinson's disease based on certain features extracted from biomedical voice recordings. Parkinson's disease is a neurodegenerative disorder characterized by motor and non-motor symptoms. Early detection is crucial for effective management and treatment of the disease.

### Features

The model utilizes various features extracted from voice recordings, including acoustic measures such as jitter, shimmer, and harmonics-to-noise ratio (HNR), as well as fundamental frequency (F0) and formant frequencies.

### Dataset

The dataset used for training and evaluation consists of voice recordings collected from individuals with and without Parkinson's disease. It is sourced from [provide dataset source/link].

### Installation

To run the project locally, follow these steps:

1. Clone the repository:
   ```
   git clone https://github.com/3008aryansingh/parkinson-prediction.git
   ```

2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Download the dataset and place it in the `data/` directory.

### Usage

1. Navigate to the project directory:
   ```
   cd parkinson-prediction
   ```

2. Preprocess the data:
   ```
   python preprocess.py
   ```

3. Train the machine learning model:
   ```
   python train.py
   ```

4. Evaluate the model:
   ```
   python evaluate.py
   ```

### Results

The trained model achieves accuracy, precision and recall on the test set, demonstrating its effectiveness in predicting Parkinson's disease.

### Contributing

Contributions are welcome! If you'd like to contribute to the project, please follow these guidelines:

- Fork the repository.
- Create a new branch for your feature or bug fix.
- Make your changes and submit a pull request.

### License

This project is licensed under the MIT. See the `LICENSE` file for more details.

### Contact

For any inquiries or suggestions regarding the project, please contact singharyan3008@gmail.com/ 9860177421.

---

