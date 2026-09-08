# Jazz Pulse

Copie autonome de Jazz Pulse pour publication sur GitHub Pages.

## Publication avec GitHub Pages

1. Creer un depot GitHub nomme `jazz-pulse`.
2. Importer tous les fichiers et dossiers de ce repertoire a la racine du depot.
3. Ouvrir `Settings` > `Pages`.
4. Dans `Build and deployment`, choisir `Deploy from a branch`.
5. Selectionner la branche `main` et le dossier `/(root)`, puis enregistrer.
6. Le site sera disponible a l'adresse `https://VOTRE-COMPTE.github.io/jazz-pulse/`.

## Structure

- `index.html` : application principale
- `audio/` : sons du metronome et six grooves
- `.nojekyll` : publication statique directe par GitHub Pages

Les chemins audio utilises par l'application sont relatifs (`./audio/...`) et sont compatibles avec un site GitHub Pages publie dans un sous-repertoire.
