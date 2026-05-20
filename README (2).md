# 🧴 Smart Sales & Demand Forecasting System

A lightweight, ML-assisted web application for analyzing sales data and predicting demand levels — built with Python and Streamlit.

---

## 📌 Overview

The Smart Sales & Demand Forecasting System lets you upload historical sales data, explore key statistics, visualize trends, and classify demand levels — all through a simple, interactive web interface. It uses the **pen Sales Dataset** as its data source.

---

## 🚀 Features

- 📂 Upload your own CSV sales data
- 📊 Instant dataset preview and summary statistics
- 📉 Interactive sales trend visualization
- 🔮 Demand level prediction based on monthly sales input (Low / Medium / High)

---

## 🛠️ Tech Stack

| Layer       | Technology        |
|-------------|-------------------|
| Language    | Python 3.x        |
| Web Framework | Streamlit       |
| Data Handling | Pandas          |

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/karthik-/Smart-Sales-forecasting-system.git
cd Smart-Sales-forecasting-system
```

### 2. Install dependencies

```bash
pip install streamlit pandas
```

### 3. Run the app

```bash
streamlit run app.py
```

The app will open in your browser at `http://localhost:8501`.

---

## 📖 Usage

1. **Launch the app** using the command above.
2. **Upload** the `pen_sales_300.csv` file using the file uploader.
3. **Explore** the dataset preview and sales statistics.
4. **Enter a sales value** in the prediction input to get a demand level forecast.
5. **View the trend chart** for a visual overview of sales over time.

### Demand Level Classification

| Sales Range      | Demand Level  |
|------------------|---------------|
| Below 1,500      | 🔴 Low Demand  |
| 1,500 – 2,999    | 🟡 Medium Demand |
| 3,000 and above  | 🟢 High Demand  |

---

## 📁 Project Structure

```
Smart-Sales-forecasting-system/
│
└── app.py          # Main Streamlit application
```

---

## 🙋‍♀️ Author

**karthiknayaka** — [@karthiknayaka](https://github.com/karthiknayaka)
