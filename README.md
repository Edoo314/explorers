# Raconter les explorateurs de tous les temps

Cartes animées des grands voyages d'exploration, de Zheng He (1405) à Apollo 11 (1969).
*Explorers of all time — six centuries of expeditions, day by day, on an animated map.*

## Contenu

| Fichier | Rôle |
|---|---|
| `index.html` | Le site complet : carte, données et bibliothèques (d3, topojson, world-atlas) intégrées. Aucune dépendance externe. |
| `favicon.svg` | Icône d'onglet (rose des vents). |
| `og.png` | Image d'aperçu pour le partage sur les réseaux sociaux (1200 × 630). |
| `vercel.json` | En-têtes de cache : la page est toujours revérifiée, l'icône et l'image sont gardées une semaine. |

## Déploiement

Site statique, sans étape de compilation. Sur Vercel : « Framework Preset : Other », pas de commande de build, dossier de sortie : la racine.

## Mettre à jour

Remplacer `index.html` par la nouvelle version, puis :

```
git add index.html
git commit -m "Description de la modification"
git push
```

Vercel republie automatiquement en une trentaine de secondes.
