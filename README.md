# 🤖 TP 1 : Agent Réflexe Simple (Robot Aspirateur)

## 📌 Objectifs du Projet

Ce projet implémente un agent réflexe simple (un robot aspirateur) capable de nettoyer une grille 3x3. Le but principal est de comprendre le cycle Perception → Décision → Action et d'évaluer la performance de l'agent.

* **Taille de la grille :** 3x3
* **Agent :** Réflexe simple (sans mémoire)
* **Règles :** Aspirer (si sale) ou se déplacer selon un cycle (DROITE, BAS, GAUCHE, HAUT).

## 🚀 Démarrage et Exécution

### Prérequis

* [Python 3.x](https://www.python.org/downloads/)
* [Jupyter Notebook](https://jupyter.org/install) (ou JupyterLab)

### Comment exécuter le Notebook

1.  **Cloner le dépôt :**
    ```bash
    git clone [https://github.com/votre_nom/nom_du_depot.git](https://github.com/votre_nom/nom_du_depot.git)
    cd nom_du_depot
    ```

2.  **Lancer Jupyter :**
    ```bash
    jupyter notebook
    ```

3.  Ouvrez le fichier **`TP1_RobotAspirateur.ipynb`** dans votre navigateur.
4.  Exécutez toutes les cellules pour voir la simulation de l'agent.

## 📊 Résultats et Performance

*(Décrivez ici les résultats obtenus, par exemple :)*

Le robot a réussi à nettoyer toutes les 6 cases sales en **12 actions** (pour seed=1). Le taux de propreté final est de 100%.

* **Taux de Propreté Final :** 100%
* **Nombre d'Actions :** 12
* **Grille Finale (Propre) :**
    ```
    0 0 0
    0 0 0
    0 R 0
    ```

## ⚙️ Auteur

**NOM :** NOUAM | **PRENOM :** IMANE | **FILIERE :** IAGI 2