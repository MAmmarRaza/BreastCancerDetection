# Breast Cancer Classification README

This README provides an overview of the breast cancer classification code, including installation instructions, code description, and usage guidelines.

## Table of Contents
1. [Installation](#installation)
2. [Code Description](#code-description)
3. [Usage](#usage)
4. [Contributing](#contributing)
5. [License](#license)

<div style="background-color:black; color:white; padding:10px;">

## Installation <a name="installation"></a>

To run the breast cancer classification code, you need to follow these steps:

1. **Clone the Repository**: Start by cloning the repository to your local machine using the following command:

`git clone https://github.com/MAmmarRaza/breast-cancer-classification.git`

2. **Install Dependencies**: Install the required dependencies given below:
    Required Libraries

    - numpy
    - pandas
    - os
    - itertools
    - glob
    - PIL
    - cv2
    - matplotlib
    - tensorflow
    - sklearn
    - keras
3. This command will install all the necessary libraries and packages needed to run the code:
  `pip install numpy pandas opencv-python matplotlib tensorflow scikit-learn keras`

4. **Dataset**: The code assumes the availability of the breast cancer dataset. Place the dataset in the appropriate directory structure as required by the code. Download link: https://www.kaggle.com/datasets/paultimothymooney/breast-histopathology-images?resource=download

</div>

<div style="background-color:black; color:white; padding:10px;">

## Code Description <a name="code-description"></a>

The breast cancer classification code performs the following steps:

1. **Data Preprocessing**:
- Loads and preprocesses the breast cancer dataset.
- Normalizes the input data.
- Splits the data into training and testing sets.

2. **Model Architecture**:
- Defines the EfficientNetB0 model architecture for breast cancer classification.
- Compiles the model with appropriate optimizer and loss function.

3. **Training**:
- Trains the model using the training data.
- Monitors and logs the loss and accuracy metrics during training.

4. **Evaluation**:
- Evaluates the trained model on the testing data.
- Generates loss and accuracy curves to analyze the model performance.

5. **Prediction**:
- Performs predictions on a sample image using the trained model.

6. **Model Saving**:
- Saves the trained model weights and architecture in H5 and JSON formats, respectively.

</div>

<div style="background-color:black; color:white; padding:10px;">

## Usage <a name="usage"></a>

To use the breast cancer classification code, follow these steps:

1. Ensure that you have installed all the necessary dependencies and have the dataset available in the expected directory structure.

2. Navigate to the project directory containing the code.

3. Download the dataset https://www.kaggle.com/datasets/paultimothymooney/breast-histopathology-images?resource=download

4. Place the dataset and .ipynb file in the same folder.
5. Run the code step by step in .ipynb file and at the end model will be stored in md directory.

5. Follow the instructions provided by the application to input the required information, such as image paths or other relevant details.

6. Monitor the output to see the classification results, loss and accuracy curves, and any other relevant information.

</div>

<div style="background-color:black; color:white; padding:10px;">

## Contributing <a name="contributing"></a>

Contributions to the breast cancer classification code are welcome. If you find any issues, have suggestions for improvements, or would like to add new features, please submit a pull request or open an issue on the GitHub repository.

</div>

<div style="background-color:black; color:white; padding:10px;">

## License <a name="license"></a>

The breast cancer classification code is licensed under the [MIT License](https://opensource.org/licenses/MIT). You are free to modify, distribute, and use the code as per the terms of the license.

</div>
