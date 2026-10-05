# Overdrive Québec — site de téléchargement

Ce dépôt est le site public du lanceur communautaire **Overdrive Québec** pour American Truck Simulator.
Il ne contient que les fichiers à télécharger, pas le code source.

| Fichier | Rôle |
|---|---|
| `index.html` | la page de téléchargement |
| `ConvoiQuebec-0.5.5.exe` | le lanceur (un seul fichier, Windows 10/11 64 bits) |
| `update.json` + `.sig` | l'annonce de la dernière version, signée; le lanceur la lit à chaque démarrage |
| `manifest.json` + `.sig` | les informations de la communauté (nouvelles, serveurs, mods, musique), signées |
| `music/` | la musique du lanceur |
| `notes/` | les notes complètes des nouvelles du babillard, lues dans le lanceur |
| `SHA256SUMS.txt` | les empreintes des fichiers |
| `notes-0.5.5.md` | les nouveautés de cette version |

Les fichiers `.sig` sont des signatures Ed25519 : le lanceur refuse toute mise à jour et tout manifeste qui ne
sont pas signés par la clé de la communauté. Ne modifie aucun fichier à la main : sa signature ne serait plus bonne.

Gratuit, fait par des joueurs. Non affilié à SCS Software ni à TruckersMP.
