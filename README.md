# Fake-bills-detector
Trained a model to authenticate banknotes

authenticate.py :
  Final script to run in terminal
    Command :
      python votre_script.py --csv_path chemin/vers/votre_fichier.csv 
      --model_path chemin/vers/votre_modele.joblib
    Warning : CSV needs to have the correct layout

best_logistic_regression_model.joblib :
  Best model identified through notebook work, to use with authenticate

billets.csv :
  Data used for model training

billets_production.csv, billets_test.csv :
  Data used for model testing

notebook.ipynb :
  Data Preparation/Transformation
  Model Training
  Model Optimization

presentation.odp :
  PowerPoint presentation of the work
  
