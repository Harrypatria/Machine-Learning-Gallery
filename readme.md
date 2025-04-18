# Laptop Analytics Dashboard

## Overview
This project provides an interactive Streamlit dashboard for comprehensive laptop data analysis with integrated machine learning capabilities. It features exploratory data analysis, price prediction (regression), laptop category classification, and laptop clustering based on specifications.

## Features
- **Interactive Data Exploration**: Dynamic visualizations for analyzing laptop specifications and market trends
- **Price Prediction Model**: ML regression model to predict laptop prices based on specifications
- **Laptop Classification**: Categorize laptops based on their intended use case
- **Laptop Clustering**: Unsupervised learning to identify natural groupings in laptop data
- **Modern UI/UX**: Responsive design with sidebar navigation, interactive filters, and hover effects

## Machine Learning Components
1. **Regression**: Predicting laptop prices based on specifications
2. **Classification**: Categorizing laptops into usage categories (e.g., Gaming, Business, Everyday)
3. **Clustering**: Identifying natural groupings in the laptop market

## Getting Started

### Prerequisites
- Python 3.8+
- pip package manager

### Installation
1. Clone the repository
```bash
git clone https://github.com/yourusername/laptop-analytics-dashboard.git
cd laptop-analytics-dashboard
```

2. Install dependencies
```bash
pip install -r requirements.txt
```

3. Run the application
```bash
streamlit run app.py
```

### Dataset
The dashboard uses a laptop dataset with the following features:
- Company: Laptop manufacturer
- TypeName: Type of laptop
- Ram: RAM in GB
- Weight: Laptop weight in kg
- Price: Laptop price
- TouchScreen: Whether the laptop has a touchscreen (0/1)
- Ips: Whether the laptop has an IPS display (0/1)
- Ppi: Display pixels per inch
- Cpu_brand: CPU manufacturer
- HDD: HDD size in GB
- SSD: SSD size in GB
- Gpu_brand: GPU manufacturer
- Os: Operating system

## Dashboard Sections
1. **Home**: Overview and key metrics
2. **Data Explorer**: Interactive data exploration and filtering
3. **Price Analysis**: Detailed price analysis and prediction
4. **Classification**: Laptop category classification
5. **Clustering**: Laptop clustering analysis

## Technical Implementation
- **Data Processing**: Pandas for data manipulation
- **Machine Learning**: PyCaret for AutoML capabilities
- **Visualization**: Plotly for interactive charts
- **Dashboard**: Streamlit for web application framework
- **Styling**: Custom CSS for modern UI elements

## License
MIT

## Author
Your Name
