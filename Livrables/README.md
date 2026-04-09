notebook.ipynb :

    Préparation/Transformation des données, Entraînement des modèles et comparaison de leur efficacité


best_logistic_regression_model.joblib : 
    
    Modèle optimal issu de mes recherches (cf notebook)


billets.csv : 
    
    Données utilisées pour entraîner le modèle


billets_production.csv, billets_test.csv : 

    Données correctement formatées pour tester le script


authenticate.py :

    Script à exécuter dans le terminal pour tester une liste de billets

Commande pour lancer le script (Attention au format de votre CSV):
    
    python authenticate.py --csv_path chemin/vers/votre_fichier.csv --model_path best_logistic_regression_model.joblib

