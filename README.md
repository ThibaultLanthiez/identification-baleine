[:arrow_left: Retour vers le portfolio](https://github.com/ThibaultLanthiez/Portfolio)

# Identification baleine

Voici mon notebook pour le challenge que m'a proposé [SOYHUCE](https://soyhuce.fr/) pour son recrutement de stage.

J'ai eu quatre jours, de lundi à jeudi, pour faire ce challenge. Étant donné que je suis étudiant, j'ai travaillé entre les cours.

L'objectif du projet est d'aider des scientifiques d'un laboratoire de Normandie à identifier les baleines qu'ils rencontrent en mer.

Pour cela, j'ai à ma disposition un [jeu de données](https://www.kaggle.com/c/humpback-whale-identification/overview) composé d'une dizaine de milliers de photos de baleines, chacune identifiée par son id ou le label new_whale si c'est une baleine non indentifiée.

J'ai commencé par analyser le jeu de données et visualiser les photos. Je les ai ensuite mis en forme pour les donner à mon modèle. Mon modèle est un réseau de neurones à convolution, une architecture spécialisée pour la reconnaissance d'images. Enfin, j'ai essayé d'améliorer la performance en développant un modèle en apprentissage par transfert.

Durant ce projet, j'ai utilisé les frameworks suivants :
* Le langage de programmation Python
* Numpy et Pandas pour la manipulation et l'analyse des données
* Matplotlib pour visualiser les photos de baleines
* Tensorflow et Keras pour la création de modèles de machine learning
* Streamlit pour mettre en production le modèle et créer une application web
* Quelques fonctions de Scikit-learn pour redimensionner les images dans mon application

# Code

Voici le code du projet : [notebook](https://github.com/ThibaultLanthiez/identification-baleine/blob/main/Identification%20baleine.ipynb)
