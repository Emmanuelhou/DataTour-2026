# DataTour-2026
 DataTour 2026 est avant tout une expérience collective où les données deviennent un levier pour innover, connecter et transformer l’Afrique.
# Contexe 
Les services de mobile money occupent une place essentielle dans l’économie numérique africaine. Ils permettent d’envoyer de l’argent, de recevoir des paiements, de régler des factures, d’effectuer des dépôts, des retraits ou des transferts, souvent sans passer par une agence bancaire traditionnelle.
Cette accessibilité a profondément transformé l’inclusion financière. Cependant, cette croissance rapide s’accompagne d’un défi majeur : la fraude. Transactions anormales, comptes compromis, comportements suspects ou tentatives de dissimulation peuvent fragiliser la confiance dans les systèmes financiers numériques. Pour les opérateurs, les fintechs, les banques et les régulateurs, détecter rapidement ces comportements est devenu une priorité absolue.

# Objectif 
Notre mission est de concevoir un modèle de machine learning capable d’estimer la probabilité qu’une transaction mobile money soit frauduleuse. Pour chaque transaction du fichier de test, nous avons prédit une probabilité comprise entre 0 et 1.

# Description des données 
Le jeu de données anonymisé fourni regroupe des transactions mobile money. Il contient un fichier d’entraînement (train.csv avec la cible fraud_flag), un fichier de test (test.csv), un fichier d'exemple de soumission et un notebook de démarrage.
Les données mélangent plusieurs dimensions : des données numériques (montants rescalés, soldes avant/après des comptes initiateurs et destinataires), des données catégorielles (catégorie d'opération anonymisée), ainsi qu'une dimension temporelle simulée (period). Chaque ligne correspond à une transaction unique identifiée par id.

# Lien de la documentation des données
 https://drive.google.com/drive/folders/1qCYYAoCwII2Ed3vuDjFXLlel4f-mYk1u?usp=sharing
