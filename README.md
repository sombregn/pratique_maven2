# 🚀 SpringBoot: Module Maven 2

Ce projet vise a mettre en place un module module maven.Comme suit.
Créer un projet maven nomée commandes : projet parent
le projet parent est juste un projet maven
Créer les modules maven suivants : services, web et batch
services sera un projet qui va gerer le metier de l'application
web est un projet tomcat
batch est un projet sping boot

---

## 📋 Table des matières
- [Objectif](#-objectif)
- [Prérequis](#-prérequis)
- [Installation](#-installation)
- [Lancement du projet](#-lancement-du-projet)
- [Captures d'écran](#-captures-décran)

---

## 🎯 Objectif
L'objectif de ce projet est de créer un module maven avec Springboot et aussi un Serveur Tomcat.

---

## 📦 Prérequis
Avant de commencer, assurez-vous d'avoir les éléments suivants installés sur votre machine :

- **Java 17** ou version supérieure 
- **Maven** pour la gestion des dépendances

---

## 🛠 Installation

### 1. Cloner le projet
Commencez par cloner le dépôt GitHub sur votre machine locale :
- **git clone  https://github.com/sombregn/pratique_maven2.git**

### 2. Accéder au répertoire du projet
Accédez au répertoire du projet cloné :
- **cd pratique_maven2**

🚀 Lancement du projet
### 1. Build de l'application
Compilez et construisez l'application avec Maven :
- **mvn clean install**

### 2. Lancer l'application
Démarrez l'application Spring Boot :
Rdv dans les modules 
- **cd batch**
- **mvn spring-boot:run**
- **cd services**
- **mvn spring-boot:run**
- **Démarrez le serveur tomCat**
- Configuration voir (image config Tomacat)
- Pour le TomCat à appuyé sur le btn Run de IDE
- **Vous pouvez également lancer l'application directement depuis votre IDE en appuyant sur le bouton Run.**

### 🌐 URLs d'accès sur Navigateur
Une fois l'application lancée, vous pouvez accéder aux services via les URLs suivantes :
- **Application: http://localhost:8080/web/**

### 📸 Captures d'écran
Pour visualiser des captures d'écran de l'application et résultats, consultez le dossier captures dans le projet.

### 📝 Remarque
Assurez-vous que maven et Java est bien installé et configurée.
