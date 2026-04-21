#  TP CI/CD avec GitHub Actions

##  Objectif
Ce projet implémente un pipeline CI/CD complet avec GitHub Actions pour une application Node.js.

---

##  Fonctionnalités

- Tests automatisés avec **Jest**
- Linting avec **ESLint**
- CI multi-versions Node.js (18, 20, 22)
- Génération de rapport de couverture de code
- Déploiement automatique sur **GitHub Pages**
- Protection de la branche `main` avec validation CI

---

##  Pipeline CI/CD

Le workflow GitHub Actions inclut :

### 🔹 CI (Continuous Integration)
- Installation des dépendances
- Lint du code
- Exécution des tests
- Génération du coverage report
- Exécution sur plusieurs versions de Node.js

### 🔹 CD (Continuous Deployment)
- Déploiement automatique sur GitHub Pages
- Dépend du succès du CI

---

##  Badge CI

![CI](https://github.com/jaouadlmchari-hub/tp-cicd-actions/actions/workflows/ci.yml/badge.svg)


---

##  Structure du projet
