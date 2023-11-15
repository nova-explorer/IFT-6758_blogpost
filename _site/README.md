# IFT6758 Blog Post A-09

Blog Post pour le projet de IFT-6758

Serving:
```bash
bundle exec jekyll serve
```
TODO :
- ajuster les marges pour que le texte prenne plus de place.

4 courbes :
  - Les courbes Receiver Operating Characteristic (ROC) et la métrique AUC de la courbe ROC. Incluez une ligne de base de classificateur aléatoire, c'est-à-dire que chaque tir a 50 % de chances d'être un but.
  - Le taux de buts (#buts / (#non_buts + #buts)) comme une fonction du centile de la probabilité de tir donnée par le modèle, c'est-à-dire que si une valeur est au 70e centile, elle est supérieure à 70% des données.
  - La proportion cumulée de buts (pas de tirs) comme une fonction du centile de la probabilité de tir donnée par le modèle,
  - Le diagramme de fiabilité (courbe de calibration). Scikit-learn fournit des fonctionnalités pour créer un diagramme de fiabilité en quelques lignes de code ; consultez l'API CalibrationDisplay (en particulier les méthodes .from_estimator() ou .from_predictions() ) pour plus d'informations.

# Instructions pertinentes pour l'installation
Voir le template: https://github.com/udem-ift6758/blogpost-template
