# Managing the end-to-end machine learning lifecycle with MLFlow

This Repository contains the resources for my tutorial **"Managing the end-to-end machine learning lifecycle with MLFlow"** at pyData/pyCon Berlin 2019.

# Basic setup

## Setup the environment
- clone this repository
- **with virtualenv (recommended)**
  - install virtualenv: `pip install virtualenv`
  - create a new environment: `virtualenv mlflow_tutorial`
  - activate the environment: `source mlflow_tutorial/bin/activate`
  - run `pip install -r requirements.txt`
  

## The notebook
- Get the `hands_on_example.ipynb`
- run `jupyter notebook`

## Start the ML FLow Tracking Server
 - mlflow server --backend-store-uri mlruns/ --default-artifact-root mlruns/ --host 0.0.0.0 --port 5000


## Project Screenshots

![Screenshot 2025-02-17 113247](https://github.com/user-attachments/assets/42023c42-f3a6-44c2-9974-6cc313b9ae56)

![Screenshot 2025-02-17 113306](https://github.com/user-attachments/assets/c56fe5f8-3a27-4f3e-920f-5d8c61afdab4)

![Screenshot 2025-02-17 112217](https://github.com/user-attachments/assets/ce9f2893-f603-4020-90c5-c4ea7ebf59cb)

![Screenshot 2025-02-17 115122](https://github.com/user-attachments/assets/70303057-e144-44d5-8b35-b9771842413b)

![Screenshot 2025-02-17 113106](https://github.com/user-attachments/assets/0ebd68eb-69b7-406f-b078-0719d4ae46a7)

