# Styles et Couleurs Utilisés

- Titre de niveau 1 (H1) : Inconsolata Extra-Bold 800
- Titres de niveaux 2 et suivants (H2, H3, etc.) et paragraphes (p) : Roboto Mono

Couleurs utilisées :
- Fond principal : #0D0D0D
- Couleur d'accent : #F2C84B
- Couleur de mise en évidence : #F2E205
- Couleur de texte : #2F3640
- Couleur de lien : #7587BF

Pour une utilisation optimisée des différentes typographies et couleurs, un fichier all.scss a été créé.

# Personnalisation du Menu et du Footer

La personnalisation du menu et du footer a été réalisée en utilisant un fichier CSS externe appelé "all.css".

## Menu

Le menu de navigation comporte trois boutons :
- "Accueil"
- "Galerie"
- "Nous contacter"

Ces boutons sont des liens (a href) qui permettent une navigation efficace à travers le site. J'ai utilisé le framework Bootstrap pour structurer le menu de manière élégante. 
Cela m'a permis de placer le logo à gauche de l'écran et les boutons de navigation à droite. L'utilisation de Bootstrap a également facilité l'intégration d'un menu "burger" pour les formats d'affichage responsifs. 
Cette approche garantit une expérience utilisateur fluide et cohérente, quel que soit le dispositif utilisé.

## Footer

Le footer a été personnalisé en créant une division (div) dédiée. Pour garantir qu'il reste en bas de l'écran sur toutes les pages, j'ai positionné cette division en mode "fixed". 
Cette méthode assure que le footer reste toujours visible au bas de la page, quel que soit le contenu ou la longueur de la page. Cela contribue à l'esthétique globale du site et à une meilleure expérience utilisateur.

# Personnalisation des Pages

## Page d'Accueil (index.html)

Sur la page d'accueil, j'ai utilisé la classe "container" de Bootstrap pour centrer les éléments de la page. La mise en page comprend :
- Une image
- Un titre
- Du texte formaté en colonnes grâce à l'utilisation de CSS avec "display: flex" et "flex-direction: column". Pour garantir la responsivité, j'ai ajusté la taille de l'image et du texte en fonction de la taille de l'écran.

## Page Galerie (galerie.html)

Dans la section container de la page galerie, j'ai utilisé les classes Bootstrap suivantes : "col-lg-4 col-md-12 mb-4 mb-lg-3" pour que les images s'adaptent à chaque taille d'écran. 
Sur un grand écran, les images sont affichées sur trois lignes, tandis qu'en format mobile, un élément est affiché par ligne. 
J'ai également ajouté des liens (a href) avec "target=_blank" sur les images pour permettre aux utilisateurs d'accéder aux pages des films en cliquant sur les images. 
L'utilisation de "target=_blank" permet d'ouvrir les pages dans une nouvelle fenêtre ou un nouvel onglet du navigateur.

## Page Films (film.html)

Pour la page films, j'ai utilisé un fichier CSS externe appelé "page.css" pour apporter des modifications spécifiques à cette page. 
Pour assurer la responsivité, j'ai utilisé "display: flex" avec "flex-direction: column" pour disposer les éléments dans un format de colonnes. 
Cela garantit une présentation élégante et adaptée à différents appareils.

## Page Nous Contacter (form.html)

Sur la page "Nous Contacter", j'ai conçu la mise en page de manière à être conviviale aussi bien en format mobile qu'en format desktop. 
En format mobile, j'ai utilisé les balises "input" et "textarea" pour permettre aux utilisateurs de remplir le formulaire de contact. J'ai appliqué "display: flex" avec "flex-direction: column" pour organiser ces éléments en colonnes. E
n format desktop, j'ai utilisé "display: flex" avec "flex-direction: row" pour aligner les champs de formulaire côte à côte, offrant ainsi une meilleure expérience utilisateur, quel que soit l'appareil utilisé.
