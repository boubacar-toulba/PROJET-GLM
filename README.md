# PROJET-GLM
Ce rapport montre comment une banque peut utiliser un modèle informatique pour prédire si un prêt sera remboursé ou non. L’idée est simple : si la banque arrive à détecter à l’avance les prêts risqués (qui ne seront pas remboursés), elle peut les refuser et éviter de perdre de l’argent.

Pour cela, on utilise une méthode appelée régression logistique, qui permet de prévoir deux résultats possibles : soit le prêt est bon, soit il est mauvais. Grâce à ce modèle, on peut estimer la probabilité qu’un prêt soit bon. Par exemple, si la probabilité est supérieure à 0,5, on considère que le prêt est bon.

Avec ce système, on arrive à bien identifier 97 % des bons prêts, mais seulement 14 % des mauvais prêts. La précision totale du modèle est d’environ 79 %. Si on change un peu le seuil de probabilité (par exemple, dire qu’un prêt est bon seulement à partir de 0,67), on peut gagner plus d’argent, même si la précision baisse un peu. À ce niveau, la banque arrive à rejeter 43 % des mauvais prêts, ce qui augmente les bénéfices de plus du double.

Le modèle utilisé est simple, facile à comprendre, et basé sur plusieurs caractéristiques du client (comme le revenu, le montant du prêt, etc.). Il peut déjà donner de très bons résultats, mais il peut aussi être amélioré dans le futur avec plus de données ou des techniques plus avancées.

En résumé, utiliser ce type de modèle permet à la banque de mieux choisir à qui prêter de l’argent, de réduire les pertes et d’augmenter fortement ses profits.
