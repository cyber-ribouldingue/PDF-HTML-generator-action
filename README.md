# Génération de PDF et HTML avec Pandoc

Ce dépôt utilise un **GitHub Actions workflow** pour générer automatiquement des fichiers PDF et HTML à partir de tous les fichiers Markdown () en utilisant **Pandoc** et **LaTeX**.

## Fonctionnement du Workflow
1. Recherche et génération de fichiers PDF et HTML pour tous les fichiers .
2. Installation de Pandoc et LaTeX.
3. Génération des fichiers PDF et HTML pour chaque fichier Markdown trouvé.
4. Ajout des fichiers générés au dépôt.
5. Mise à jour automatique du  avec des liens vers les fichiers générés.

## Comment générer un PDF et un HTML
1. Ajoutez un fichier  à la racine du dépôt.
2. Effectuez un **push** ou une **pull request** vers la branche .
3. Le PDF et le fichier HTML seront générés et ajoutés aux dossiers  et .

[Télécharger le PDF généré](output/pdf/)
[Télécharger le fichier HTML généré](output/html/)
