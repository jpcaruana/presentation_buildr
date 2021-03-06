Présentation sur buildr en français.
Les slides sont faits avec remarkjs: voir http://remarkjs.com

# Texte introduction
"Montre-moi ton build, je te dirai comment se porte ton projet"

Buildr est un outil qui s'appuie sur rake, "the ruby make", et sur le langage ruby. Buildr reprend les bonnes idées issues de maven (repositories maven, arborescence standard des sources, standard des commande compile, test, install...) tout en proposant un outil simple, transparent et facile à faire évoluer.

Nous verrons des exemples concrets de buildfile sur des projets réels. Nous verrons aussi les bénéfices liés à la couche rake puis les possibilités ouvertes par le langage ruby.

Quelques exemples de comparatif avant/après entre maven et buildr :

projet de téléphonie : le build passe de 12 min à 2 min : le feedback est accéléré et plus clair. L'équipe peut alors oser des modifications profondes de son produit.

projet vidéo : le build passe de 14000 lignes (maven 1) à moins de 800. Temps et risque de release considérablement réduits sur un projet à haut risque, appropriation par l'équipe de son build, refactoring de modules...

buildr est disponible à l'adresse http://buildr.apache.org/ ; une communauté active et ouverte s'en occupe au Etats-Unis et en Europe.

Cette session s'adresse principalement à des développeurs soucieux de leur build.

Liens d'autres présentations buildr :
 * https://github.com/aboisvert/buildr-javazone-2010
 * http://buildr.markmail.org/message/qk7t2h7jglbr7zgh?q=list:users+slide
