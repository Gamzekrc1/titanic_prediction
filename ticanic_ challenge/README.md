# Titanic Survival Prediction

This project uses machine learning to predict the survival of passengers on the Titanic based on features like age, sex, fare, and passenger class.

## Getting Started

These instructions will help you set up a virtual environment and install the required packages to run the project.

### Prerequisites

Before proceeding, make sure you have Python 3.6 or later installed on your system. You can check your Python version by running:

```bash
python --version

Setting Up a Virtual Environment
A virtual environment helps manage dependencies and prevent conflicts with other Python projects. Follow these steps to create a virtual environment:

Install virtualenv if you haven't already:
pip install virtualenv

Navigate to the project directory and create a new virtual environment:
cd /path/to/project
virtualenv venv

Activate the virtual environment:
For Windows:
venv\Scripts\activate

For macOS/Linux:
source venv/bin/activate


Installing Required Packages
Once the virtual environment is activated, install the required packages using the requirements.txt file:
pip install -r requirements.txt


Running the Project

After installing the required packages, you can run your Python script to train and evaluate the Titanic survival prediction model:

python main.py
