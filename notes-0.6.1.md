# Overdrive Québec 0.6.1

Cette version protège tes réglages : le lanceur lit tes fichiers du jeu, et ne change un réglage que quand tu le lui demandes d'un clic. Il n'a jamais touché à tes touches, à ton profil ni à tes sauvegardes, et ça ne change pas.

- **DirectX 12 : plus de retour automatique.** Si le jeu refuse DirectX 12 ou se ferme dans les deux premières minutes, le lanceur te le dit et te propose « Revenir à DirectX 11 » ou « Garder DirectX 12 ». Rien ne change sans ton clic (en 0.6.0, il remettait DirectX 11 tout seul, même si tu avais simplement quitté le jeu vite).
- **Un choix fait pendant que le jeu tournait ne passe plus par-dessus tes réglages.** Un mode de conduite ou une option choisis jeu ouvert attendent le prochain « Jouer ». Si, entre-temps, tu as changé ces réglages dans le jeu, c'est ton choix dans le jeu qui gagne : le lanceur laisse tomber le sien et te le dit. Un choix en attente gardé par une ancienne version du lanceur n'est plus appliqué (il ne peut pas être vérifié) : refais-le si tu le veux encore.
- **Réglages personnalisés : aucun mode n'est présélectionné.** Si tes réglages ne correspondent à aucun mode, la fenêtre de conduite affiche « Personnalisé », aucune carte n'est cochée et « Appliquer » reste grisé tant que tu n'as pas choisi un mode.
- **« Restaurer mes réglages » ne recrée plus jamais un fichier.** Si tu as effacé un config.cfg (pour remettre le jeu à zéro), le lanceur ne le remplace plus par ton ancienne copie complète : il te le signale et garde la copie.
- Le lanceur lit maintenant tes fichiers de réglages en laissant le jeu les écrire en même temps : une lecture au moment où le jeu se ferme ne peut plus l'empêcher d'enregistrer.
- La correction des fuseaux horaires nomme le profil qu'elle va modifier.
