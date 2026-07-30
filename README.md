# CepTFlow: Supermarket Demand Forecasting

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)
![Flask](https://img.shields.io/badge/Flask-Web%20App-green?style=for-the-badge&logo=flask)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?style=for-the-badge&logo=pandas)

CepTFlow is an end-to-end data pipeline and web application engineered specifically for supermarket demand forecasting. By processing massive volumes of historical transactional data, the system generates time-series projections to optimize inventory management and reduce waste.

## 🚀 Key Features

*   **Massive Data Processing:** Capable of ingesting and processing large datasets (10GB+) of raw supermarket transactional data efficiently.
*   **Time-Series Forecasting:** Utilizes advanced machine learning models to generate accurate predictive models for future demand, seasonal spikes, and sales trends.
*   **Interactive Web Dashboard:** A Flask-based frontend featuring interactive JavaScript charting for dynamic data visualization and projection analysis.
*   **Cloud Data Integration:** Architected to pull, clean, and process data directly from modern cloud data warehouses like Snowflake.

## 🛠️ Technology Stack

*   **Backend Application:** Python, Flask
*   **Data Engineering & ETL:** Pandas, NumPy, Snowflake
*   **Machine Learning:** Scikit-Learn, Time-Series Forecasting Libraries
*   **Frontend UI:** HTML5, CSS3, JavaScript (Chart.js / D3.js)

## ⚙️ Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/SaaFazal/CepTFlow.git
   cd CepTFlow
   ```
2. **Create a virtual environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
4. **Run the application:**
   ```bash
   python app.py
   ```
   The application will be available at `http://127.0.0.1:5000/`.

## 📈 Usage
Once the application is running, upload your normalized transactional CSV datasets or connect the Snowflake integration. The dashboard will automatically process the latest data points and render the 30-day forecast projections.
