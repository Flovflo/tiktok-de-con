# tiktok-de-con

HTML : Structure la page avec un titre, un conteneur pour le canevas (qui maintient un rapport d'aspect de 9:16), et des boutons de contrôle.
CSS (Tailwind CSS) : Style la page pour une apparence moderne et responsive, y compris un thème sombre et des styles pour les boutons. Le conteneur du canevas utilise un "padding hack" pour maintenir le format 9:16.
JavaScript :
Initialise le canevas et gère son redimensionnement.
Contient la logique pour trois animations distinctes :
Billes Rebondissantes : Des billes colorées qui se déplacent et rebondissent sur les bords du canevas.
Lignes Ondulantes : Plusieurs lignes sinusoïdales qui se déplacent de manière fluide.
Cercles Dynamiques : Des cercles qui changent de taille et se déplacent, avec un effet de mélange de couleurs lorsqu'ils se chevauchent (globalCompositeOperation = 'lighter').
Gère le passage d'une animation à l'autre via les boutons.
Affiche des messages de notification non bloquants.
L'animation démarre par défaut avec les billes rebondissantes.
