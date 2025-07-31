# 📊 DataCans - Data Analytics Platform

A powerful, user-friendly web application built with Streamlit for comprehensive data analysis and cleaning. Upload your CSV/Excel files and get instant insights with automated data cleaning, profiling, and visualization.

---

## 🚀 Features

- **Smart Data Upload:** Support for CSV and Excel files  
- **Automated Data Cleaning:**  
  - Missing value detection and handling  
  - KNN Imputation for intelligent data filling  
  - Data type optimization  
- **AI-Powered Profiling:** Generate comprehensive data reports using ydata-profiling  
- **Interactive Visualizations:** Dynamic charts and graphs with Plotly  
- **Export Capabilities:** Download cleaned data as Excel files  
- **Bilingual Interface:** Arabic and English support  

---

## 🛠️ Tech Stack

- **Frontend:** Streamlit  
- **Data Processing:** Pandas, NumPy  
- **Machine Learning:** Scikit-learn (KNN Imputation)  
- **Visualization:** Plotly  
- **Profiling:** ydata-profiling  
- **Export:** OpenPyXL  

---

## 📁 Project Structure

datacans-analytics/
├── app.py # Main Streamlit application
├── src/
│ ├── init.py
│ ├── data_processor.py # Data cleaning and preprocessing
│ ├── analytics.py # Analytics and insights generation
│ └── utils.py # Utility functions
├── requirements.txt # Python dependencies
├── config.py # Configuration settings
├── .streamlit/
│ └── config.toml # Streamlit configuration
├── assets/
│ └── screenshots/ # Application screenshots
├── tests/
│ ├── init.py
│ ├── test_data_processor.py
│ └── test_analytics.py
├── sample_data/
│ └── sample.csv # Sample dataset for testing
├── .gitignore
├── LICENSE
└── README.md


---

## 🚀 Quick Start

### Prerequisites

- Python 3.8 or higher  
- pip package manager  

### Installation

```bash
git clone https://github.com/yourusername/datacans-analytics.git
cd datacans-analytics

python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

pip install -r requirements.txt

streamlit run app.py
Open your browser and navigate to http://localhost:8501
