# 🎬 Analyse de Données de Films - Dashboard Power BI

## 📌 Contexte

Ce projet vise à explorer et analyser un jeu de données extrait de la base TMDB (The Movie Database), contenant des informations détaillées sur plusieurs milliers de films : titres, genres, dates de sortie, budgets, revenus, popularité, et plus encore.

L'objectif principal est de créer un **dashboard Power BI interactif** permettant d'extraire des insights pertinents sur l'industrie cinématographique.

---

## 🎯 Objectifs de l'analyse

L’analyse s’articule autour de plusieurs questions clés :

- Quels sont les films les plus rentables ?
- Quels genres de films génèrent le plus de revenus ?
- Y a-t-il une corrélation entre le budget et le revenu d’un film ?
- Quelle est l’évolution de la production cinématographique dans le temps ?
- Quelles années ont connu le plus de succès en termes de revenus ?

---

## 🧽 Nettoyage et préparation des données

Le nettoyage a été réalisé via **Power Query**, avec les étapes suivantes :

- Suppression des lignes avec des **valeurs manquantes ou nulles** dans les colonnes clés (`budget`, `revenue`, etc.)
- Suppression des doublons
- Filtrage des films dont le `budget` ou le `revenue` est égal à 0
- Conversion des colonnes `release_date` en format Date
- Séparation et normalisation des genres (lorsqu’ils sont combinés dans une seule cellule)

---

## 📊 Choix des visualisations

Une attention particulière a été portée à la **pertinence des visuels** pour répondre aux questions posées :

- 🔹 **Graphiques en barres** : pour comparer les revenus et les budgets par genre ou par film
- 🔹 **Histogrammes** : pour visualiser la distribution des budgets ou des notes moyennes (`vote_average`)
- 🔹 **Graphiques en courbes** : pour suivre l’évolution de la production ou des revenus au fil du temps
- 🔹 **Treemaps** : pour mettre en avant les genres de films les plus représentés
- 🔹 **Filtres interactifs (slicers)** : pour explorer les résultats par année, genre, score, etc.

Chaque visuel a été conçu pour **aider la prise de décision** en rendant les données digestes et interactives.

---

## 📈 Résultats obtenus

Le dashboard met en lumière plusieurs faits intéressants :

- Les genres **Action** et **Aventure** dominent en termes de revenus globaux.
- Certains films à **budget modéré** peuvent générer des revenus exceptionnels.
- Une corrélation existe entre **budget élevé** et **grands succès commerciaux**, mais ce n’est pas systématique.
- L’industrie a connu un **pic de production** dans les années 2000-2010.

---

## ✅ Conclusion

Ce projet démontre comment un dataset brut peut être transformé en un **outil d’analyse puissant** grâce à Power BI. En adoptant une démarche de Data Analyst — poser des questions, nettoyer les données, choisir les bons visuels — nous avons pu extraire des insights pertinents pour comprendre les tendances du cinéma.

---

## 📁 Fichiers inclus

- `rapport_movies.pbix` → Fichier Power BI
- rapport_movies.pdf` → dashboard
- `tmdb-movies.csv` → Données sources
- `README.md` → Présentation du projet

---

## ✨ Auteur

Réalisé par **[Kouadio Abel Bekantié]** – Passionné par la data, l’analyse visuelle et l’extraction d’insights à valeur ajoutée.

