# TP Web - Escape from Tarkov (Raid Customs)

Projet de site web interactif a choix multiples sur le theme du jeu Escape from Tarkov.

## Liste des 10 scenes (parcours coherent)

- index.html : Accueil et briefing du raid
- pages/scene01.html : Deploiement en zone industrielle
- pages/scene02.html : Les voies ferrees et le mirador de sniper
- pages/scene03.html : Le grand hangar des douanes
- pages/scene04.html : Le chantier en construction (voie Sud)
- pages/scene05.html : Fouille du pilleur et obtention de la Cle Marquee 314
- pages/scene06.html : Les dortoirs a trois etages (acces exclusif avec la cle)
- pages/scene07.html : La station-service et le boss Reshala (extraction ZB-1011)
- pages/scene08.html : La Chambre Marquee 314 (butin legendaire et fuite)
- pages/scene09.html : La forteresse militaire (extraction ZB-013)
- pages/scene10.html : Le poste de commandement de la forteresse
- pages/kia.html : Ecran de defaite (Killed In Action)
- pages/victoire.html : Ecran de victoire (Survived)

## Deux routes de raid bien distinctes

1. **Route Nord (La voie de la Chambre 314)** :
   - scene01 -> scene03 (hangar) -> scene05 (neutraliser le pilleur et prendre la cle) -> scene06 (dortoirs) -> scene08 (deverrouiller la Chambre 314) -> victoire.html ou scene09.
   - *Impossible d'acceder aux dortoirs et a la chambre 314 sans avoir neutralise le pilleur.*

2. **Route Sud (La voie de la Station et Forteresse)** :
   - scene01 -> scene02 (voies ferrees) -> scene04 (chantier) -> scene07 (station-service) ou scene09 (forteresse) -> victoire.html.

Aucun cul-de-sac. Toutes les pages disposent de retours logiques.
