# ProjectZen

## 🪧 À propos

ProjectZen est une plateforme web pensée pour simplifier la gestion de projets des petites et moyennes équipes.
Elle permet de suivre l’avancement, d’organiser les tâches et de fluidifier la communication, avec un outil léger, flexible et facile à utiliser.

---

## 📚 Table des matières

- 🪧 À propos
- 📦 Prérequis
- 🚀 Installation
- 🛠️ Utilisation
- 🤝 Contribution
- 🏗️ Construit avec
- 📚 Documentation
- 🏷️ Gestion des versions
- 📝 Licence

---

## 📦 Prérequis

Avant de démarrer, assurez-vous d'avoir :

- [Node.js v14 ou supérieur](https://nodejs.org/)
- [npm](https://docs.npmjs.com/)
- Un navigateur web récent (Chrome, Firefox, Edge...)
- [Heroku CLI](https://devcenter.heroku.com/articles/heroku-cli) pour le déploiement
- Variables d’environnement :  
  - `DB_USER` : nom d'utilisateur de la base de données  
  - `DB_PASS` : mot de passe de la base de données

---

## 🚀 Installation

Cloner le dépôt :
```bash
git clone https://github.com/ProjectZen/ProjectZen.git
cd ProjectZen
```

Installer les dépendances :
```bash
npm install
```

---

## 🛠️ Utilisation

### Démarrage de l'application
```bash
npm start
```
Accéder ensuite à : [http://localhost:8080](http://localhost:8080)

### Ajouter une tâche
```bash
npm run add-task "Nom de la Tâche"
```

### Lancer les tests
```bash
npm test
```

### Problèmes courants

- Si `npm start` ne fonctionne pas, vérifiez que tous les modules sont installés avec `npm install`.

---

## 🤝 Contribution

### Étapes pour contribuer :
1. Fork le dépôt
2. Crée une branche :  
   ```bash
   git checkout -b feature/nom-fonctionnalité
   ```
3. Apporte tes modifications
4. Commit tes changements :
   ```bash
   git commit -m "Ajout de la fonctionnalité : nom"
   ```
5. Push ta branche :
   ```bash
   git push origin feature/nom-fonctionnalité
   ```
6. Ouvre une pull request

---

## 🏗️ Construit avec

### Langages & Frameworks

- **JavaScript (ES6+)** : langage principal  
- **HTML5 / CSS3** : structure et style  
- **[React](https://reactjs.org/)** : front-end  
- **[Node.js](https://nodejs.org/)** : back-end  
- **[Express.js](https://expressjs.com/)** : serveur

### Outils

#### CI

- **[Travis CI](https://travis-ci.org/)** : intégration continue automatisée  
  Permet d’exécuter les tests à chaque push et pull request.

#### Déploiement

- **[Heroku](https://devcenter.heroku.com/)** : hébergement de l’application  
  Utilise le Heroku CLI pour déployer directement depuis le terminal.

---

## 📚 Documentation

- [Documentation officielle React](https://reactjs.org/docs/getting-started.html)
- [Travis CI Docs](https://travis-ci.org/docs)
- [Heroku CLI Docs](https://devcenter.heroku.com/articles/heroku-cli)

---

## 🏷️ Gestion des versions

Ce projet suit la [gestion sémantique de version (SemVer)](https://semver.org/lang/fr/).

Les versions sont disponibles via la section [Releases du dépôt GitHub](https://github.com/ProjectZen/ProjectZen/releases).  
> Un correctif lié à une fraude a été appliqué dans l'historique de commits.

---

## 📝 Licence

Ce projet est sous licence MIT. Voir le fichier [LICENSE](./LICENSE) pour plus d'informations.
