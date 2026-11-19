# ÉCHO — données ouvertes

Ce dépôt est destiné à publier les **bases de données dérivées** des données ouvertes utilisées par l'application ÉCHO. Il est indépendant du code de l'application et ne contiendra aucune donnée des utilisateurs d'ÉCHO.

> **Statut : en préparation.** Aucune donnée n'est encore publiée ici.

## Organisation

| Dossier | Source | Licence |
|---|---|---|
| [`datasets/que-faire-a-paris/`](datasets/que-faire-a-paris/) | « Que Faire à Paris ? - Evènements et activités », Direction de la Communication - Ville de Paris | Open Database License (ODbL) v1.0 |

Chaque jeu de données aura :

| Fichier | Contenu |
|---|---|
| `catalogue.json` | Dernière version publiée (lien stable). |
| `versions/<version>/catalogue.json` | Chaque version publiée, jamais réécrite. |
| `SHA256SUMS` | Empreinte SHA-256 de chaque version. |
| `metadata.json` | Provenance : source, éditeur, adresse du jeu de données, licences, format. |

[CHANGELOG.md](CHANGELOG.md) listera chaque publication (version, date, nombre de fiches, empreinte) ; l'historique Git les conservera toutes.

## Licence

Voir [LICENSE.md](LICENSE.md).

## Contact

Pour toute question : ouvrir une *issue* sur ce dépôt.
