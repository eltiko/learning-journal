<!DOCTYPE html>
<html>
    <head>
        <title>Les boucles en JavaScript</title>
        <meta charset="utf-8">
    </head>
    <body>
        <h1>Les boucles</h1>
        <script>
            var i;
            
            /*i = 0 est appelée phase d'initialisation
             *i < 10 correspond à la condition
             *i++ est la phase d'incrémentation*/
            
            for(i = 0; i < 10; i++){
                alert ('i contents de value : ' + i);
            }
            
            /*Note : l'incrémentation se fait APRES le passage dans
             *la boucle. Ainsi, i contient 0 lors du premier passage*/
        </script>
    </body>
</html>
