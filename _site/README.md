# IFT6758 Blog Post A-09

Blog Post pour le projet de IFT-6758

Serving:
```bash
bundle exec jekyll serve
```
TODO :
- mettre des abbréviations pour les 4 courbes?
- ajuster les marges pour que le texte prenne plus de place.

4 courbes :
  - Les courbes Receiver Operating Characteristic (ROC) et la métrique AUC de la courbe ROC. Incluez une ligne de base de classificateur aléatoire, c'est-à-dire que chaque tir a 50 % de chances d'être un but.
  - Le taux de buts (#buts / (#non_buts + #buts)) comme une fonction du centile de la probabilité de tir donnée par le modèle, c'est-à-dire que si une valeur est au 70e centile, elle est supérieure à 70% des données.
  - La proportion cumulée de buts (pas de tirs) comme une fonction du centile de la probabilité de tir donnée par le modèle,
  - Le diagramme de fiabilité (courbe de calibration). Scikit-learn fournit des fonctionnalités pour créer un diagramme de fiabilité en quelques lignes de code ; consultez l'API CalibrationDisplay (en particulier les méthodes .from_estimator() ou .from_predictions() ) pour plus d'informations.

TODO - Questions:
  - 2
    - 2.1
      -	histogramme nombre buts et non-buts, séparés, regroupés par distance
      - histogramme nombre buts et non-buts, séparés, regroupés par angle
      -	histogramme 2D distance vs angle. Pas besoin de séparer les buts et les non-buts.
      - Discuter.
    - 2.2
      - figure taux de buts vs distance
      - figure taux de buts vs angle
      - Discuter.
    - 2.3
      - histogramme nombre buts nets vides et non-vides, séparés, classés (regroupés ?) par distance
      - Incluez ce chiffre dans votre article de blog et discutez de vos observations
      - Pouvez-vous trouver des événements qui ont des caractéristiques incorrectes (par exemple, de mauvaises coordonnées x/y) ? Si oui, prouvez qu'un événement a des caractéristiques incorrectes.
  - 3
    - 3.1
      - Discuter prédictions et problème potentiel
      - (peut-être intéressant de mettre un graphe de notre régression?)
    - 3.3
      - 4 courbes sur train=distance
      - 4 courbes sur train=angle
      - 4 courbes sur train=distance & angle
      - 4 courbes pour ligne de base aléatoire
    - 3.4
      - lien comet.ml pour train=distance
      - lien comet.ml pour train=angle
      - lien comet.ml pour train=distance & angle
  - 4
    - 4.5
      - liste des caracs crées
      - répertorier par nom de colonne
      - répertorier par explication
      - lien comet.ml
  - 5
    - 4 courbes pour XGBoost train=distance & angle
    - 4 courbes pour XGBoost train=caracs S4 et ajustage des HP
    - 4 courbes pour 5.3 meilleur modèle
    - 5.1
      - Discuter config train/validation et comparer avec régression logistique
      - lien comet.ml
    - 5.2
      - Discuter choix HP
      - inclure figures pour justifier choix HP
      - Comparer avec XGBoost 5.1
      - lien comet.ml
    - 5.3
      - Discuter stratégies de sélection de caractéristiques essayées et ensemble de caractéristiques optimal
      - Inclure figures pour justifier
      - Comparer meilleur modèle avec XGBoost 5.1
      - lien comet.ml
  - 6
    - 6.1
      - Discuter techniques et méthodes essayées
      - 4 courbes
      - mettre en évidence le meilleur modèle (final)
    - 6.2
      - lien comet.ml
  - 7
    - 7.1
      - En utilisant le test = saison regulière 2019/2020
      - 4 courbes pour régression logistique train = distance (S3.3)
      - 4 courbes pour régression logistique train = angle (S3.3)
      - 4 courbes pour régression logistique train = distance & angle (S3.3)
      - 4 courbes pour meilleur XGBoost (S5.3)
      - 4 courbes pour modèle final (S6.1)
      - Discuter résultats et observations
      - performance test vs train
      - Est-ce que des modèles fonctionnent plus ou moins bien que prévu
    - 7.2
      - En utilisant le test = saison éliminatoire 2019/2020
      - 4 courbes pour régression logistique train = distance (S3.3)
      - 4 courbes pour régression logistique train = angle (S3.3)
      - 4 courbes pour régression logistique train = distance & angle (S3.3)
      - 4 courbes pour meilleur XGBoost (S5.3)
      - 4 courbes pour modèle final (S6.1)
      - Discuter résultats et observations
      - Différence par rapport à saison régulière

# Instructions pertinentes pour l'installation
Voir le template: https://github.com/udem-ift6758/blogpost-template
