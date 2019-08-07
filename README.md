# Apprentissage statistique

Ce projet est un mini challenge d'apprentissage statistique. Il a été réalisé dans le cadre de ma seconde année de master de bioinformatique.<br>
Ce projet a été en binôme avec Christelle Viguier.

## Données

Les niveaux d’expression (normalisés) de 4654 gènes ont été relevés chez 184 patientes souffrant d’un
cancer du sein à un stade précoce. Ils sont collectés dans le fichier *xtrain.txt* (1 ligne=1 gène, 1 colonne= 1 individu). Après une opération chirurgicale, certaines patientes ont fait une rechute (label= + 1), d’autres non (label= -1). Les labels des 184 individus sont reportés dans le fichier *ytrain.txt*.<br>
Le but est de prédire la rechute ou non-rechute de patientes dont les niveau d’expression des mêmes 4654
gènes sont donnés dans le fichier *xtest.txt*.

## Travail demandé

  - Analyse descriptive des données.
  - Implémentation de plusieurs méthodes adaptées vue en cours.
  - Evaluation de la performance des méthodes utilisées.
  - Justification de la meilleure méthode réalisant la meilleure prévision.
