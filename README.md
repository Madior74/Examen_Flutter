# 📱 Examen Flutter - Application de Gestion des Inscriptions Étudiants

Ce projet est une application mobile développée avec **Flutter** dans le cadre de l'examen de Développement Mobile (Licence 2). Elle permet la **gestion des inscriptions des étudiants**, avec une interface conviviale, une **authentification via Firebase**, et une base de données **SQLite** pour le stockage local des informations.

---

## 🔒 Authentification Firebase

L'application permet aux utilisateurs de créer un compte et de se connecter à l'aide de leur email et mot de passe via **Firebase Authentication**.

- Page d'inscription
- Page de connexion

---

## 📊 Tableau de bord (Dashboard)

Le tableau de bord affiche en temps réel :

- ✅ Nombre total d'étudiants inscrits
- 👩 Nombre d'étudiantes (sexe féminin)
- 👨 Nombre d'étudiants (sexe masculin)
- 📈 Un **diagramme circulaire** (pie chart) affichant la répartition homme/femme avec le plugin [`fl_chart`](https://pub.dev/packages/fl_chart)

---

## 🧑‍🎓 Modèle Étudiant

Chaque étudiant a les attributs suivants :

- Nom
- Prénom
- Photo de profil
- Adresse
- Téléphone
- Email

---

## 📄 Liste des étudiants

- Affichage de **tous les étudiants** sous forme de liste
- **Recherche dynamique** par nom ou prénom
- **Détail d’un étudiant** accessible via un clic sur la fiche

---

## 👤 Modèle Utilisateur (Compte)

Les informations pour chaque compte utilisateur sont :

- Nom
- Prénom
- Adresse
- Téléphone
- Email
- Mot de passe

---

## 🗄️ Stockage

- 🔐 Authentification avec **Firebase**
- 📂 Données des étudiants stockées en **local via SQLite**

---

## 📸 Captures d'écran

Voici quelques aperçus de l'application :


- Page de Connexion
- Accueil ou Tableau de bord
- Menu Drawer
- Page liste des Etudiants


---

## 📝 Instructions de Lancement

1. Cloner le projet :
   ```bash
   git clone https://github.com/Madior74/Examen_Flutter.git

