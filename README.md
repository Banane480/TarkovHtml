# TP Web - Escape from Tarkov (Raid Customs)

Projet de site web interactif a choix multiples sur le theme du jeu Escape from Tarkov.

## Liste des 10 scenes (parcours coherent)

- index.html : Accueil et briefing du raid
- pages/scene01.html : Deploiement en zone industrielle
- pages/scene02.html : Les voies ferrees et le mirador de sniper
- pages/scene03.html : Le grand hangar des douanes
- pages/scene04.html : Le chantier en construction (carrefour central)
- pages/scene05.html : Fouille du pilleur et decouverte de la Cle Marquee 314
- pages/scene06.html : Les dortoirs a trois etages (entree et couloir)
- pages/scene07.html : La station-service et le boss Reshala
- pages/scene08.html : La Chambre Marquee 314 (butin legendaire et fuite)
- pages/scene09.html : La forteresse militaire
- pages/scene10.html : Le poste de commandement de la forteresse
- pages/kia.html : Ecran de defaite (Killed In Action)
- pages/victoire.html : Ecran de victoire (Survived)

## Arbre de navigation complet

- index.html -> scene01.html
  - scene01.html -> scene02.html | scene03.html
  - scene02.html -> kia.html | scene04.html | scene01.html
  - scene03.html -> scene05.html | scene04.html | scene01.html
  - scene04.html -> scene06.html | scene07.html | scene02.html | scene03.html
  - scene05.html -> scene06.html | scene04.html | scene03.html
  - scene06.html -> scene08.html (Chambre 314) | victoire.html (Dorms V-Ex) | scene09.html | kia.html | scene04.html
  - scene07.html -> scene09.html | scene06.html | kia.html | scene04.html
  - scene08.html -> victoire.html (Fenetre camion) | scene09.html | kia.html | scene06.html
  - scene09.html -> scene10.html | victoire.html (Bunker ZB-013) | scene06.html | scene07.html
  - scene10.html -> victoire.html (Courant ZB-013) | kia.html | scene09.html
  - kia.html & victoire.html -> index.html

Aucun cul-de-sac. Toutes les pages disposent de retours logiques et d'une continuite geographique reelle basee sur la carte Customs de Tarkov.
