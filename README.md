# API AI Collection - Assignment and Campaign

## Introduction

Welcome to the API AI Collection - Assignment and Campaign project! This API is designed to automate the assignment of specific tasks to debt collectors and predict the most effective debt collection strategies (campaigns). The project utilizes machine learning techniques, specifically Random Forest for classification and K-Means Clustering, to enhance the efficiency of debt collection processes.

## Features

The API AI Collection - Assignment and Campaign offers the following key features:

1. **Predict Assignment**: Predicts the most suitable debt collector for a specific debtor based on various factors. This feature ensures that tasks are assigned to collectors with the highest chances of success.

2. **Predict Campaign**: Predicts the most effective debt collection campaign strategy for a given debtor. This feature optimizes the debt collection process by recommending the most appropriate approach.

## Usage

To use the API AI Collection - Assignment and Campaign, you can make HTTP POST requests to the following endpoints:

1. **Predict Assignment**:
   - Endpoint: `/predict-assignment`
   - Description: Predicts the most suitable debt collector for a given debtor.
   - Request Payload: Provide debtor-related data for prediction.
   - Response: Receive the recommended debt collector.

2. **Predict Campaign**:
   - Endpoint: `/predict-campaign`
   - Description: Predicts the most effective debt collection campaign strategy.
   - Request Payload: Provide debtor-related data for prediction.
   - Response: Receive recommendations for the best campaign strategy.

## Installation

To set up and run the API AI Collection - Assignment and Campaign, follow these steps:

1. Clone the project repository to your local machine:

   ```bash
   git clone https://github.com/your-username/ai-collection-assignment-campaign.git
  ```

2. Create a virtual environment using the following command:
  ```
  python -m venv venv
  ```

3. Activate the created virtual environment:
  ```
  .\venv\Scripts\activate
  ```

4. Upgrade Pip
Ensure that your Pip is up to date. You can check your Pip version using the following command:

```
python -m pip install --upgrade pip
```

5. Install the requirements from requirements.txt:

  ``` 
  pip install -r requirements.txt
  ```

6. Move tp directory project
  ```
  cd .\ai_collection\
  ```

7. To start the Django server, use the following command:

  ```
  python manage.py runserver
  ```

8. To try Predict Assignment feature:
```
http://127.0.0.1:8000/fitur-4/predict-assignment/
```

9. To try Predict Campaign feature:
```
http://127.0.0.1:8000/fitur-4/predict-campaign/
```
