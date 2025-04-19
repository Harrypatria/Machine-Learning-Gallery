# Laptop Price Prediction Dashboard

An end-to-end machine learning application with an interactive Streamlit dashboard for laptop price prediction, classification, and clustering analysis.

## Features

- **Interactive Dashboard**: Modern UI with sidebar navigation, interactive charts, and responsive design
- **Machine Learning Models**: 
  - Price Prediction (Regression)
  - Laptop Category Classification
  - Customer Segment Clustering
- **Data Analysis**: Comprehensive EDA tools with interactive visualizations
- **AutoML**: Powered by PyCaret for automated model training and comparison
- **Model Deployment**: Ready-to-use prediction interface

## Project Structure

```
laptop-price-prediction/
├── app.py                      # Main Streamlit application
├── data/
│   └── laptop_data_cleaned.csv # Dataset
├── models/                     # Directory to save trained models
├── scripts/                    # Python modules for data processing, visualization, etc.
├── components/                 # UI components
├── utils/                      # Utility functions
├── README.md                   # Project documentation
└── requirements.txt            # Dependencies
```

## Installation

1. Clone the repository:
```bash
git clone https://github.com/Harrypatria/Machine-Learning-Gallery.git
cd machine-learning-gallery
```

2. Create a virtual environment (optional but recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Run the application:
```bash
streamlit run app.py
```

## Usage

1. **Data Exploration**: Navigate to the "Data Explorer" section to analyze the dataset with interactive visualizations
2. **Price Prediction**: Use the "Price Prediction" section to predict laptop prices based on specifications
3. **Classification**: Classify laptops into different categories using the "Classification" section
4. **Clustering**: Explore customer segments in the "Clustering" section
5. **Model Training**: Train custom models with different parameters in the "Model Trainer" section

## Data Preprocessing

The following preprocessing steps are applied to the data:
- Handling missing values
- Encoding categorical variables
- Feature scaling
- Feature engineering (new features like processor generation, screen size)
- Outlier detection and handling

## Model Training

The application uses PyCaret's AutoML capabilities for model training:
1. Data splitting (train/test)
2. Model selection and comparison
3. Hyperparameter tuning
4. Model evaluation
5. Model saving for deployment

## Technologies Used

- **Streamlit**: Interactive web application framework
- **PyCaret**: AutoML library for model training
- **Pandas & NumPy**: Data manipulation
- **Plotly & Matplotlib**: Data visualization
- **Scikit-learn**: Machine learning algorithms

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/amazing-feature`
3. Commit your changes: `git commit -m 'Add some amazing feature'`
4. Push to the branch: `git push origin feature/amazing-feature`
5. Open a Pull Request

---

<div align="center">


## 🌟 Support This Project
**Follow me on GitHub**: [![GitHub Follow](https://img.shields.io/github/followers/Harrypatria?style=social)](https://github.com/Harrypatria?tab=followers)
**Star this repository**: [![GitHub Star](https://img.shields.io/github/stars/Harrypatria/SQLite_Advanced_Tutorial_Google_Colab?style=social)](https://github.com/Harrypatria/SQLite_Advanced_Tutorial_Google_Colab/stargazers)
**Connect on LinkedIn**: [![LinkedIn Follow](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/harry-patria/)

Click the buttons above to show your support!

</div>


