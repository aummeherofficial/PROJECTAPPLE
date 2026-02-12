# Applelytics – Custom Apple Configuration & Order Analytics System

A backend-driven Apple device configuration and analytics system built using **Python, SQLite, Pandas, NumPy, and Matplotlib**.

---

## 📌 Project Overview

Applelytics is a configuration-based ordering system that allows users to customize Apple devices and analyze sales data.

Unlike a simple configuration program, this system integrates:

- **Dynamic pricing logic**
- **Persistent SQLite database storage**
- **Structured order logging**
- **Data analytics and visualization**
- **Google Drive-based permanent database integration**

The project simulates a real-world backend workflow combined with data analytics.

---

## 🛠️ Technologies Used

- **Python**
- **SQLite**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Google Colab**
- **Google Drive Integration**

---

## 🔄 Project Workflow

1. User selects device configuration options (Model, Variant, Storage, Color, Refresh Rate, Accessories)
2. System calculates total price dynamically
3. Order data is stored in a persistent SQLite database
4. Data is retrieved and processed using Pandas
5. Numerical analysis is performed using NumPy
6. Clean dataset is exported to CSV
7. Visualizations are generated for analytical insights

---

## 📊 Key Features

- Dynamic device configuration system
- Automatic pricing engine
- Discount handling logic
- Persistent database storage (Google Drive)
- Revenue and average order value analysis
- Most sold model identification
- Model-wise sales visualization
- Storage preference distribution chart
- Structured CSV report generation
- Beginner-friendly but industry-oriented backend project

---

## 📁 Project Files

- `Applelytics.ipynb` – Main project notebook
- `requirements.txt` – Required Python libraries
- `images/` – Output and visualization screenshots
- `README.md` – Project documentation

> **Note:**  
> Database and CSV files are generated dynamically and stored in Google Drive. They are not included in this repository.

---

## ▶️ How to Run

1. Open the notebook in **Google Colab** or **Jupyter Notebook**
2. Install required libraries (if needed):

```bash
pip install pandas numpy matplotlib
