# AI_Product_Dashboard

This repository contains the server-side components for an AI product's dashboard. The front-end part of the project has already been implemented, and this repository focuses on setting up the backend using Node.js with Express and Python for AI-related functionality.

## Features

- Set up a Node.js server using Express to serve as the backend for the AI product's dashboard.
- API endpoints to handle tasks:
  - `/api/metrics`: Respond with mock AI model metrics data in JSON format.
  - `/api/predictions`: Respond with simulated AI predictions and actual results for data visualization.
- Data storage: JSON files are used to store and retrieve AI metrics and prediction data.
- Proper error handling and validation for API requests.

## Prerequisites

- Node.js and npm: [Install Node.js](https://nodejs.org/)
- Python: [Install Python](https://www.python.org/)

## Getting Started

1. Clone this repository: https://github.com/sudhanshu9630/AI_Product_Dashboard.git
1. Install the dependencies for the Node.js server: npm install
2. Run the Node.js server: node server.js
3. Install the Python dependencies: pip install -r requirements.txt
4. Run the Python script for AI predictions: python ai_predictions.py
5. Open your browser and navigate to http://localhost:3000 to access the AI product's dashboard.

## API Endpoints
* /api/metrics: Get mock AI model metrics data.
* /api/predictions: Get simulated AI predictions and actual results for data visualization.
  
## Contributing
Contributions are welcome! If you find a bug or want to add new features, please follow these steps:
1. Fork the repository.
1. Create a new branch: git checkout -b feature-name
1. Make your changes and commit them: git commit -m "Add feature"
1. Push to the branch: git push origin feature-name
1. Submit a pull request.
