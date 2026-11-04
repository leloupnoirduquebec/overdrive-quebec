# Overdrive Québec 0.9.17

- Correctif : le lanceur ne se présente plus comme planté quand le pilote graphique se réinitialise pendant la fermeture (erreur « UCEERR_RENDERTHREADFAILURE »). Rien n'était perdu, mais le rapport d'erreur faisait peur.
- Correctif : si le pilote graphique se réinitialise pendant que le lanceur est ouvert, il se relance tout seul en affichage logiciel (plus lent, mais stable) au lieu de s'arrêter.
- Correctif : dans la vérification des mods, un fichier de clé Overdrive que le serveur accepte n'est plus signalé comme « pas permis sur le serveur ».
- Correctif : l'Ultimate Graphics Mod est facultatif sur le serveur. Le lanceur ne le demande plus comme obligatoire et ne le signale plus comme « pas permis sur le serveur ». Si tu l'as, garde-le sous les modules d'Overdrive : le lanceur t'avertit encore s'il passe au-dessus de Météo.
- Correctif : « Ouvrir la fiche des mods » depuis la vérification ne bloque plus la fenêtre. La vérification se ferme et la fiche s'ouvre à sa place.
- Correctif : les fenêtres du Logbook en jeu s'affichent maintenant sans passer par la carte graphique, pour éviter l'erreur « UCEERR_RENDERTHREADFAILURE » quand une mission démarre l'inspection.

Mise à jour : ferme le jeu ET le lanceur, rouvre le lanceur (il installe la mise à jour), puis relance le jeu avant de te reconnecter au serveur.
