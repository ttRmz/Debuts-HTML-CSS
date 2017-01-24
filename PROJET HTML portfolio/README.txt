J'ai rencontré une difficulté par rapport au type de navigateur 
utilisé, le "margin-left" n'est pas le même pour le contenu de droite
(avec ma photo) en fonction du navigateur et malgré mes recherches je 
n'ai pas trouvé la solution. Je pensais qu'il fallait ajouter les
prefixes -moz- et -webkit- mais ce n'est pas ça.

div.container_right {
        width: 17%;
        position: fixed;
        z-index: 1;

        -webkit-margin-left: 53%;
        -moz-margin-left: 4%;
        margin-left: 53%;
        /* margin left de 53% seulement pour chrome */
        /* margin left de 4% pour toute autre plateforme */

        -webkit-box-shadow: 0px 1px 10px 0px rgba(0, 0, 0, 0.25);
        -moz-box-shadow: 0px 1px 10px 0px rgba(0, 0, 0, 0.25);
        box-shadow: 0px 0px 10px 0px rgba(0, 0, 0, 0.25);
        background-color: #ffffff;
    }

Je retrouve le même problème pour les icons dans mon footer.
Sans ces problemes la page fonctionne parfaitement, comme on peut le voir
avec une preview google chrome.

J'ai quand même uploadé le site malgré les defauts pour voir ce que ça
donne sur mobile : http://ramirez-io.esy.es/