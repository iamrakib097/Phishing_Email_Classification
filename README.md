# Phishing Email Detection 

##Overview

This GitHub repository contains the source code for a phishing email detection application built using Streamlit. The application utilizes a voting model composed of Support Vector Classifier (SVC), Linear Regression, and Extra Trees Classifier, achieving an impressive accuracy of 97.7% and precision of 98%.
#Table of Contents
1. [Installation](#installation)
2. [Usage](#usage)
3. [Model Training](#model-training)
4. [Dataset](#dataset)
5. [Results](#results)
6. [Contributing](#contributing)
7. [License](#license)

##Installation

To get started, ensure you have Python 3 installed on your machine. Then, clone the repository and install the required dependencies using the following commands:

```bash
git clone https://github.com/iamrakib097/Phishing_Email_Classification.git
cd phishing-email-detection
pip install -r requirements.txt
```
##Usage

Run the Streamlit application with the following command:

```bash

streamlit run app.py
```
Visit the provided URL in your web browser to interact with the phishing email detection application.
Model Training

If you wish to train the model with your own dataset or explore the training process, follow these steps:
```markdown
    Open the phishing-email.ipynb Jupyter Notebook.
    Modify the notebook as needed for your dataset or model parameters.
    Execute the cells to train the model.
    Update the application with the newly trained model.
```

##Dataset

The dataset used for training the model is included in this repository as `Phishing_email.csv`. It contains [provide a brief description of the dataset, e.g., features, labels, etc.].
If you want to explore or use a different dataset, feel free to replace it with your own or find a suitable one on platforms like [Kaggle](https://www.kaggle.com/datasets).

##Results

The voting model achieved the following performance metrics:
```markdown
    Accuracy: 97.7%
    Precision: 98%
```
Feel free to explore the results directory for more detailed information on the model's performance.
##Contributing

Contributions to this project are welcome. If you find a bug or have suggestions for improvement, please open an issue or submit a pull request.
##License

This project is licensed under the MIT License. Feel free to use and modify the code for your own purposes.

Thank you for using our phishing email detection application! If you have any questions or concerns, please don't hesitate to reach out.
