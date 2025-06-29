# 📚 GraphQL Java School API

Une API GraphQL simple en Java pour la gestion d'auteurs et de livres, réalisée sans base de données — les données sont simulées via des listes statiques. Ce projet est conçu pour découvrir les concepts fondamentaux de GraphQL avec Java.

## ✨ Fonctionnalités

- 📖 Rechercher tous les livres et auteurs
- 🔍 Trouver un livre ou un auteur par ID
- 🧑‍🏫 Obtenir tous les livres écrits par un auteur
- 🆕 Ajouter dynamiquement de nouveaux auteurs et livres

## 🏗️ Technologies utilisées

- Java 17+
- [GraphQL Java](https://github.com/graphql-java/graphql-java)
- [Spark Java](http://sparkjava.com/)
- Jackson Databind (pour JSON)
- Aucune base de données – simulation via des listes statiques

## 🗂️ Structure du projet

- `entities/` : contient les classes `Author` et `Book`
- `data/` : simule une base de données avec la classe `DataStore`
- `graphQL/` : contient le `GraphQLProvider` qui configure les resolvers
- `Main.java` : lance un serveur léger Spark sur le port `7070`
- `schema.graphqls` : schéma GraphQL définissant types, requêtes et mutations
