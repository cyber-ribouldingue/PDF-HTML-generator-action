# PDF Generator with Pandoc

Ce projet utilise une GitHub Action pour générer automatiquement des fichiers PDF à partir de fichiers Markdown (`.md`). La génération du PDF est déclenchée chaque fois qu'il y a un **push** sur la branche `main` ou lors de la création d'une **pull request**.

## Fonctionnement de la GitHub Action

### 1. Fichier source

Le fichier Markdown à convertir en PDF doit être nommé `input.md` et placé à la racine du dépôt. Ce fichier sera utilisé par la GitHub Action pour générer un fichier PDF.

### 2. Déclenchement automatique

La GitHub Action se déclenche automatiquement lors d'un **push** sur la branche `main` ou lors de la création d'une **pull request**.

### 3. Étapes de la GitHub Action

La GitHub Action suit les étapes suivantes :

- **Vérification de l'existence du fichier `input.md`** : Si le fichier n'est pas trouvé, le workflow échoue.
- **Installation de Pandoc et des dépendances LaTeX** : Ces outils sont nécessaires pour convertir le fichier Markdown en PDF.
- **Génération du PDF** : Le fichier `input.md` est converti en PDF et placé dans le dossier `output/` sous le nom `output.pdf`.
- **Mise à jour du `README.md`** : Un lien vers le PDF généré est ajouté dans le `README.md`.
- **Push des modifications** : Le PDF généré est ajouté au dépôt et un lien vers celui-ci est ajouté au fichier `README.md`.

### 4. Où trouver le fichier PDF généré

Le fichier PDF généré est placé dans le dossier `output/` à la racine du dépôt. Le fichier PDF est également référencé dans le `README.md` du dépôt avec un lien de téléchargement.

### 5. Ajouter ou modifier le fichier Markdown

Pour générer un nouveau PDF, ajoutez ou modifiez le fichier `input.md` à la racine du dépôt. Ensuite, effectuez un **push** vers la branche `main`, ou ouvrez une **pull request**. La GitHub Action se déclenchera automatiquement et générera un nouveau PDF.

### 6. Exemple d'un fichier `input.md`

Voici un exemple simple de fichier Markdown (`input.md`) que vous pouvez utiliser :

```markdown
# Titre du Document

Ce document est un exemple de fichier Markdown.

## Sous-titre

Voici un paragraphe d'exemple.

