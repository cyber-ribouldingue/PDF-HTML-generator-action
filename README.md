# Génération de PDF et HTML avec Pandoc

Ce dépôt utilise un **GitHub Actions workflow** pour générer automatiquement des fichiers PDF et HTML à partir de fichiers Markdown () en utilisant **Pandoc** et **LaTeX**.

## Fonctionnement du Workflow
1. Vérification de l'existence du fichier Markdown ().
2. Installation de Pandoc et LaTeX.
3. Génération du PDF et du HTML à partir de .
4. Ajout des fichiers générés au dépôt.
5. Mise à jour automatique du  avec des liens vers les fichiers générés.

## Comment générer un PDF et un HTML
1. Ajoutez un fichier  à la racine du dépôt.
2. Effectuez un **push** ou une **pull request** vers la branche .
3. Le PDF sera généré et ajouté au dossier .
4. Le fichier HTML sera généré et ajouté au dossier .

[Télécharger le PDF généré](output/pdf/output.pdf)
[Télécharger le fichier HTML généré](output/html/output.html)
