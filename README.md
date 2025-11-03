# SparkAttriNet
Ce projet consiste à prédire l’attrition des clients en construisant un modèle de classification binaire utilisant PySpark, MLlib, MongoDB et Streamlit.


### 💡  Idée derrière le projet ``SparkAttriNet`` :

Le projet ``SparkAttriNet`` vise à prédire le risque de départ des clients (attrition) dans une banque à l’aide d’un pipeline de machine learning distribué.

L’idée principale est de détecter à l’avance les clients susceptibles de quitter la banque, afin que l’entreprise puisse agir avant qu’ils ne partent — par exemple en leur proposant des offres personnalisées ou un meilleur service.

Pour atteindre cet objectif, le projet combine plusieurs briques technologiques :

- 🧱 Apache Spark (PySpark) : permet de traiter de grands volumes de données clients de manière distribuée et rapide.

- 🧮 MLlib : la bibliothèque de Spark dédiée au machine learning scalable, utilisée pour construire un modèle de classification (ex. : Logistic Regression, Random Forest).

- 🗄️ MongoDB : sert de stockage intermédiaire pour les données nettoyées et prêtes à être utilisées.

- 🌐 Streamlit : fournit une interface web simple et interactive pour tester le modèle et visualiser les résultats en temps réel.

En résumé :

- 🔍 ``SparkAttriNet`` est un système complet qui prend les données clients brutes, les analyse, les nettoie, construit un modèle prédictif distribué et expose une interface de prédiction utilisable par les analystes métier.