# 🍳 Mes Recettes

Carnet de recettes personnel façon Pinterest, pensé **100 % mobile** (iPhone et Android).

- 110 recettes avec photo, ingrédients, étapes et lien vers la recette d'origine
- Filtres par saison 🌸 ☀️ 🍂 ❄️, par catégorie et par temps de préparation
- Liste de courses intelligente : quantités recalculées pour 2 personnes et ingrédients fusionnés, avec copie en un geste
- Gestes natifs : appui long pour le menu, glisser à gauche pour supprimer (avec « Annuler »)
- Palette « Mediterranean Calm », aucune librairie externe
- Données enregistrées dans le navigateur du téléphone (localStorage)

## Structure

```
index.html   ← toute l'application (HTML, CSS et JS dans un seul fichier)
img/         ← 110 photos des recettes (.webp, 4:5)
README.md
```

## Mettre en ligne avec GitHub Pages

1. Dans le dépôt : **Settings → Pages**.
2. *Source* : **Deploy from a branch** → branche `main`, dossier `/ (root)` → **Save**.
3. Après 1 à 2 minutes, le site est en ligne à l'adresse `https://<votre-compte>.github.io/<nom-du-depot>/`.

## Installer sur le téléphone

- **iPhone (Safari)** : ouvrir le site → bouton Partager → **Sur l'écran d'accueil**.
- **Android (Chrome)** : ouvrir le site → menu ⋮ → **Ajouter à l'écran d'accueil**.

L'application s'ouvre alors en plein écran, comme une app.

## Bon à savoir

- Les recettes, la sélection et la liste de courses sont enregistrées **sur chaque téléphone**. Elles ne se synchronisent pas entre appareils.
- Vider les données du navigateur efface les recettes ajoutées ou modifiées.
- Pour ajouter une photo à une recette créée dans l'app, collez le lien d'une image en ligne.

## Crédits

Recettes et photos d'origine : [Jow](https://jow.fr). Les étapes ont été résumées et chaque fiche renvoie vers la recette complète. Ce projet est destiné à un **usage personnel**.
