# 🛫 Gestion des Vols avec Python et MongoDB

Ce projet permet de récupérer des données de vols depuis une API, de les stocker dans une base de données MongoDB et de fournir plusieurs fonctionnalités pour les manipuler.

---

## 🚀 Fonctionnalités

- **📥 Récupérer et stocker les vols dans MongoDB**  
  Consomme une API externe pour récupérer les données de vols et les insère dans une collection MongoDB.

- **📋 Afficher tous les vols enregistrés**  
  Affiche la liste complète des vols stockés dans la base de données.

- **🔍 Rechercher des vols en fonction d’une date**  
  Permet à l'utilisateur de saisir une date et affiche tous les vols disponibles à cette date.

- **🧮 Calculer le nombre total de vols disponibles**  
  Retourne le nombre total de vols stockés dans la base de données.

- **📅 Trier les vols par date décroissante**  
  Affiche la liste des vols triés par date de départ en ordre décroissant.

---

## 🛠️ Technologies utilisées

- **🐍 Python** : Pour le script de gestion des données.
- **🍃 MongoDB** : Pour le stockage des données de vols.
- **🌐 API externe** : Pour récupérer les données de vols.

---

## 📂 Structure du projet

GETION_VOLS/
├── pycache/
├── db/
│ ├── pycache/
│ └── database.py
├── services/
│ ├── pycache/
│ └── flights_service.py
├── utils/
│ ├── pycache/
│ └── api_client.py
├── app.py
├── config.py
README.md

### **Description des dossiers et fichiers :**

- **`GETION_VOLS/`** : Dossier principal du projet.
  - **`db/`** : Contient les fichiers liés à la base de données.
    - **`database.py`** : Gère la connexion à MongoDB et les opérations de base de données.
  - **`services/`** : Contient les services métiers.
    - **`flights_service.py`** : Implémente les fonctionnalités liées aux vols.
  - **`utils/`** : Contient les utilitaires.
    - **`api_client.py`** : Gère les appels à l'API externe.
  - **`app.py`** : Point d'entrée de l'application.
  - **`config.py`** : Contient les configurations du projet (comme les clés API, les URLs, etc.).

- **`README.md`** : Documentation du projet.
- **`requirements.txt`** : Liste des dépendances Python.

---

## 🚀 Comment démarrer

1. **Installer les dépendances** :
   ```bash
   pip install -r requirements.txt
   Démarrer MongoDB :
Assurez-vous que MongoDB est installé et en cours d'exécution.

Exécuter le script :
python GETION_VOLS/app.py
📝 Exemples d'utilisation
Récupérer et stocker les vols :
fetch_and_store_vols()
Afficher tous les vols :
fetch_vols()
search_vols_by_date("2023-10-15")
Trier les vols par date décroissante :
sort_vols_by_date_desc()
🙏 Remerciements
Merci d'utiliser ce projet ! N'hésitez pas à contribuer ou à signaler des problèmes. 😊


---

## 🚀 Comment démarrer

1. **Installer les dépendances** :
   ```bash
   pip install -r requirements.txt
