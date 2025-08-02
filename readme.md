
# EV-ADOPTION-FORECASTING

A data-driven project to predict the adoption trends of electric vehicles (EVs). This repository contains code, data, and pre-trained models for forecasting future EV adoption based on historical vehicle population data.

## Project Structure

| File/Folder | Description |
| :-- | :-- |
| `CODE.ipynb` | Code and analysis notebook |
| `EV_Adoption_Forecasting.ipynb` | Main notebook for EV adoption forecasting workflow |
| `Electric_Vehicle_Population_By_County.csv` | Raw dataset of EV populations by county |
| `preprocessed_ev_data.csv` | Data file after preprocessing and cleaning |
| `forecasting_ev_model.pkl` | Serialized trained model for EV adoption forecasting |
| `app.py` | Web/Flask app to serve predictions (demo interface) |
| `ev-car-factory.jpg` | Image file used for visualization or presentation |
| `README.md` | This file |

## Getting Started

### Prerequisites

- Python 3.7+
- Recommended:
    - pandas
    - numpy
    - scikit-learn
    - flask
    - jupyter notebook

Install requirements (if a `requirements.txt` exists):

```bash
pip install -r requirements.txt
```


### How to Use

1. **Data Exploration \& Preprocessing**
Open `CODE.ipynb` or `EV_Adoption_Forecasting.ipynb` to review data cleaning, feature engineering, and exploratory analysis steps.
2. **Model Training**
Use `EV_Adoption_Forecasting.ipynb` to train models and evaluate results. The script saves the best trained model as `forecasting_ev_model.pkl`.
3. **Web App Demo**
Run `app.py` to launch a local server and interact with the EV adoption forecasting model.

```bash
python app.py
```

4. **Preprocessed Data**
Use `preprocessed_ev_data.csv` if you want to skip raw data cleaning.

## Data

- **Source:** `Electric_Vehicle_Population_By_County.csv`
Contains historic data of EV registrations by county.
- **Preprocessed File:** `preprocessed_ev_data.csv` contains cleaned and feature-engineered data ready for training.


## Model

- **File:** `forecasting_ev_model.pkl`
This is the trained machine learning model used for predicting future EV adoption trends.


## Results

See the provided Jupyter notebooks for EDA, forecasting plots, and evaluation metrics.
<img width="1887" height="1036" alt="Screenshot 2025-08-02 211149" src="https://github.com/user-attachments/assets/5959cfc1-680d-44ed-8292-346bb754f514" />


<img width="1875" height="1034" alt="Screenshot 2025-08-02 211236" src="https://github.com/user-attachments/assets/12c6b7a3-eb2b-4d11-9f00-9a0bff20b16c" />


<img width="1882" height="1043" alt="Screenshot 2025-08-02 211308" src="https://github.com/user-attachments/assets/bd82f2cc-87c8-476f-b786-b529427aa2bd" />



<img width="1860" height="1032" alt="Screenshot 2025-08-02 211340" src="https://github.com/user-attachments/assets/dff3186e-9022-4822-a4cf-055755cc64da" />





## Image

`ev-car-factory.jpg` is available for use in reports/presentations related to the project.

## Contributing

Contributions are welcome! Please raise an issue or submit a pull request.

## License

Specify license here if applicable (e.g. MIT).

Feel free to update details such as model types, specific usage instructions, and credits as needed!

<div style="text-align: center">⁂</div>

[^1]: image.jpg

