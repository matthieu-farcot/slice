# Slice Slice Baby

Experience en réalité augmentée

(C) 2026 M. Farcot

Ce projet propose une expérience de réalité augmentée (AR) accessible via un navigateur mobile, permettant d'afficher et de contrôler plusieurs témoignages vidéo lorsque l'utilisateur scanne un flyer dédié.

Technologies utilisées

1. A-Frame (1.7.0)

Framework WebVR/AR pour créer des scènes 3D en HTML.
Utilisé pour :

la scène AR
la caméra
les plans 3D (a-plane)
la gestion des assets
CDN : https://aframe.io/releases/1.7.0/aframe.min.js

2. MindAR (mindar-image-aframe) -- v1.2.5

Bibliothèque de réalité augmentée pour la reconnaissance d'images.
Utilisée pour :

détecter le poster
afficher les objets 3D
gérer targetFound / targetLost
CDN : https://cdn.jsdelivr.net/npm/mind-ar@1.2.5/dist/mindar-image-aframe.prod.js

3. HTML5 / CSS3

Utilisés pour :

la structure de la page
le design des boutons, overlays et modals
l'integration des éléments 3D

4. JavaScript (Vanilla)

Utilisé pour :

la gestion du changement de vidéos
les événements AR
la lecture/pause automatique
le modal d'informations
la mise à jour des boutons et indicateurs

5. Fichiers et assets

Fichiers 3D 
Image : Logo-simplifie-NB.jpg
Cible AR : targets-JPO.mind
Compatibilité mobile

Fonctionne sur Chrome Android, Safari iOS (playsinline), et nécessite un serveur local ou HTTPS. Testé sur une variété de mobiles (selon les possessions des élèves qui passaient devant le bureau) et de systèmes informatiques.

Structure du projet

/assets
/films
/object
slice.mind
index.html

Fonctionnement

Scan du Poster.
Détection de la cible et affichage de l'animation 3D.

Crédits

Source poster : Camexia / Art et Métiers ParisTech

Projet imaginé, encadré et co-développé par Matthieu Farcot
(c) Lycée Louis de Cormontaigne -- Metz, 2026
