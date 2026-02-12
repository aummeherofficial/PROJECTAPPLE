Applelytics

Custom Apple Configuration & Order Analytics System


1️⃣ Project Overview

Applelytics is a Python-based backend system that simulates a configurable Apple device ordering platform integrated with a data analytics engine.

The system:
Collects structured user configuration inputs
Calculates dynamic pricing
Stores order data in a persistent SQLite database
Performs analytical reporting using Pandas and NumPy
Generates visual insights using Matplotlib
This project demonstrates backend logic integration with data analytics workflows.

2️⃣ Core Functionalities

🔹 Device Configuration Module
Model selection
Variant selection
Storage configuration
Color selection
Refresh rate selection (60Hz / 120Hz)
Accessory integration
Dynamic total price calculation
Discount handling


🔹 Data Persistence Layer

SQLite database integration
Google Drive permanent storage
Automatic table creation (CREATE TABLE IF NOT EXISTS)
Structured order logging
CSV export support

🔹 Analytics Engine

Total Revenue calculation
Average Order Value computation
Most Sold Model identification
Model-wise Sales Distribution (Bar Chart)
Storage Preference Distribution (Pie Chart)

3️⃣ Tech Stack

Python
SQLite
Pandas
NumPy
Matplotlib
Google Colab
Google Drive Integration

4️⃣ System Workflow

User Input
Configuration Validation
Dynamic Pricing Calculation
Database Storage
Data Retrieval
Analytical Processing
Visualization Output

5️⃣ Database Structure
The SQLite database stores the following structured fields:
Date
Model
Variant
Storage
Color
Refresh Rate
Accessories
Discount
Final Price

Note:
Database and CSV files are runtime-generated and stored in Google Drive. They are not included in this repository.


6️⃣ Key Learning Outcomes

This project strengthened understanding of:
Modular function design
Backend logic structuring
Persistent data storage
SQL integration within Python
Data manipulation using Pandas
Numerical computation using NumPy
Professional data visualization practices
