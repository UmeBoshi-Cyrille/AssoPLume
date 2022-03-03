# AssoPLume
HTML CSS BOOTSTRAP app Eval

# Front-end d'un site associatif Fictif

_réalisation d'un projet de site web responsive dans le cadre d'une évaluation d'entraînement_ 

### site web de l'Association fictive : La Plume.

Ebauche d'un Site internet fictif donnant accès aux informations concernant une association, dites "la Plume". 
Le site présente succintement le but, l'intérêt, le partage du contenu spécifique au credo de cet organisme et de ses membres.
Un formulaire de contact est présent dans le but d'intéragir avec la communauté et de participer à leurs activités.

## Prérequis

- Avoir installer un éditeur de code. (J'ai personnellement utilisé vscode).
- avoir installer des extentions "SASS" en vue de compiler les fichiers ".scss".

##Deploiement

https://la-plume.herokuapp.com/


## Contribution et construction du projet

### * Intégralement réaliser avec les langages "HTML", "CSS" et le framework "Bootstrap", le projet comprend :
- 3 documents html 
- 4 dossiers, dont : 
- Un dossier utils comprennant le reset et le fichier Bootstrap.min.css
auquel tous les fichiers html sont lier.
- Un dossier image, pour le stockage des images.
- Un dossier icons pour leur stockage.
- un dossier CSS.

### * Le style est découpé en deux parties:
- Les parties communes relatives à tous les documents HTML, cela comprend : le Header, le carousel et le footer.
le style du texte réuni dans un seul document "style.scss"
- Les parties respectives à chaque fichier html : le Banner et le main pour "Index.html", les main respectifs aux deux autres pages.

### * Le Menu
Au format mobile:
- S'ouvre et se ferme grâce à une checkbox camouflé sous un label.
- Contenu camouflé par un overflow qui devient visible et se déploit à l'ouverture.
- En position fixe, est accessible à tout endroit de la page.
- Chaque chemin est normalement relier.

Aux formats plus larges :
- Le menu se déploit dans la largeur du header.
- N'est accessible qu'en haut de page.

### * Carousel commun
Comme pour le menu : 
- Accessible sur chaque pages avant le footer.
- Entièrement conçu avec du CSS.
- Inspirer d'un mini-projet code-pen.

Au format mobile :
- Carousel présent au format mobile. 
- Un chemin est présente en entête de chaque image.

Aux formats plus larges :
- Se déploit en largeur rendant toutes les images accessibles et cliquables.
- Images avec propriété title.
!!! problème ordre d'apparition des images lorsque l'on décide d'aller dans un sens ou dans l'autre.
- Il semble, malgré leur bonne écriture que les liens ne renvoient pas au chemin escompté,
mais à leurs pages respectives ce qui est intriguant.
PS : Les autres chemins fonctionnent correctement.


### * Navigation interne à chaque page
- La plume dans le header reconduit à l'accueil.
- Les flèches présentes entre chaque partie d'une page, permettent un défilement rapide vers le prochain contenu
grâce à des ancres.
- Un retour au header est présent en fin de page, sous le carousel.

## Gallerie

### * Menu des thèmes de la Gallerie
Par choix de suivre les recommandations de l'évaluation, aussi afin de pratiquer :
- Ce menu est construit dans un jeu de contraste de couleur "clair/sombre"
lorsque l'on passe la sourie dessus.
- L'intitulé de chaque élément de la liste possède aussi ce même jeu de contraste. 
- hélas, l'intitulé ne change de couleur qu'au contact avec la sourie sur l'ancre,
non pas sur l'élément "li" de la liste.

### * Thèmes de la Gallerie
- Chaque thème comporte quelques proverbes pour étoffer le contenu et offrir un aperçu.
- Chaque proverbe est muni d'une explication qui apparaît au contact avec la sourie grâce à un overflow.
- Le champs des explications est laissé volontairement blanc par souci de temps.

## Problématiques relevées
- La pages escales semble mal s'afficher sur de petits appareils, écrasant le contenu en quelque endroits. (TEST fait avec un samsung J3)
- L'attribution des chemins n'est pas parfait, et certains ne s'effectuent pas toujours correctement, notamment les ancres à d'autres pages.



