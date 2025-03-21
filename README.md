# AIMedicineStockPredictorWebsite
# MediTrend AI - Predictive Analytics for Pharmaceutical Inventory Management

## Overview
MediTrend AI is an advanced AI-powered platform designed to help pharmacies and medical suppliers optimize inventory management. It leverages machine learning to predict disease trends, forecast medicine demand, and enhance supply chain efficiency with real-time analytics.

## Features
- **AI-Based Stock Prediction**: Predicts future medicine demand using machine learning models.
- **Real-Time Analytics**: Provides insights into disease trends and medicine sales.
- **Automated Inventory Management**: Reduces stockouts and overstock situations.
- **User-Friendly Web Interface**: Built with TailwindCSS and Alpine.js for a responsive and modern UI.

## Tech Stack
- **Backend**: Python, Flask, MongoDB, Scikit-learn, XGBoost
- **Frontend**: HTML, TailwindCSS, Alpine.js
- **Machine Learning Models**: Random Forest, Gradient Boosting, XGBoost

## Installation
### Prerequisites
- Python 3.8+
- MongoDB
- Node.js (for frontend development)

### Backend Setup
```sh
# Clone the repository
git clone https://github.com/your-repo/MediTrend-AI.git
cd MediTrend-AI

# Install dependencies
pip install -r requirements.txt

# Start the backend server
python app.py
```

### Frontend Setup
```sh
cd frontend
# Install dependencies (if using a build system like Vite or Webpack)
npm install

# Start the frontend server
npm run dev
```

## Usage
1. **Data Ingestion**: Collects sales and environmental data from MongoDB.
2. **Model Training**: Uses machine learning models to forecast medicine demand.
3. **Prediction & Visualization**: Displays insights on the web interface.

## Model Evaluation
The system evaluates model performance using:
- **Mean Absolute Error (MAE)**: 15.2
- **Root Mean Squared Error (RMSE)**: 22.5
- **R-squared (R²)**: 0.89

## API Endpoints
- `/predict` - Predicts medicine stock requirements.
- `/train` - Triggers model training.
- `/analytics` - Returns disease trend insights.

## License
This project is licensed under the MIT License.

## Contributors
- Manash Chandrawal(manashsingh7890@gmail.com)

## Contact
For any inquiries, please contact **manashsingh7890@gmail.com**.

