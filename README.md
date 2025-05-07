# QMSS Practicum Project

This repository contains the materials and report for the **Columbia QMSS Practicum Project**. This project aims to develop a predictive software system for early warning of cloudbursts in urban areas. 

## Table of Contents

- [QMSS Practicum Project](#qmss-practicum-project)
  - [Table of Contents](#table-of-contents)
  - [Project Overview](#project-overview)
  - [Report](#report)
  - [Data](#data)
  - [Code](#code)
  - [Images](#images)
  - [Installation and Setup](#installation-and-setup)
  - [Contributing](#contributing)
  - [License](#license)

## Project Overview

The INDRA project, sponsored by Columbia University’s QMSS program and AltSurya Inc., aims to develop a predictive software system for early warning of cloudbursts in India. The system will utilize machine learning and multiple data sources to enhance disaster preparedness for residents and businesses. The key objectives include predicting cloudburst occurrence within a 3-hour window, estimating intensity and potential impact, and achieving a prediction accuracy surpassing the current 50% benchmark in target locations. The project involves data preprocessing, model development, and performance evaluation.

## Report

The final project report is available as a PDF. You can download it from the link below:

- [Download the full report](./Final%20report.pdf)

## Data

The data used in this project is stored in the `data` folder. 

## Code

All code used for data analysis is in the `scripts` folder.
- **Cloudburst prediction.ipynb**: Script for preprocessing the data, running the analysis, and generating results.


## Images

Any figures or images related to the project are stored in the `images` folder. These include:

- **Hourly Precipitation distribution.png**: A figure visualizing the distribution of hourly precipitation.
- **Time series of the key variable.png**: A figure representing the time series of the key variable.
- **INITIAL MODEL MATRIX.png**: A figure displaying the initial model's correlation matrix.
- **Matrix with dry period feature.png**: A figure of the model's correlation matrix, including interaction terms and dry period features.

## Installation and Setup

To set up this project locally, follow the steps below:

1. Clone the repository:

    ```bash
    git clone https://github.com/linxi75/QMSS-Practicum-Project.git
    ```

2. Navigate into the project directory:

    ```bash
    cd QMSS-Practicum-Project
    ```

3. If needed, set up a virtual environment:

    ```bash
    python3 -m venv env
    source env/bin/activate   # On Windows use `env\Scripts\activate`
    ```

4.  Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```
5. Run the analysis using the Jupyter notebook:

    ```bash
    jupyter notebook scripts/Cloudburst\ prediction.ipynb
    ```

## Contributing

If you'd like to contribute to this project, feel free to fork the repository, create a new branch, make your changes, and submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.
