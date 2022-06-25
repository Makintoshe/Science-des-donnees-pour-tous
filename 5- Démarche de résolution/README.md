Besoins identifiés : 

1. Feature Engineering (prétraitmeent: nettoyer et compréhension des données) 60 à 70 %
    a. Valeurs manquantes
    b. Valeurs aberrantes (une valeur inhabituelle : ex : taille de 1000 cm)
    c. Valeurs rares (fraude transaction)
    d. Feature Encoding
    e. EDA (Exploratory Data Analysis)
    f. Feature Scaling
    g. Feature Selection
    h. Utiliser une méthode de Réduction de Dimensionnalité (Facultatif)
2. Modélisation (partie IA) 30 % de temps
    a. Contextualiser le problème : classif ? reg ?? detection ? etc.
    b. Selectionner un ensemble de Modeles
    c. Découper les données en Train/Test ou (app/dec)
    d. Gérer le compromis biais-vairance en Répétant jusqu'à l'obtention du (1) meilleur modèle :
    	0. i = 1
    	a. Découper Train et Test en : Train_ et Val ... Test_i
    	b. Validation croisée : Recherche des hyperparamètres avec Train_ et Val
    	c. configurer les modèles avec les HypParmas
    	d. Entrainer le modèle avec les Train
    	e. Evaluation: Prédire à l'aide des modèle obtenus en (d) et des Test_i
    	f. Selectionner le(s) meilleur(s) modèle(s) à l'aide des métrics
4. Conclure
5. Explicabilité (facultatif)

