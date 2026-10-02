# TP Web - Escape from Tarkov (Raid Customs)

Projet de site web interactif de type histoire a choix (livre dont vous etes le heros) sur le theme du jeu Escape from Tarkov.

## Structure du site

- index.html : Accueil et briefing de la mission
- pages/scene01.html : Deploiement en zone industrielle
- pages/scene02.html : Les voies ferrees (choix furtif ou sprint risque)
- pages/scene03.html : Le grand hangar (fouille ou combat)
- pages/scene04.html : La station-service (dernier obstacle)
- pages/scene05.html : La caisse d'armes (butin militaire)
- pages/kia.html : Fin par la mort (Killed In Action)
- pages/victoire.html : Fin victorieuse (Extraction reussie - Survived)

## Arbre de navigation

- Accueil (index.html) -> Scene 01
  - Scene 01 -> Scene 02 ou Scene 03
  - Scene 02 -> Mort (kia.html) ou Scene 04
  - Scene 03 -> Scene 05 ou Scene 04
  - Scene 04 -> Victoire (victoire.html) ou Mort (kia.html)
  - Scene 05 -> Victoire (victoire.html)
  - Mort et Victoire -> Retour a l'accueil (index.html)

Tous les chemins permettent de revenir en arriere ou de relancer le jeu, aucun cul-de-sac.
