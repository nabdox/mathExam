# Application Examens Mathématiques

Ce projet propose une application web autonome (fichier `index.html`) permettant de créer et gérer des examens de mathématiques pour des classes d'élèves. Les données sont stockées localement dans le navigateur via `localStorage`.

## Fonctions principales
- **Création de questions QCM** avec rendu LaTeX, support des réponses multiples et attribution de points.
- **Importation d'élèves** depuis un fichier Excel (`NotesCC`), attribution automatique des numéros.
- **Passation et correction** : l'examinateur sélectionne un élève, enregistre les réponses et obtient une note sur 20.
- **Statistiques** : histogramme de répartition des notes et calculs de moyenne, médiane, mode et écart-type.
- **Export** : génération de l'examen en PDF et export des résultats au format Excel.

## Utilisation
1. Ouvrir `index.html` dans un navigateur moderne.
2. Créer des questions puis importer la liste des élèves depuis un fichier Excel.
3. Sélectionner un élève et saisir ses réponses pour obtenir la note.
4. Consulter les statistiques dans l'onglet correspondant.

Les bibliothèques utilisées sont chargées via CDN : MathJax, Chart.js, SheetJS et jsPDF.

## Tests

Le projet ne comprend pas encore de suite de tests automatisés. Un script minimal est fourni pour
permettre l'exécution de `npm test`, qui affiche simplement un message.

