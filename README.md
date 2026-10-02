# TP Web - Escape from Tarkov (Raid Customs)

Projet de site web interactif a choix multiples sur le theme du jeu Escape from Tarkov.

## Liste des 10 scenes

- index.html : Accueil et briefing du raid
- pages/scene01.html : Deploiement en zone industrielle
- pages/scene02.html : Les voies ferrees et le sniper Scav
- pages/scene03.html : Le grand hangar et le pilleur hostile
- pages/scene04.html : La station-service abandonnee
- pages/scene05.html : La caisse d'armes lourdes
- pages/scene06.html : Le chantier en construction
- pages/scene07.html : Embuscade et passe-partout
- pages/scene08.html : La reserve medicale
- pages/scene09.html : Les dortoirs a trois etages
- pages/scene10.html : La forteresse et l'extraction finale
- pages/kia.html : Ecran de defaite (Killed In Action)
- pages/victoire.html : Ecran de victoire (Survived)

## Arbre de navigation complet

- index.html -> scene01.html
  - scene01.html -> scene02.html | scene03.html
  - scene02.html -> kia.html | scene04.html | scene06.html
  - scene03.html -> scene05.html | scene07.html | scene06.html
  - scene04.html -> scene08.html | scene09.html | kia.html
  - scene05.html -> scene10.html | scene04.html
  - scene06.html -> scene10.html | scene09.html
  - scene07.html -> scene05.html | scene06.html
  - scene08.html -> scene10.html | victoire.html
  - scene09.html -> scene05.html | scene10.html | kia.html
  - scene10.html -> victoire.html | kia.html
  - kia.html & victoire.html -> index.html

Aucun cul-de-sac. Toutes les pages disposent de liens retour et de continuite.
