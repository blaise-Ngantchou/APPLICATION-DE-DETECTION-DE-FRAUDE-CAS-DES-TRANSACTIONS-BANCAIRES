# APPLICATION-DE-DETECTION-DE-FRAUDE-CAS-DES-TRANSACTIONS-BANCAIRES

🎯 But du projet :
Avec l’augmentation des transactions numériques, la détection précoce des fraudes est devenue un enjeu crucial pour les entreprises. Ce projet a donc pour objectif de développer un modèle de machine learning capable de détecter automatiquement les transactions bancaires frauduleuses.

🔍 Principe du projet :
• Construire un modèle de classification distinguant transactions légitimes et frauduleuses.
• Tester différentes stratégies de prétraitement et d’ingénierie des caractéristiques.
• Optimiser les modèles afin d’améliorer la précision, le rappel et la capacité de détection.

🛠 Outils & Technologies :
• Python (Pandas, Scikit-learn, Matplotlib)
• Modèles : Random Forest, SVM, Logistic Regression
• Dataset Kaggle “Credit Card Fraud Detection”
• Streamlit

📊 Méthodologie :
• Prétraitement des données : nettoyage, normalisation, gestion du déséquilibre.
• Ingénierie des features : création de nouvelles variables pour renforcer la séparation des classes.
• Construction des modèles : entraînement et comparaison de plusieurs algorithmes de classification adaptés aux données déséquilibrées.
• Évaluation et optimisation : analyse des performances via précision, rappel, F1-score, AUC-ROC ; optimisation des hyperparamètres ; utilisation de techniques de rééquilibrage (oversampling).

📈 Résultats obtenus :
• Modèle robuste avec environ 94 % de précision.
• Amélioration significative de la détection des transactions frauduleuses tout en minimisant les faux positifs.
• Meilleure compréhension des variables clés influençant la fraude.

💻 Application associée :
Une application Streamlit a été développée en parallèle pour :
• visualiser les données et les indicateurs clés ;
• tester le modèle directement via une interface simple ;
• simuler la prédiction d’une transaction en temps réel.
