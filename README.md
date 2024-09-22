### House Price Prediction 🏡💸
A machine learning web application that predicts house prices based on various features like area, number of rooms, etc.

## Features
- Predicts house prices based on input features.
- Built using Flask for the web framework and scikit-learn for the prediction model.
- Deployed on Render for live access.

## Softwares and Tools Requirements

1. [Github Account](https://github.com)
2. [RenderAccount](https://render.com/)
3. [VSCodeIDE](https://code.visualstudio.com/)
4. [GitCLI](https://git-scm.com/book/en/v2/Getting-Started-The-Command-Line)

## How to Run Locally

1. Clone the repository:
```
git clone https://github.com/HarshavardhanKurtkoti/House-price-prediction.git
cd House-price-prediction
```

2. Install dependencies:
```
pip install -r requirements.txt
```

3.  Run the application:
```
python app.py
```

4. Open your browser and navigate to http://localhost:5000 to access the app.


## API Usage

To make predictions using the API, send a POST request to /predict_api:
```
POST http://localhost:5000/predict_api
{
    "data": [value1, value2, ..., valueN]
}
```
Where value1, value2, etc., represent the feature values for the house you want to predict.

## Deployment

The application is deployed on Render. Check it out live [here](https://car-price-prediction-xpub.onrender.com/).

## License
This project is licensed under the Apache License 2.0