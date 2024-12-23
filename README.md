# Generated PDF
[Download the generated PDF](output/output.pdf)

## Génération automatique de PDF avec GitHub Actions

Ce projet utilise une GitHub Action pour générer automatiquement un fichier PDF à partir d'un fichier Markdown (`input.md`). La génération du PDF est déclenchée chaque fois qu'il y a un **push** sur la branche `main` ou lors de la création d'une **pull request**.

### Fonctionnement de la GitHub Action

1. **Fichier source** : Le fichier Markdown à convertir en PDF doit être nommé `input.md` et placé à la racine du dépôt.
2. **Déclenchement automatique** : La GitHub Action se déclenche automatiquement lors d'un **push** sur la branche `main` ou lors d'une **pull request**.
3. **Génération du PDF** : Le fichier `input.md` est converti en PDF et placé dans le dossier `output/` sous le nom `output.pdf`.
4. **Mise à jour du `README.md`** : Un lien vers le PDF généré est ajouté au fichier `README.md` pour permettre aux utilisateurs de télécharger le PDF.

### Où trouver le fichier PDF généré

Le fichier PDF généré est placé dans le dossier `output/` à la racine du dépôt. Vous pouvez également télécharger le PDF directement depuis le `README.md`, où un lien de téléchargement est automatiquement ajouté après chaque génération.

### Ajouter ou modifier le fichier Markdown

Pour générer un nouveau PDF, ajoutez ou modifiez le fichier `input.md` à la racine du dépôt, puis effectuez un **push** vers la branche `main` ou ouvrez une **pull request**. La GitHub Action se déclenchera automatiquement et générera un nouveau PDF.

### Exemple de fichier `input.md`

Voici un exemple simple de fichier Markdown (`input.md`) que vous pouvez utiliser pour tester la génération du PDF :

```markdown
# Titre du Document

Ce document est un exemple de fichier Markdown.

## Sous-titre

Voici un paragraphe d'exemple.

