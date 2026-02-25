# Healthcare Operations Intelligence Dashboard

A Streamlit-based dashboard for analyzing healthcare operations, patient demographics, clinical trends, operational efficiency, and staffing optimization.

---

## Overview

The Healthcare Operations Intelligence Dashboard provides a comprehensive analytical platform for hospital management and decision-makers. It integrates operational, clinical, and staffing data into a unified interactive system that enables data-driven healthcare management.

The dashboard focuses on performance monitoring, patient demand analysis, capacity planning, and workforce optimization.

---

## Features

- Executive Overview with key KPIs
- Patient Demographics and Demand Analysis
- Clinical and Disease Intelligence
- Operational Efficiency and Capacity Tracking
- Staffing and Resource Optimization
- Global filters (date, department, demographics)
- Dark and Light theme toggle
- Performance optimization using caching
- Operational alerts system
- Patient journey timeline visualization
- Capacity planning simulator
- PDF export for selected dashboard views

---

## Tech Stack

- Python
- Streamlit
- Pandas
- Plotly

---

## Project Structure

```
├── app.py
├── myPages/
│   ├── page1.py
│   ├── page2.py
│   ├── page3.py
│   ├── page4.py
│   ├── page5.py
│   └── page6.py
├── data/
│   └── dataFinal.xlsx
├── .streamlit/
│   └── config.toml
├── Agile_document/
│   └── Niyati_agile_document.xls
├── .gitignore
└── README.md
```

---

## How to Run Locally

### 1. Create and activate a virtual environment (Optional but recommended)

```
python -m venv venv
```

**Windows**

```
venv\Scripts\activate
```

**macOS/Linux**

```
source venv/bin/activate
```

---

### 2. Install dependencies

```
pip install -r requirements.txt
```

---

### 3. Run the application

```
streamlit run app.py
```

---

## Data

Dataset used:

```
data/dataFinal.xlsx
```

Ensure the dataset file is present inside the `data/` folder before running the application.

---

## Documentation

Agile documentation including:
- Product backlog
- Sprint backlog
- Task tracking
- Impediments log
- Sprint retrospectives

Available at:

```
Agile_document/Niyati_agile_document.xls
```

---

## Contributors

Group Project (Internship)

Individual contributions are tracked through Agile documentation.

---

## Notes

- The `venv/` folder and cache files are excluded from the repository.
- `.streamlit/config.toml` is included to maintain consistent UI and theme configuration across environments.

---

## Publishing README

After updating this file:

```
git add README.md
git commit -m "Update README with project overview and setup"
git push
```
