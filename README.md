# Project 2: Gold Recovery Prediction

[Notebook project](./3269200a-875b-4222-a958-a0a1e76a80f0.ipynb)

## Objective  
To predict gold recovery rates at the rougher and final stages using machine‑learning pipelines and the sMAPE metric.

Technologies Used  
- Python (pandas, NumPy, scikit‑learn)  
- Visualization (Matplotlib, Seaborn)  
- Modeling (RandomForestRegressor, LightGBM)  
- Environment (Jupyter Notebook, GitHub Actions)

## Key Steps  
1. **Data Loading & Verification**:
   - Loaded train/test/full datasets and validated recovery formulas against ground truth. 
2. **Data Cleaning**:
   - Imputed missing values via time‑based interpolation and backfill.  
3. **Exploratory Analysis**:
   - Visualized Au, Ag, Pb concentration distributions across process stages.  
4. **Feature Engineering**:
   - Aggregated total metal concentrations and removed irrelevant columns. 
5. **Modeling Pipeline**:
   - Built and evaluated a RandomForestRegressor with scaling and sMAPE scoring.  
6. **Hyperparameter Tuning**:
   - Compared multiple configurations (n_estimators, max_depth) to select the best model.

## Results  
Achieved a final sMAPE of ~7.05%, demonstrating robust predictive accuracy for both flotation and purification stages.
