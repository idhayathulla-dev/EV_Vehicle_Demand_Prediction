# EV_Vehicle_Demand_Prediction

A data science project focused on analyzing and forecasting electric vehicle (EV) adoption at the county level across the United States. This repository demonstrates end-to-end data analysis, preprocessing, visualization, and baseline forecasting models.

**Context:**  
This project was developed purely for learning purposes as part of an **AICTE Internship**, following standard industry data science workflows.

---

## Project Overview

Electric vehicle adoption is growing rapidly, but adoption rates vary significantly across regions. This project aims to:

- Analyze county-level EV adoption data
- Clean and preprocess real-world datasets
- Visualize temporal and geographic trends
- Build baseline forecasting models for EV demand
- Evaluate model performance using standard metrics

This is a learning-focused project, not a production deployment.

---

## Repository Structure

.
├── app.py
├── EV_Adoption_Forecasting.ipynb
├── Electric_Vehicle_Population_By_County.csv
├── preprocessed_ev_data.csv
├── requirements.txt
└── README.md


---

## Files Description

- `app.py` – Simple demonstration script to load data and run a sample workflow  
- `EV_Adoption_Forecasting.ipynb` – Main notebook containing EDA, modeling, and evaluation  
- `Electric_Vehicle_Population_By_County.csv` – Raw county-level EV population dataset  
- `preprocessed_ev_data.csv` – Cleaned and feature-engineered dataset  
- `requirements.txt` – Python dependencies  

---

## Requirements & Setup

### Prerequisites
- Python 3.8+
- Git

### Installation

```bash
git clone <repository-url>
cd ev-vehicle-demand-prediction

python -m venv .venv
.venv\Scripts\activate   # Windows
# source .venv/bin/activate  # macOS/Linux

pip install --upgrade pip
pip install -r requirements.txt
Usage
Run the Jupyter Notebook
jupyter notebook EV_Adoption_Forecasting.ipynb
The notebook includes:

Data loading and preprocessing

Exploratory data analysis

Feature engineering

Model training

Forecast evaluation (MAE, RMSE)

Run the Demo Script
python app.py
Dataset
Electric_Vehicle_Population_By_County.csv
Raw EV population counts aggregated at the U.S. county level.

preprocessed_ev_data.csv
Cleaned dataset used directly for modeling.

Any additional data sources should be properly documented if added.

Results
Baseline regression and time-series models implemented

Model performance evaluated using MAE and RMSE

Clear regional differences observed in EV adoption trends

Detailed analysis and visualizations are available in the notebook.

Contributing
This repository is primarily for learning, but contributions are welcome.

Suggested improvements:

Advanced forecasting models

Better feature engineering

Cross-validation and tuning

Documentation enhancements

Please open an issue before making major changes.

License
This project is intended for educational and learning purposes.

Acknowledgements
Developed as part of a learning internship under AICTE, focusing on practical data science and machine learning fundamentals.
