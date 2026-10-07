# Overdrive Québec 0.5.9

- Sécurité renforcée : les mises à jour du lanceur et le contenu de la communauté sont maintenant signés par deux clés séparées, et la clé des mises à jour ne quitte plus jamais l'ordinateur de l'administrateur. Un fichier « manifest.json » déposé à côté du lanceur (par exemple dans ton dossier Téléchargements) n'est plus lu, et ta connexion Steam n'est envoyée qu'au serveur de la communauté. Tu n'as rien à faire.
- Si une version du lanceur plante au démarrage, l'ancienne revient toute seule, et la vérification des mises à jour se fait en premier : une version corrigée peut toujours t'arriver sans tout retélécharger à la main.
- Le mod Overdrive peut maintenant être téléchargé d'une deuxième adresse si la première ne répond pas, toujours vérifié par son empreinte. Un téléchargement qui ne reçoit plus rien pendant une minute s'arrête au lieu de tourner sans fin, puis l'autre adresse est essayée.
- Ta position en direct sur la carte n'est plus jamais publique : sans connexion, la carte ne montre que des points anonymes (au kilomètre près), sans nom, sans vitesse ni livraison. Ton nom et ta livraison n'apparaissent aux membres connectés que si tu actives le nouvel interrupteur « Ma position en direct sur la carte des membres » dans ton Logbook ; il est éteint par défaut et tu peux l'éteindre en tout temps.
- Si ton Logbook ou tes réglages ne peuvent pas être lus (antivirus, OneDrive, version plus récente du lanceur), le lanceur ne les écrase plus jamais : il te dit où ton fichier est gardé, et un fichier illisible est mis de côté au lieu d'être perdu.
- Un fichier de Steam abîmé (bibliothèques ou jeu) n'empêche plus le lanceur de démarrer : le jeu est simplement indiqué comme introuvable.
- Une réponse bizarre d'un serveur de jeu ne bloque plus le démarrage ni l'actualisation : le serveur s'affiche « réponse invalide ».
- Le plugin du Logbook garde tes événements même quand un antivirus bloque un instant son fichier, et conserve deux anciens journaux au lieu d'un : tes trajets survivent à de longues sessions sans ouvrir le lanceur.
- Une image de profil ou de mod abîmée est retéléchargée au lieu de rester cassée.
- Si tu ouvres le lanceur une deuxième fois, la fenêtre déjà ouverte revient au premier plan au lieu d'en ouvrir une autre.
- Si un autre programme nommé « Overdrive.exe » (par exemple la liseuse OverDrive) se trouve dans le même dossier, le lanceur ne le touche plus jamais.
