# AgriUrea – Granular Urea Fertilizer Price Forecasting

## Internship Project – DNEXT Intelligence SA (June 2025 – July 2025)

### Project Overview

During my internship at **DNEXT Intelligence SA**, I developed **AgriUrea**, a web-based forecasting application designed to provide **daily price predictions for granular urea fertilizer in the Middle East**. The application focuses on short-term forecasts (next **14 days**) while earlier experimentation covered extended horizons (14 days, 1 month, and 1 year) during the model evaluation phase.

### Key Contributions

* **Data Preprocessing & Quality Control**: Processed and validated over **6,600 rows of historical daily market data (2007–2025)** including urea, Brent crude, TTF gas, corn, wheat, and precipitation, ensuring robustness and consistency.
* **Experimentation Phase**: Benchmarked multiple forecasting approaches:

  * **Statistical models**: Prophet.
  * **Machine Learning models**: CatBoost, LightGBM, XGBoost.
  * **Deep Learning models**: LSTM, BiLSTM, Transformer Encoder.
  * Conducted forecasts for **14 days, 1 month, and 1 year (daily resolution)** to evaluate performance across horizons.
* **Application Development**: Built a scalable pipeline with:

  * **Frontend**: React.js with Tailwind CSS for interactive visualization.
  * **Backend**: FastAPI for model inference and data processing.
  * **Visualization**: Displaying historical prices, 14-day forecasts, and key influencing factors.
* **Model Deployment**: Integrated two high-performing models (**LightGBM and BiLSTM**) into the app, achieving **\~0.97 R²**, ensuring high forecast reliability.
* **Feature Importance Analysis**: Identified major price drivers such as energy costs, precipitation patterns, seasonal demand, and trade policies.
* **Collaboration**: Worked with my **Tunisia-based supervisor** and the **Head of Fertilizer Analysis (Switzerland)** to align model outputs with market intelligence and trading practices.

### Value Added

This project demonstrates how **AI and advanced analytics can enhance decision-making in the fertilizer market** by:

* Supporting farmers, traders, and policymakers with **short-term actionable insights**.
* Reducing uncertainty in procurement, sales, and investment strategies.
* Establishing a **repeatable and extensible pipeline** for future forecasting improvements.

---

**Skills & Tools**: Time Series Analysis, Statistical Modeling, Machine Learning, Deep Learning, Data Preprocessing, React.js, FastAPI, Python (NumPy, Pandas, Scikit-learn, TensorFlow/Keras), Tailwind CSS, Data Visualization.
