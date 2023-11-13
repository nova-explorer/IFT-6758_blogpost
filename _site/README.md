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
  - 3
    - 3.4
      - lien comet.ml pour train=distance
      - lien comet.ml pour train=angle
      - lien comet.ml pour train=distance & angle
  - 5
      - inclure figures pour justifier choix HP
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
