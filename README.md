Rapport Power BI – Analyse des ventes
Présentation

Ce projet présente un **tableau de bord Power BI** réalisé à partir d’un fichier de ventes (`sales_2.csv`).
L’objectif est d’analyser les performances commerciales, le chiffre d’affaires, les commandes (y compris les commandes annulées) et leur répartition par région et par catégorie de produits.

Le rapport a été construit en suivant une démarche complète : préparation des données, modélisation, calculs DAX et création de visuels interactifs.

Préparation et qualité des données

Les données ont été importées dans **Power BI Desktop** via **Power Query**.
Un travail a été effectué sur :

* la vérification des types de données,
* la qualité et la cohérence des colonnes,
* le renommage des champs avec des libellés clairs (clients, produits, régions, commandes…).

Les colonnes ont été nettoyées et harmonisées afin d’assurer une base fiable pour l’analyse.
Modélisation des données

Le modèle repose sur une structure normalisée avec :

* une table **Clients**,
* une table **Produits**,
* une table **Régions**,
* une table **Ventes**.

Les relations entre les tables ont été vérifiées et ajustées pour garantir la cohérence des analyses et des visuels.
Mesures et indicateurs

Plusieurs mesures DAX ont été créées pour suivre les indicateurs clés, notamment :

* le total des ventes,
* le nombre de commandes,
* la quantité vendue,
* la valeur moyenne d’une commande,
* le suivi des commandes annulées (volume, montant et pourcentage).
Tableaux de bord

Le rapport contient **plusieurs onglets** :

* un onglet principal de **suivi des ventes** avec des KPI, des graphiques temporels et des répartitions par région et par catégorie,
* un onglet dédié aux **commandes annulées**, permettant d’analyser leur évolution et leur impact sur le chiffre d’affaires.

Des filtres (dates, statut des commandes, régions), des info-bulles avancées et un menu de navigation facilitent l’exploration des données.
Interface et ergonomie

Un thème personnalisé a été appliqué pour assurer une cohérence visuelle.
Le rapport intègre :

* une navigation par icônes,
* des signets pour filtrer rapidement certaines catégories de produits,
* une version mobile adaptée pour la consultation sur smartphone.
Sécurité et publication

 Fichier du projet
`rapport_vents_video_formation.pbix` : rapport Power BI complet
le fichier `.pbix` doit être ouvert avec **Power BI Desktop** pour consulter le tableau de bord. Quelques images de la réalisation sont disponibles sur le fichier zip réalisation 
