# Exploitation automatique de pix-orga par classe en python

### Objectif 
Fournir des fichiers des résultats de l'avancée des campagnes PIX orga :
- par classe,
- lisibles,
- en html (et/ou pdf),
- en particulier, pour fournir les résultats aux enseignants non inscrits dans Pix orga,
- en affichant les élèves n'ayant pas fait le parcours (déclencheur de l'affichage : 1 élève de la classe a fait le parcours)

Produire une synthèse de toutes les classes.

### Fonctionnement
Lancer le programme python exploitation-auto-pix-orga.py puis renseigner vos identifiants pix-orga.

### Tests
- Le programme est utilisé pour une structure d'une centaine de classes,

#### À tester
- Le programme est prévu pour gérer un personne administrant plusieurs établissements mais cette fonction n'a pas pu être testée

### Bilbiothèques python
- Utilise la bibliothèque pandas (le plus souvent présente dans les packs python)
- Facultativement utilise la bibliothèque xhtml2pdf pour générer les fichiers pdf. L'absence de la bibliothèque est géré automatiquement. Le programme produit un document hmtl parfaitement lisible.

### Exemples
#### Parcours de rentrée

![Capture d'écran résultats d'un parcours de rentrée](Capture-%C3%A9cran-r%C3%A9sultats-parcours-rentr%C3%A9e.jpg) 

#### Parcours thématique

![Capture d'écran résultats d'un parcours de rentrée](Capture-%C3%A9cran-r%C3%A9sultats-parcours-th%C3%A9matique.jpg) 

#### Collecte de profil

![Capture d'écran résultats d'un parcours de rentrée](Capture-%C3%A9cran-collecte-profils.jpg) 
