# GTA MOD : change_ped

Change le modèle du personnage, au hasard ou à ton choix.

## Démo

<video controls src="change_ped.mp4" title="Démo du mod change_ped"></video>

## Fonctionnalités

- Changement de ped aléatoire
- Choix manuel du modèle

## Prérequis

- Serveur FiveM à jour avec accès admin
- Ressource [MenuV](https://github.com/MenuV/MenuV) installée et démarrée avant ce mod

## Installation

1. Télécharge ce dépôt et renomme le dossier `gtamod-change-ped` en `change_ped`
2. Copie le dossier `change_ped` dans `resources/`
3. Ajoute `ensure menuv` puis `ensure change_ped` dans ton `server.cfg`
4. Redémarre le serveur

## Utilisation

Appuie sur **F1** pour ouvrir le menu, puis choisis « Aléatoire » (modèle au hasard) ou « Choisir » (saisie du nom exact du modèle, par exemple `a_m_m_beach_01`). En secours, la commande `change_ped` dans la console F8 ouvre aussi le menu.

> Le mod `vehicle_settings` utilise aussi la touche **F1** : si les deux sont démarrés en même temps, change la touche de l'un des deux dans son `client.lua`.

## Structure du dossier

```
change_ped/
├─ client.lua           -- script principal (menu MenuV)
├─ fxmanifest.lua
├─ change_ped.mp4       -- vidéo de la démo
└─ README.md
```

## Crédits

Tuto et mod réalisés par :
Alice MASSART, PAD EMD 2026.
