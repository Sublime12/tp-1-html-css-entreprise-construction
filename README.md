# TP-1 HTML CSS ENTREPRISE CONSTRUCTION
##### Le readme est ecrit en Francais mais vu que mon clavier est anglais et que je suis sur Linux, il est difficile pour moi d'ecrire les caracteres accentues.  

TP1 de INF3090
Le project consiste a construire un site web statique sur un projet d'entrepreneur

Ce projet represente le site web d'une entreprise de construction et de consultation

Le site contient la partie `assets` qui va contenir nos `Images` et differents `Fonts` 
recuperes sur internet.
Le repertoire racine (!!! du source code) contient nos differents pages html (5 pages) 
avec un seul fichier css qui sert a styler toutes les pages

    
## Exigences (Ou les trouver)
Certaines exigences peuvent etre difficiles a trouver, je vais les lister ici pour vous permettre 
de les trouver plus rapidement.

`Toutes les exigences ont etes respectes`


- `Pour naviguer entre les pages`, les sections de navigation se trouvent au `header` et 
au `footer` de toutes les pages

- `Les listes ordonnees et non-ordonnees` se trouvent dans la page d'acceuil (index.html)
juste apres notre tableau dans la premiere et la troisieme `Card` (Carte en francais probablement) 

- `Les liens internes` se trouvent dans notre footer (des toutes les pages) dans la section
`INFORMATIONS`, les deux liens sont `NOS PROJECTS` (Il point vers le tableau) et `PROJET RECENT` (Vers la partie recent project) dans la page d'acceuil

- `Les liens externes` se trouvent dans notre footer dans la partie de Gauche ou sont nommees 
les personnes qui ont ecrites (codees) le site (En l'occurence moi mais inspire par un template chez [Template.net](https://template.net)).

- `Le formulaire de plainte` est la page `contact.html`


## Structure du project
```
.
├── about.html
├── assets
│   ├── fonts
│   │   ├── changa_one
│   │   │   ├── ChangaOne-Italic.ttf
│   │   │   ├── ChangaOne-Regular.ttf
│   │   │   ├── Changa_One.zip
│   │   │   └── OFL.txt
│   │   ├── Changa_One.zip
│   │   ├── OFL.txt
│   │   ├── README.txt
│   │   ├── static
│   │   │   └── TiltNeon-Regular.ttf
│   │   └── TiltNeon-Regular-VariableFont_XROT,YROT.ttf
│   └── images
│       ├── about-bg.jpg
│       ├── about.jpg
|       ...
|       ...
|       ...
├── contact.html
├── index.css
├── index.html
├── package.json
├── package-lock.json
├── projects.html
├── README.md
└── services.html

5 directories, 43 files
```
## Style
Pour mon css, j'ai utilise des noms de balise utilitaire.
Les noms de mes styles ont ete inspire du framework [Tailwindcss](https://tailwindcss.com/)
La feuille Css a ete long a ecrire surtout a cause du nombre des styles mais `je peux vous assurer que tout le css a ete ecrit par moi-meme`.

Qu'est-ce que cela veut dire?

Cette approche permet de donner a nos classes css des noms qui representent le style 
qu'on veut appliquer

Pourquoi?

Ceci a quelques avantages, d'abord cela permet a nos classes css d'etre bien plus courte, aussi on connait tout cette situation quand on veut modifier juste un element dans une seule page (Genre dans la page d'acceuil) mais la classe css a modifier est applique sur plusieurs pages, avec l'approche des noms significatifs on devait faire apres avoir modifier notre style verifier toutes nos autres pages pour etre sure que notre style etait correct, probleme qui peut etre regle facilement si les classes css representent le style a appliquer

Ceci a aussi quelques desavantages, nos elements dans le html auront tendance a avoir beaucoup de classes ce qui nuire a la lisibilite du html