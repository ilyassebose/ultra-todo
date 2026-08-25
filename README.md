# ✅ UltraTodo Pro

**Application de gestion de tâches ultra-complète avec connexion entre utilisateurs, mode vocal, mind map, et persistance IndexedDB.**

---

## 📱 Description

UltraTodo Pro est une application de gestion de tâches mobile-first (PWA compatible) qui fonctionne **100% hors ligne** grâce à IndexedDB. Elle permet de :
- Créer, modifier, supprimer des tâches
- Organiser par projets, tags, priorités
- Ajouter des sous-tâches
- Définir des répétitions (quotidien, hebdo, mensuel)
- Utiliser la **saisie vocale** pour ajout multiple
- Visualiser les tâches en **Mind Map** avec zoom/déplacement
- Se **connecter avec d'autres utilisateurs** via un code à 6 chiffres
- Voir les tâches et statistiques des contacts connectés
- Suivre ses **statistiques** (taux de complétion, série, etc.)
- Créer des **modèles (templates)** réutilisables
- Exporter/Importer en JSON/CSV

---

## 🚀 Installation

### Option 1 : Fichier HTML simple
1. Télécharge le fichier `index.html`
2. Ouvre-le dans n'importe quel navigateur (Chrome, Firefox, Edge, Safari)
3. ✅ C'est prêt !

### Option 2 : Convertir en APK (Android)
1. Va sur [FreeWebToApk](https://freewebtoapk.com) ou utilise **Capacitor**
2. Choisis "Local HTML File"
3. Upload le fichier `index.html`
4. Génère l'APK
5. Installe sur ton téléphone
6. ✅ Les données persistent grâce à IndexedDB

### Option 3 : Héberger en ligne
- **Netlify Drop** : [app.netlify.com/drop](https://app.netlify.com/drop)
- **Tiiny.host** : [tiiny.host](https://tiiny.host)
- **GitHub Pages** : Repo `username.github.io`

---

## 🎯 Fonctionnalités Détaillées

### 📋 Gestion des Tâches
| Fonctionnalité | Description |
|----------------|-------------|
| **Ajout rapide** | Bouton + → Ajouter en écrit ou vocal |
| **Priorités** | 🔴 Haute, 🟡 Moyenne, 🟢 Basse |
| **Date & Heure** | Échéance avec heure précise |
| **Tags** | Étiquettes personnalisées |
| **Sous-tâches** | Liste de sous-tâches cochables |
| **Projets** | Assigner à un projet |
| **Répétition** | Quotidien, Hebdomadaire, Mensuel |
| **Dépendances** | Bloquer une tâche tant qu'une autre n'est pas finie |
| **Archivage** | Masquer sans supprimer |

### 🎤 Mode Vocal
- **Ajout multiple** : Dites "Ajouter [tâche]" plusieurs fois
- **Commande Stop** : Dites "Stop" ou "Terminer" pour finir
- **Reconnaissance continue** : Plusieurs tâches en une session
- **Tags automatiques** : Les tâches vocales sont taguées "vocal"

### 🧠 Mind Map
- **Visualisation** : Tâches et projets en nœuds
- **Connexions** : Cliquez sur 2 tâches pour créer une dépendance
- **Assignation projet** : Cliquez sur une tâche puis sur un projet
- **Zoom** : Boutons +/− ou pincement tactile
- **Déplacement** : Glisser pour déplacer les nœuds
- **Auto-organisation** : Réorganise automatiquement

### 🔗 Connexions entre Utilisateurs
- **Code personnel** : 6 chiffres générés automatiquement
- **Partage** : Donnez votre code à quelqu'un
- **Connexion** : Entrez le code de l'autre personne
- **Vue des tâches** : Consultez les tâches du contact
- **Vue des stats** : Consultez les statistiques du contact
- **Déconnexion** : Retirez un contact à tout moment

### 📈 Statistiques
- **Taux de complétion** : Pourcentage de tâches terminées
- **Tâches actives** : Nombre de tâches en cours
- **Série (Streak)** : Jours consécutifs avec au moins une tâche finie
- **En retard** : Tâches dépassant leur échéance
- **Graphique 7 jours** : Évolution de la productivité

### 📦 Modèles (Templates)
- **Modèles prédéfinis** : Réunion, Courses, Projet
- **Création personnalisée** : Nom + liste de tâches
- **Application en 1 clic** : Crée toutes les tâches du modèle

### 📤 Export / Import
- **Export JSON** : Sauvegarde complète
- **Export CSV** : Compatible Excel/Sheets
- **Import** : Restauration depuis un fichier JSON

### 🔒 Sécurité
- **Mot de passe maître** : Verrouillage de l'application
- **Données locales** : Tout est stocké en IndexedDB
- **Aucun serveur** : Vos données ne quittent jamais votre appareil

### 🌓 Thème
- **Clair** : Par défaut
- **Sombre** : Basculer via le bouton 🌓
- **Persistant** : Le thème est sauvegardé

---

## 💾 Stockage des Données

### IndexedDB (Primaire)
