# 🩺 Coronavirus Pandemic Analysis Dashboard

Yeh ek interactive web application hai jo India mein COVID-19 ke data ko monitor karne ke liye banaya gaya hai. Ise **Python**, **Dash**, aur **Plotly** ka upyog karke banaya gaya hai.

## 📊 Dashboard Preview
![Dashboard Screenshot](screenshots/Screenshot%202026-03-09%20080214.png)
> Interface featuring real-time KPI cards, Commodities line charts, Case distribution pie charts, and State-wise analysis.

## 🚀 Key Features (As per Code)

*   **Real-time KPI Cards:** Dashboard ke top par Total, Active, Recovered, aur Deaths ka live count dikhta hai.
*   **Commodities Total Count:** Ek interactive line graph jo **Mask**, **Sanitizer**, aur **Oxygen** ki supply ko track karta hai.
*   **Zone Distribution:** Ek dynamic **Pie Chart** jo Status ke hisaab se Red, Blue, Green, aur Orange zones ka ratio dikhata hai.
*   **State Total Count:** Ek descriptive **Bar Graph** jo har state ke confirmed, recovered, aur deceased cases ka comparison dikhata hai.

## 🛠️ Tech Stack
*   **Language:** Python
*   **Libraries:** 
    *   `Pandas`: Data manipulation ke liye.
    *   `Plotly & Dash`: Interactive charts aur web layout ke liye.
    *   `Dash Bootstrap Components`: Responsive design ke liye.

## 📂 Dataset Insight
*   **File Name:** `state_wise_daily data file IHHPET.csv`
*   **Key Columns:** State, Status (Confirmed/Recovered/Deceased), Hospitalized, Medical Supplies (Mask/Oxygen), aur Zone Data.

## ⚙️ How to Run this Project?

1.  **Repository Clone Karein:**
    ```bash
    git clone https://github.com
    cd covid19-india-dash-app
    ```

2.  **Dependencies Install Karein:**
    ```bash
    pip install -r requirements.txt
    ```

3.  **App Run Karein:**
    ```bash
    python app.py
    ```
    Iske baad apne browser mein `http://127.0.0.1` open karein.
