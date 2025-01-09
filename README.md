# Next.js - Guide de Démarrage du Projet

Ce guide fournit les instructions pour créer et démarrer un projet en Next.js.

---

## Prérequis
1. **Visual Studio Code (ou un IDE)** : Assurez-vous d'avoir un éditeur de code installé sur votre ordinateur. Vous pouvez télécharger Visual Studio Code [ici](https://code.visualstudio.com/).
2. **Node.js** : Installez Node.js depuis le site officiel [nodejs.org](https://nodejs.org). Node.js inclut également un gestionnaire de dépendances, **npm** (Node Package Manager).

---

## Instructions pour démarrer le projet

### 1. Ouvrir Visual Studio Code
- Lancez Visual Studio Code (ou tout autre IDE de votre choix) sur votre ordinateur.

### 2. Installer Node.js
- Si ce n'est pas déjà fait, téléchargez et installez Node.js depuis le site officiel [nodejs.org](https://nodejs.org).
- Pour vérifier si Node.js est correctement installé, tapez les commandes suivantes dans un terminal :
  ```bash
  node -v
  npm -v
  ```
  Ces commandes afficheront les versions de Node.js et npm installées.

### 3. Créer un nouveau projet
- Ouvrez un terminal et exécutez les commandes suivantes pour créer un nouveau projet, y accéder, et démarrer le serveur local :
  ```bash
  npx create-next-app@latest mon-projet-next
  cd mon-projet-next
  npm run dev
  ```
  - **`npx create-next-app@latest`** : Crée un nouveau projet Next.js avec la dernière version disponible.
  - **`cd mon-projet-next`** : Entre dans le dossier de votre projet.
  - **`npm run dev`** : Lance le serveur local pour développer.

### 4. Tester en navigation privée
- Ouvrez votre navigateur en mode **navigation privée**.
- Rendez-vous sur l'adresse suivante :
  ```
  http://localhost:3000
  ```
  Cela garantit que votre navigateur charge toujours les versions les plus récentes de vos fichiers, en évitant les problèmes liés au cache.

---

## Notes
- Vous pouvez modifier votre projet en éditant les fichiers dans le dossier **`pages/`**. Par exemple :
  - **`pages/index.js`** : Contient la page d'accueil par défaut de votre application.
- Les modifications sont automatiquement rechargées dans votre navigateur.

---

## Ressources utiles
- [Documentation officielle de Next.js](https://nextjs.org/docs)
- [Node.js - Documentation](https://nodejs.org/en/docs/)
- [Visual Studio Code](https://code.visualstudio.com/)

