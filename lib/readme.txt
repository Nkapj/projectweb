=== RESSOURCES EXTERNES ET CHOIX TECHNIQUES ===

1. Bootstrap 5.3.8
Source :
https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/css/bootstrap.min.css

Utilisation :
Bootstrap a été utilisé pour la mise en page responsive du site, en particulier pour :
- la grille (row / col)
- l’alignement des blocs
- certains espacements et utilitaires
- la structure du header et de certaines sections
La classe row est utilisée pour créer une ligne dans le système de grille de Bootstrap. 


L’utilisation de Bootstrap implique la présence de balises <div> liées à son système de grille.
Ces <div> ne sont pas utilisés pour remplacer abusivement les balises HTML5, mais principalement 
pour organiser les colonnes et lignes nécessaires à la mise en page responsive.

2. Bootstrap Bundle 5.3.8
Source :
https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/js/bootstrap.bundle.min.js

Utilisation :
Le fichier JavaScript Bootstrap est chargé pour assurer le fonctionnement prévu des composants Bootstrap utilisés dans le projet.

3. Bootstrap Icons 1.11.0
Source :
https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.0/font/bootstrap-icons.css

Utilisation :
Les icônes Bootstrap ont été utilisées dans le header, le footer (résaux sociaux et autres ( Videos
 Podcast
 Newsletters
 Juegos
 Club El Comercio
 Edición impres) ).

=== REMARQUE SUR LA STRUCTURE HTML ===

Layout custom.html
inline-block pour les 3 colonnes (consigne 18). Bootstrap gère le responsive via les classes col-
(consigne 19 interdit @media). overflow-y: auto sur .principal pour limiter la hauteur (consigne 18).


Les balises <div> ont été limitées autant que possible.
Lorsqu’elles sont présentes, c’est principalement :
- pour appliquer la grille Bootstrap
- pour regrouper certains éléments visuels ou structurels
- pour faciliter l’alignement responsive sans détourner les balises sémantiques de leur rôle
