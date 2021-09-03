# P4
# Scoring

Pour accorder un crédit à la consommation, l’entreprise "Pret à dépenser" calcule la probabilité qu’un client le rembourse, ou non. Elle souhaite donc développer un algorithme de scoring pour aider à décider si un prêt peut être accordé à un client.

Pour ce , ce script est une solution de scoring basée sur les historiques des prets.

Après acquisition, exploration, nettoyage et ingeneering, ce script teste un ensemble de modèles d'apprentissage :

régression logistique Ridge et Lasso
Modèle des fôrets aleatoires parallèles avec choix du seuil d'importance des features grace à threshold (RandomForestClassifier)
LightGBM
une fois le meilleur modèle est adopté , on procède à rendre le modèle facilement interprétable.
