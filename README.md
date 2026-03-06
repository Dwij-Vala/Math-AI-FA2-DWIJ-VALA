# 📈 Crypto Volatility Visualizer  
### Mathematics for AI-II – Formative Assessment 2

---

# 👤 Student Information

**Name:** Dwij Vala  
**Student ID:** 2505369  
**Course:** Mathematics for AI-II  
**Assessment:** Formative Assessment 2  

---

# 🌐 Live Deployed Application

The application is deployed using **Streamlit Cloud**.

🔗 **Public App Link**

https://crypto-volatility-dwij-vala.streamlit.app/

This interactive dashboard allows users to analyze cryptocurrency volatility and explore simulated market behavior using mathematical models.

---

# 📌 Project Overview

The **Crypto Volatility Visualizer** is an interactive financial analytics dashboard built using **Python, Streamlit, Pandas, and Plotly**.

The application automatically fetches **real-time cryptocurrency market data** using the **CoinGecko API**, allowing users to analyze price trends, market volatility, and trading volume behavior.

The dashboard also includes a **mathematical simulation lab** where users can experiment with sine waves, cosine waves, random noise, and drift models to simulate market volatility patterns.

---

# 🎯 Project Objectives

This project aims to:

- Analyze cryptocurrency price behavior over time
- Visualize market trends using interactive charts
- Calculate financial indicators such as volatility and returns
- Demonstrate mathematical modeling of market movements
- Build a user-friendly dashboard using Streamlit
- Deploy the application publicly using GitHub and Streamlit Cloud

---

# ⚙️ Automatic Data Loading

Unlike many dashboards that require manual dataset uploads, this application **automatically retrieves cryptocurrency data from the CoinGecko API**.

This provides several advantages:

- No dataset files are required in the repository
- The dashboard always loads fresh data
- Deployment is simpler and more reliable
- Users can explore real cryptocurrency price behavior

The API retrieves historical **Bitcoin market data**, including:

- Price history
- Trading volume
- Timestamp data

The application then processes this information to generate additional indicators such as:

- Moving averages
- Volatility measurements
- Daily returns

---

# 📊 Dashboard Features

## 📈 Market Overview Metrics

The dashboard displays key indicators including:

- Current Price
- Average Price
- 7-Day Volatility
- Total Price Change
- Market Trend Detection
- Stability Score

These indicators help users quickly understand overall market conditions.

---

## 📉 Interactive Visualizations

### Price Trend Chart
Shows cryptocurrency price movement over time.

### Moving Averages
Includes:

- 7-Day Moving Average
- 30-Day Moving Average

These help identify long-term trends.

---

### Candlestick Chart
Displays Open, High, Low, and Close price behavior similar to professional trading platforms.

---

### High vs Low Comparison
Shows the price range within each time interval.

---

### Volume Analysis
Displays trading activity using bar charts.

---

### Rolling Volatility
Calculated using a **7-day rolling standard deviation of daily returns**.

This helps measure market instability.

---

### Daily Returns
Shows the percentage change between consecutive price points.

---

### Volume vs Returns Scatter Plot
Helps analyze whether trading activity influences price volatility.

---

# 🧪 Simulation Lab

The Simulation Lab allows users to experiment with mathematical models that simulate financial market behavior.

Users can generate artificial price movements using:

### Pattern Types

- Sine Waves
- Cosine Waves
- Random Noise
- Combined Pattern

---

### Adjustable Parameters

Users can adjust:

**Amplitude**
Controls how large the simulated price swings are.

**Frequency**
Controls how often price fluctuations occur.

**Drift**
Adds a long-term upward or downward trend.

---

### Simulation Outputs

The simulation section includes:

- Simulated price graphs
- Real vs simulated market comparison
- Volatility comparison metrics

This demonstrates how mathematical models can approximate real financial behavior.

---

# 📂 Repository Structure

The project repository contains the following files:

```
crypto-volatility-visualizer
│
├── crypto.py
├── requirements.txt
└── README.md
```

Because the application loads data automatically from the API, **no dataset files are required** in the repository.

---

# 🧰 Technologies Used

| Technology | Purpose |
|------------|---------|
| Python | Core programming language |
| Streamlit | Dashboard framework |
| Pandas | Data manipulation and analysis |
| NumPy | Mathematical calculations |
| Plotly | Interactive charts |
| Requests | API data retrieval |
| GitHub | Version control |
| Streamlit Cloud | Application deployment |

---

# ▶️ Running the Project Locally

### Step 1 — Clone the Repository

```
git clone https://github.com/YOUR_USERNAME/crypto-volatility-visualizer.git
```

---

### Step 2 — Navigate to the Project Folder

```
cd crypto-volatility-visualizer
```

---

### Step 3 — Create a Virtual Environment

```
python -m venv venv
```

Activate environment (PowerShell):

```
.\venv\Scripts\Activate.ps1
```

---

### Step 4 — Install Dependencies

```
pip install -r requirements.txt
```

---

### Step 5 — Run the Streamlit Application

```
streamlit run crypto.py
```

The application will open automatically in your browser.

---

# 🧠 Mathematical Concepts Used

This project demonstrates several mathematical and statistical techniques:

- Sine and cosine wave modeling
- Random noise generation
- Linear drift modeling
- Percentage change calculations
- Rolling standard deviation
- Moving averages
- Volatility measurement

These techniques help simulate and analyze real financial market behavior.

---

# 🎓 Learning Outcomes

This project demonstrates the ability to:

- Work with financial time-series data
- Apply mathematical modeling to market behavior
- Build interactive dashboards
- Visualize complex data effectively
- Deploy applications using modern development tools

---

# 🏁 Final Reflection

The **Crypto Volatility Visualizer** combines mathematical modeling, financial data analysis, and interactive visualization to create an educational tool for exploring cryptocurrency markets.

By integrating real-time data with simulation models, the dashboard demonstrates how mathematical concepts can be applied to understand complex financial systems.
