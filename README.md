# Online Banking Analytics Project

📊 **End-to-End Online Banking Data Analysis using Python, SQL, and Power BI**

This project demonstrates a complete data pipeline for online banking analytics, including data extraction, transformation, loading (ETL), and visualization. It helps analyze customer registrations, transactions, and trends, providing actionable insights for business decision-making.

---

## Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Setup & Installation](#setup--installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

---

## Project Overview

This project involves:

- Importing raw customer and transaction data from CSV files.
- Cleaning and transforming the data using Python and Pandas.
- Loading transformed data into a MySQL data warehouse (`wh_online_banking`).
- Visualizing data trends and insights with Power BI dashboards.
- Providing insights on customer behavior, transaction trends, and forecasts.

---

## Data Sources

- `customer_joining_info.csv` — customer registration data.
- `customer_transactions.csv` — customer transaction data.
- `wh_online_banking.sql` — SQL script to set up the data warehouse schema.
- `Online Banking Project.pbix` — Power BI dashboard file.

---

## Technologies Used

- **Python** (Pandas, SQLAlchemy, PyMySQL)
- **MySQL / SQL** (Data warehouse and queries)
- **Power BI** (Data visualization)

---

## Project Structure


- **Online Banking Project.ipynb** → Python notebook handling ETL (Extract, Transform, Load).
- **CSV files** → Raw datasets for customers and transactions.
- **wh_online_banking.sql** → Schema and table creation script for MySQL database.
- **Power BI file** → Ready-made dashboard for visualization.

---

## Setup & Installation

1. **Clone the repository**

```bash
git clone https://github.com/Rahulmahala25/Digital-Banking-Project.git
cd Digital-Banking-Project
