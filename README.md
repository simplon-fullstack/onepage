# onepage

site one page

LIEN DU JEUDI 29/08

https://prod.liveshare.vsengsaas.visualstudio.com/join?14F3C85BB7B5DA0631DE77B4CFA5EAE7334F


## EFFET JS LIGHTBOX

    ON PEUT CLIQUER SUR UNE MINIATURE ET AFFICHER L'IMAGE EN GRAND EN DESSOUS

    ON VEUT QUE L'IMAGE EN GRAND NE SOIT PAS VISIBLE AU DEPART.
    ET SEULEMENT QUAND ON CLIQUE ALORS L'IMAGE EN GRAND S'AFFICHE AU DESSUS DE LA PAGE.

    CSS
    z-index
    display
    position

    pour les effets: 

    transition

## BIBLIOTHEQUE D'ANIMATION JS

https://animejs.com


## POUR CODER AVEC SON SERVEUR WEB (XAMPP, WAMPSERVER, MAMP)


    * DEMARRER LE SERVEUR WEB
    * ENSUITE DEMARRER APACHE ET MYSQL
    * => ATTENDRE QUE LES SERVEURS SOIENT PRETS (ICONE EN VERT)
    * ENSUITE VERIFIER DANS LA NAVIGATEUR (GOOGLE CHROME, FIREFOX)

    http://localhost/
    http://localhost:8080/
    http://localhost:8888/
    http://localhost:81/

    SI LE SERVEUR WEB EST XAMPP, ALORS LE DOSSIER POUR NOTRE CODE EST

    C:\xampp\htdocs\simplon

    SI ON EST DANS WAMPSERVER

    C:\wamp64\www\simplon

    => AVEC VISUAL STUDIO CODE, ON OUVRE LE DOSSIER POUR AJOUTER NOTRE CODE

    => File > Open Folder
    => ENSUITE CHOISIR LE BON DOSSIER

    POUR VOIR LE RESULTAT DE NOTRE CODE
    DANS LE NAVIGATEUR, IL FAUT ALLER SUR L'URL

    SI VOTRE SERVEUR WEB EST SUR CETTE URL
    http://localhost:81/

    ALORS MON CODE EST SUR CETTE URL
    http://localhost:81/simplon/

    SI JE VEUX VOIR LE DOSSIER onepage
    http://localhost:81/simplon/onepage/

    SI JE VEUX VOIR MA PAGE base-flex.html
    http://localhost:81/simplon/onepage/base-flex.html

    DOC SUR FLEX (EN ANGLAIS) 
    https://css-tricks.com/snippets/css/a-guide-to-flexbox/

    MEDIA QUERIES
    https://www.alsacreations.com/article/lire/930-css3-media-queries.html

    => POUR POUVOIR DONNER DES REGLES CSS SEULEMENT SUR CERTAINES TAILLES D'ECRAN


## JAVASCRIPT

    * LANGAGES DECLARATIFS
    HTML
    CSS
    => LE DEVELOPPEUR ECRIT LE RESULTAT ATTENDU
    => ET C'EST LE NAVIGATEUR QUI SE DEBROUILLE POUR FAIRE LE TRAVAIL
    => ASSEZ FACILE A APPRENDRE

    ----------- ETAPE QUI FAIT MAL QUAND ON APPREND -------------

    * LANGAGES DE PROGRAMMATION
    JS
    PHP
    => LE DEVELOPPEUR DONNE DES INSTRUCTIONS
    => IL FAUT SAVOIR TOUTES LES ETAPES POUR ATTEINDRE SON OBJECTIF
    => L'ORDINATEUR SUIT LES INSTRUCTIONS 
    ET NE SAIT ABSOLUMENT CE QUE VOUS VOULEZ
    PROBLEME: SI DONNE DES MAUVAISES INSTRUCTIONS, L'ORDINATEUR SUIT CES INSTRUCTIONS 
    => BUG, PROBLEMES DE SECURITE, etc...
    => LE DEVELOPPEUR DEVIENT RESPONSABLE DU RESULTAT

    CREATION DE JAVASCRIPT: 1995

    JAVASCRIPT EST UN CODE QUI EST EXECUTE PAR LE NAVIGATEUR (AU DEBUT)

    DEPUIS QUELQUES ANNEES, ON A AUSSI NodeJS QUI PERMET D'EXECUTER DU CODE JS COTE SERVEUR


    DANS LE NAVIGATEUR, ON A 3 LANGAGES
    HTML    structure du contenu
    CSS     design, visuel, layout (mise en page)
    JS      interactivité et animation (dynamique)

    POUR MODIFIER LE HTML D'UNE PAGE, JS UTILISE LE DOM
    Document
    Object
    Model

    LA PAGE (DOCUMENT) EST MODELISEE DANS LE MONDE JAVASCRIPT SOUS LA FORME D'OBJETS
    => PROGRAMMATION ORIENTE OBJET

    tableau en javascript
    => container et plusieurs contenus
    => dans un tableau les éléments sont ordonnés

    objet en javascript
    => container et on peut y ranger plusieurs contenus
    => on n'a pas de notion d'ordre entre les éléments

    la notion d'objet est très vague
    => en gros, un objet est une boite qui permet de ranger plusieurs valeurs

    => arborescence
    => parent et enfants

    une balise est un objet javascript
    un attribut de balise est une propriété de l'objet javascript

    <img src="images/photo1.jpg">

    => balise img est un objet
    => dans l'objet, attribut src est une propriété 
        dont la valeur est le texte "images/photo1.jpg"

    AVEC JAVASCRIPT, JE PEUX UTILISER LE HTML COMME SOURCE D'INFORMATIONS
    => ON PEUT ACCEDER AUX INFORMATIONS DU HTML

    ET ON PEUT MODIFIER LE HTML EN MODIFIANT LES BALISES OU LES ATTRIBUTS

    ATTENTION: 
    GOOGLE REFERENCE LE CONTENU HTML INITIAL DE LA PAGE
    ET DONC TOUT LE CONTENU MODIFIE/AJOUTE PAR JS NE SERA PAS (BIEN) REFERENCE


    AVEC LES POSSIBILITES DES LANGAGES DE PROGRAMMATION
    variables
    valeurs
    conditions
    boucles
    fonctions
    => ON PEUT CREER DES PROGRAMMES TRES COMPLEXES


## ANIMATION

    POUR FAIRE DES ANIMATIONS COMPLEXES PLUS FACILEMENT
    => UTILISER DES BIBLIOTHEQUES

    https://animejs.com
    https://greensock.com/gsap/

## MOTEUR DE JEUX

http://phaser.io/

## ANIMATION 3D

https://www.babylonjs.com/


## EXERCICE SITE VITRINE

HTML => PREPARER UN SITE RESPONSIVE
CSS  => UTILISER FLEX POUR CREER DES COLONNES
JS   => AJOUTER INTERACTIVITE POUR CLIQUER ET DECOUVRIR PLUS DE CONTENUS
PHP  => DECOUPER VOTRE HTML EN FICHIERS PHP

MOTIVATION: CREER UN SITE CV QU'ON PEUT PRESENTER A UN EMPLOYEUR

Accueil
Mes Compétences
Mes Projets
Contact











