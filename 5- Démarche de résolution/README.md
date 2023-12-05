Tâches identifiées : 

1. Feature Engineering (prétraitement: nettoyer et compréhension des données) 60 à 70 % de temps

    a. Valeurs manquantes

    b. Valeurs aberrantes (une valeur inhabituelle : ex : taille de 1000 cm)

    c. Valeurs rares (fraude transaction)

    d. Feature Encoding

    e. EDA (Exploratory Data Analysis)

    f. Feature Scaling

    g. Feature Selection

    h. Utiliser une méthode de Réduction de Dimensionnalité (Facultatif)

## 2. Méthodologie Pratique pour Comparer Plusieurs Algorithmes d'Apprentissage

**Méthodologie :**
1. Choisissez une métrique de performance pertinente \(R\).
2. Pour chaque jeu de données \(D_j\):
   - Effectuez \(k\) divisions des données \(D_{j,\text{app}k} / D_{j,\text{test}k}\).
   - Pour chaque algorithme d'apprentissage \(A_i\):
     - Déterminez les meilleurs hyperparamètres en utilisant la fonction `Selection`.
     - Entraînez le modèle \(h_{i,j,k}\) avec \(D_{j,\text{app}k}\).
     - Évaluez sa performance \(R_{i,j,k}\) sur \(D_{j,\text{test}k}\).
   - Calculez la performance moyenne \(R_{i,j}\).
   - 
3. Comparez les performances sur chaque jeu de données et/ou globalement à l'aide d'un test de significativité statistique.

4. Conclure

5. Explicabilité (facultatif)

