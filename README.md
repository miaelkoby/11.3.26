## Streamlit Dashboard Sample

This repository contains a simple interactive dashboard built with **Streamlit**, **Pandas**, and **Plotly Express**.

The app displays:
- A set of KPI cards (Sales, Revenue, Users, Engagement)
- A line chart showing the selected metric over time
- A data table with the underlying data

### Features

- **Interactive filters**: Choose which metric to visualize from the sidebar.
- **KPI summary**: Top-level metrics for total sales, revenue, users, and average engagement.
- **Responsive layout**: Uses Streamlit's wide layout and column system.

### Installation

1. **Create and activate a virtual environment (optional but recommended)**:

```bash
python -m venv .venv
.venv\Scripts\activate
```

2. **Install dependencies**:

If you already have a `requirements.txt` file:

```bash
pip install -r requirements.txt
```

Otherwise, install the needed packages directly:

```bash
pip install streamlit pandas plotly
```

### Running the App

From the project root (where `dashboard.py` is located), run:

```bash
streamlit run dashboard.py
```

Then open the URL that Streamlit prints in the terminal (usually `http://localhost:8501`).

### Project Structure

- `dashboard.py` – main Streamlit application file.
- `README.md` – project documentation (this file).

### How to Use

- Open the sidebar on the left.
- Select a metric from **"Select Metric"**.
- The line chart and KPIs will update based on the chosen metric.

### License

You can use and modify this example freely for learning or as a starting point for your own dashboards.

