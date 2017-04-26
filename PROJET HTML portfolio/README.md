J'ai rencontré une difficulté par rapport au type de navigateur 
utilisé. Le "margin-left" n'est pas le même pour le contenu de droite
(avec ma photo) en fonction du navigateur.

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

Sans ces problemes la page fonctionne parfaitement, comme on peut le voir
avec google chrome.

J'ai quand même hébergé le site malgré les defauts pour voir ce que ça
donne sur mobile

# Demo : http://ramirez-io.esy.es/
