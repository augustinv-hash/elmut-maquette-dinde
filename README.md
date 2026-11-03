# Maquette SEO : elmut.fr/produits-chien/frais/dinde

Maquette statique annotée de la page https://elmut.fr/produits-chien/frais/dinde, avec les recommandations SEO datashake pour la requête « nourriture chien dinde ». Démo en `noindex`, non destinée à être indexée.

- Version du 03/11/2026, sur le modèle de la V2 de la maquette poulet (retour d'Elmut du 21/10) : aucun bloc de texte en bas de page.
- Encadrés verts : recommandations (title, meta, petit H1 en surtitre, alt du hero et alt en anglais, H2 « Informations nutritionnelles » doublé et sans espace, FAQ propre à la recette à la dinde).
- Contours pointillés verts : H1 ajouté et nouvelles questions de la FAQ, réponses dépliées pour la lecture.
- Le texte existant de la page n'est pas modifié.
- Bouton « Masquer les recommandations » : affiche la page optimisée sans les annotations.

Chiffres de la FAQ relevés le 03/11/2026 sur les 5 fiches recettes chien, cuisson à 90 °C sur /production, transition de 7 jours sur /produits-chien.

## Reconstruire

```bash
cd ~/Documents/CODE/elmut-maquette-dinde
~/Documents/CODE/seo-tools/.venv/bin/python -I scripts/build.py
```

Le script rend la page réelle avec Playwright (cache dans `scripts/cache/`, à supprimer pour forcer un nouveau rendu), retire le JavaScript et les traceurs, puis applique les recommandations. Polices : mêmes règles que la maquette /produits-chien (OFL en local, PP Pangaia et Maison Neue remplacées par Playfair Display et Archivo).
