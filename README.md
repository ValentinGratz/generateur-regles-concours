# Générateur de Règles de Concours IA

Un outil web 100% gratuit et côté client pour générer automatiquement des règlements de concours. Décrivez votre concours en une phrase, obtenez des règles complètes instantanément.

**[🚀 Voir la démo](https://valentingratz.github.io/generateur-regles-concours/)**

### ✨ Fonctionnalités
- **1-clic** : Un champ texte + un bouton Générer
- **Zéro dépendance** : HTML/CSS/JS vanilla, pas de build
- **Gratuit** : Aucune API payante, tout tourne dans le navigateur
- **Confidentiel** : Aucune donnée envoyée à un serveur
- **Responsive** : Mobile et desktop
- **Multilingue** : Accepte les descriptions dans toutes les langues

### 📋 Exemple d'utilisation
1. **Description** : `Concours photo thème "été". 1er prix : GoPro. Tirage le 31/08`
2. **Clic sur Générer**
3. **Résultat** : Règlement complet avec article 1 à X : participation, dates, lots, critères, dépôt légal, RGPD

### 🚀 Déploiement sur GitHub Pages

1. **Téléchargez** le fichier `.html` depuis l'aperçu → renommez-le `index.html`
2. **Uploadez** `index.html` à la racine de votre repo GitHub
3. **Activez Pages** : `Settings` > `Pages` > Source : `Deploy from a branch` > `main` > `/root` > `Save`
4. **En ligne** : `https://tonpseudo.github.io/nom-du-repo` en 1-2 min

### 🛠️ Personnalisation
Tout tient dans `index.html` :

| Élément | Où modifier |
| --- | --- |
| **Couleurs / Logo** | Balise `<style>` |
| **Textes / Titres** | Balise `<body>` |
| **Logique de génération** | Balise `<script>` > fonction `genererRegles()` |
| **Titre onglet** | `<title>Générateur de Règles IA</title>` |
| **Favicon** | Ajouter `<link rel="icon" href="favicon.ico">` dans `<head>` |

### ⚙️ Brancher une vraie IA [Optionnel]
Le générateur actuel utilise des templates JS. Pour utiliser GPT-4, Claude, Mistral :
1. Récupérez une clé API
2. Dans `<script>`, remplacez `genererRegles()` par un `fetch` vers l'API
3. **Attention** : Ne mettez jamais votre clé API en dur dans un repo public. Utilisez un proxy backend.

### 📄 Licence
MIT - Vous pouvez utiliser, modifier et vendre ce code librement.

---
Créé avec Meta AI. Remplacez `tonpseudo` par votre nom d'utilisateur GitHub.
