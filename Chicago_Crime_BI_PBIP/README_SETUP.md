# Chicago Crime BI - Power BI Project (PBIP)
1. Put the 5 Colab CSVs (crime_cleaned, crime_predictions, model_comparison, feature_importance, confusion_matrices) in one folder, e.g. C:\PowerBI\crime_data\
2. Power BI Desktop: File > Open > Chicago_Crime_BI.pbip (enable Preview features: Power BI Project (.pbip) save option, TMDL and PBIR formats).
3. Transform data > Edit parameters > set DataFolder to your CSV folder, keeping the trailing backslash > Close & Apply > Refresh.
Pages: Crime Overview | Battery & Assault Hotspots | Baseline vs Ensemble | Confusion Matrix | Explainability & Predictions
Only Split = Test rows in crime_predictions.csv are out-of-sample.
