# 🐾 PetFriends – Application JavaFX de gestion et commande de produits pour animaux

## 📖 Description du projet

**PetFriends** est une application de bureau développée avec **JavaFX** permettant aux utilisateurs de :
- Commander des produits destinés aux animaux de compagnie  
- Consulter les offres promotionnelles
- Publier et consulter des avis (ratings) 
- Gérer les informations utilisateurs 

L’application offre une interface graphique intuitive et moderne permettant d’interagir avec la base de données (ajout, modification, suppression et consultation des données).

Ce projet a été réalisé dans le cadre d’un **mini-projet académique**, afin de maîtriser les concepts de développement d’applications de bureau en **JavaFX** et la manipulation des données via **JDBC/MySQL**.

---

## ⚙️ Technologies utilisées

- ☕ **Java 17**  
- 🎨 **JavaFX** (FXML, SceneBuilder, CSS)  
- 🗄️ **MySQL** pour la base de données  
- 🔗 **JDBC** pour la connexion entre Java et la base  
- 🧱 **Maven** comme outil de gestion de dépendances  
- 🧩 **MVC (Model–View–Controller)** pour la structure de l’application  

---

## 🚀 Installation et exécution
- 1️⃣ Cloner le projet
<pre>git clone https://github.com/SirineRaies/PetFriends.git</pre>
<pre>cd PetFriends</pre>

- 2️⃣ Ouvrir dans l’IDE

Importer le projet dans IntelliJ IDEA ou Eclipse.


- 3️⃣ Configurer la base de données
Créer une base de données MySQL nommée par exemple :

<pre>CREATE DATABASE petfriends;</pre>

Configurer ensuite la connexion (dans MyConnection.java) :

<pre>private static final String URL = "jdbc:mysql://localhost:3306/petfriends";
private static final String USER = "root";
private static final String PASSWORD = "";</pre>

- 4️⃣ Lancer l’application

Exécuter la classe principale : **Main.java**


L’interface JavaFX se lancera avec la page principale de l’application PetFriends.

 ---

## 🧠 Fonctionnalités principales

### 👤 Gestion des utilisateurs

- Inscription et connexion d’un utilisateur
- Modification et suppression du profil
- Affichage des informations de l’utilisateur

### 🛒 Gestion des produits

- Affichage de la liste des produits pour animaux
- Ajout, modification et suppression d’un produit (administrateur)
- Consultation du détail d’un produit avec description et prix

### 🎁 Gestion des offres

- Affichage des offres promotionnelles
- Association d’une offre à un produit
- Calcul automatique de la réduction

### ⭐ Gestion des ratings

- Un utilisateur peut publier un avis sur un produit
- Affichage de la moyenne des notes pour chaque produit
- Suppression ou modification d’un rating existant
  
---

## Auteur
Sirine Raies : Étudiante en ingénierie logicielle à l’École Polytechnique de Sousse
