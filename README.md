# ONNX Prédiction

Ce projet permet de dessiner un chiffre sur un canvas et d'utiliser un modèle ONNX pour prédire le chiffre dessiné.

## Lien en ligne du projet 

https://imdimeh.github.io/Rendu-IA-Mehdi-Bellam/

## Prérequis

Avant de commencer, assurez-vous d'avoir les éléments suivants installés sur votre machine :

- [Node.js](https://nodejs.org/) (version 12 ou supérieure)
- Un navigateur web moderne (Chrome, Firefox, etc.)

## Installation

1. Clonez le dépôt sur votre machine locale :

    ```sh
    git clone https://github.com/ImDimeh/Rendu-IA-Mehdi-Bellam.git
    ```

2. Accédez au répertoire du projet :

    ```sh
    cd Rendu-IA-Mehdi-Bellam
    ```

3. Installez les dépendances nécessaires :

    ```sh
    npm install
    ```

## Lancer le projet

1. Démarrez un serveur local pour servir les fichiers statiques. Vous pouvez utiliser un serveur HTTP simple comme `http-server` :

    ```sh
    npx http-server
    ```

2. Ouvrez votre navigateur web et accédez à l'URL suivante :

    ```
    http://localhost:8080
    ```

3. Vous devriez voir la page web avec le canvas pour dessiner un chiffre. Utilisez les boutons "Supprimer" pour effacer le canvas et "Prédiction" pour obtenir une prédiction du chiffre dessiné.

## Structure du projet

- [index.html](http://_vscodecontentref_/0) : Le fichier HTML principal.
- [style.css](http://_vscodecontentref_/1) : Les styles CSS pour la page web.
- [script.js](http://_vscodecontentref_/2) : Le script JavaScript pour gérer le dessin sur le canvas et la prédiction avec le modèle ONNX.
- [ModelMehdi.onnx](http://_vscodecontentref_/3) : Le modèle ONNX utilisé pour la prédiction.

## Dépendances

Ce projet utilise les dépendances suivantes :

- [ONNX Runtime Web](https://www.npmjs.com/package/onnxruntime-web) : Pour exécuter le modèle ONNX dans le navigateur.

## Auteurs

- Mehdi Bellam

## Licence

Ce projet est sous licence MIT. Voir le fichier LICENSE pour plus de détails.
