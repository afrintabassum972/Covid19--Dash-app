# 🩺 COVID-19 India Analysis Dashboard

An interactive, real-time web application built to monitor and visualize Coronavirus pandemic data across India. This project is developed using **Python**, **Dash**, and **Plotly**, providing a comprehensive look at case statistics, medical supply availability, and regional zone distributions.

## 🌐 Live Demo
You can access the live dashboard here:
👉 **[Live Project on Render](https://covid19-india-dash-app.onrender.com)**

---

## 📊 Dashboard Preview
![Dashboard Interface](screenshots/Screenshot%202026-03-09%20080214.png)
> *The interface features real-time KPI cards, interactive line charts for medical commodities, case distribution charts, and state-wise comparative analysis.*

## 🚀 Key Features

*   **Real-time KPI Tracking:** Instant summary of **Total**, **Active**, **Recovered**, and **Deceased** cases via color-coded metric cards.
*   **Medical Commodity Analysis:** A dynamic line graph to track the supply and demand of essential items like **Masks**, **Sanitizers**, and **Oxygen**.
*   **Regional Zone Distribution:** A responsive **Donut/Pie Chart** visualizing the ratio of Red, Blue, Green, and Orange zones.
*   **State-wise Case Breakdown:** An interactive **Bar Graph** allowing users to filter and compare data across different Indian states.

## 🛠️ Tech Stack

*   **Language:** Python 3.x
*   **Framework:** [Dash](https://dash.plotly.com) (by Plotly)
*   **Visualization:** Plotly Express & Graph Objects
*   **Data Handling:** Pandas & NumPy
*   **Styling:** Bootstrap (via `dash-bootstrap-components`)
*   **Deployment:** Render

## 📂 Project Structure

```text
├── screenshots/                # Dashboard preview images
├── app.py                      # Main application code
├── state_wise_daily data file IHHPET.csv # Pandemic statistics dataset
├── requirements.txt            # Python dependencies
├── Procfile                    # Deployment configuration for Render
└── README.md                   # Project documentation
