# Génération de PDF avec Pandoc

Ce dépôt utilise un **GitHub Actions workflow** pour générer automatiquement des fichiers PDF à partir de fichiers Markdown () en utilisant **Pandoc** et **LaTeX**.

## Fonctionnement du Workflow
1. Vérification de l'existence du fichier Markdown ().
2. Installation de Pandoc et LaTeX.
3. Génération du PDF à partir de .
4. Ajout du PDF généré au dépôt.
5. Mise à jour automatique du  avec un lien vers le PDF.

## Comment générer un PDF
1. Ajoutez un fichier  à la racine du dépôt.
2. Effectuez un **push** ou une **pull request** vers la branche .
3. Le PDF sera généré et ajouté au dossier .

[Télécharger le PDF généré](output/output.pdf)
