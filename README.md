
 #Semaine 12: http://www.chris36180.hebergratuit.net/
##Exercice 1:Auto-Completion:https://htmlpreview.github.io/?https://github.com/chris36180/semaine12/blob/master/exo1/index.html
##Le principe est simple mais efficace : dès qu'un utilisateur tape un caractère dans le champ, une recherche est immédiatement effectuée et retournée au navigateur. 
Ce dernier affiche alors les résultats dans un petit cadre généralement situé sous le champ de recherche. 
Les résultats affichés peuvent alors être parcourus, soit par le biais des touches fléchées du clavier (haut et bas), soit par le biais du curseur de la souris. 
Si on choisit un des résultats listés, celui-ci est alors automatiquement écrit dans le champ de recherche en lieu et place de ce qui avait été écrit par l'utilisateur. 
Il ne reste alors plus qu'à lancer la recherche.

L'avantage de ce type de script, c'est que l'on gagne un temps fou : la recherche peut être effectuée en tapant seulement quelques caractères. 
Cela est aussi très utile lorsque l'on ne connaît qu'une partie du terme recherché ou bien quand on fait une faute de frappe.

##Exercice 2:Tic-Tac-Toe: https://htmlpreview.github.io/?https://github.com/chris36180/semaine12/blob/master/exo2/index.html
###Étape 1 : faire une <div id="jeu"> avec 9 divs à l'intérieur. Faire en sorte qu'il y en ait 3 par ligne. Leur mettre un identifiant logique : « x1y2 » pour la div sur la colonne 1 et ligne 2 par exemple. Pensez aux bordures !

###Étape 2 : ajoutez un onclick sur la div de jeu. Utiliser le target pour retrouver quelle sous-div a été cliquée. Pour vérifier que tout fonctionne bien, faire une alerte qui affiche l'id de la div cliquée. Puis retirer l'alert.

###Étape 3 : quand une div est cliquée, lui ajouter la classe « player1 » si c'était un coup du joueur 1, et « player2 » si c'était le 2. En CSS, faire que l'une des classes fasse un fond vert et que l'autre fasse un fond rouge.

###Étape 4 : ajouter un bouton pour recommencer la partie en cours de route en réinitialisant la grille.

###Étape 5 : quand trois divs alignées sont assignées à un même joueur, afficher une alerte qui annonce sa victoire, puis réinitialiser la grille.

###Étape 6 : empêcher un joueur de jouer là où un coup a déjà été joué.
