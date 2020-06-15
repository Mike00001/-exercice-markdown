# -exercice-démarque
le  Markdown  C'est un petit langage très simple qui permet d'écrire du HTML de façon raccourcie. On peut s'en servir sur certains forums (Le Site du Zéro, Stack Overflow...) ou pour rédiger des documentations (incontournable sur GitHub).

Les créateurs de Markdown trouvaient que ce n'était pas vraiment pratique de devoir mettre en forme manuellement des textes en HTML (ou, pire, en bbCode). Imaginez, vous voulez poster un message sur un forum qui accepte uniquement le HTML et vous voulez écrire une liste à puces. Vous allez devoir écrire à la main
voici  une liste non ordonnée  ecrit en html:
<html>
    <head>
        <title>first page</title>
    </head>        
    <body>
        <ul>
            <li>Red</li>
            <li>Blue</li>
            <li>Green</li>
        </ul>
    </body>
</html>
Voici une liste  ordonnée ecrit en html:
<html>
    <head>
        <title>first page</title>
    </head>
    <body>
        <ol>
            <li>Red</li>
            <li>Blue</li>
            <li>Green</li>
        </ol>
    </body>
</html>
Voici une liste dans une liste (liste imbriquée):
<html>
    <head>
        <title>Ce que je vais faire:</title>
    </head>        
    <body>
 <ul>
  <li>Lire un livre</li>
  <li>Préparer une soupe
    <ol>
      <li>Couper les légumes</li>
      <li>Mettre dans l'eau et cuire</li>
      <li>Mouliner</li>
    </ol>
  </li>
  <li>Relever le courrier</li>
</ul>
      
    </body>
</html>
Voici un exemple de titre et de sous  titres à deux niveaux 
<html>
    <head>
        <title>Ma première formation</title>
    </head>        
    <body>
        <!-- Titre -->
        <h1>1-Becode</h1>
        <!-- Sous titre -->
        <h2>1.1- WebDev</h2>
        <h2>1.2- intelligence artificielle</h2>
        <h1>2-XXXX</h1>
        <!--sous titre du deuxième titre-->
        <h2>2.1-boulangerie patisserie</h2>
        <h2>2.2-higiène alimentaire</h2>
    </body>
</html>
<html>
    <head>
        <title>Ma première formation</title>
    </head>        
    <body>
        <!-- quelques liens -->
        <a href ="https://openclassrooms.com/fr/courses/2342361-gerez-votre-code-avec-git-et-github/2433596-installez-git#r-2448448">pour maitriser Git et GitHub,ciquer ici</a> <br/>
        <a href ="https://openclassrooms.com/fr/courses/1304236-redigez-en-markdown">pour comprendre le markdown,cliquer ici</a> <br/>
        <a href ="https://guides.github.com/activities/hello-world/">savoir utiliser les repository...,cliquer ici</a> 
    </body>
</html>
Une image statique :
<html>
    <head>
        <title>Ma première formation</title>
    </head>        
    <body>
 <img src = "alien.jpg" /> 
    </body>
</html>
Une image  annimée:
<html>
    <head>
        <title>une image annimée</title>
    </head>        
    <body>
 <img src = "image animée.gif" /> 
    </body>
</html>
Un peu de code 
<html>
    <head>
        <title>Ce que je dois faire</title>
    </head>        
    <body>
      <ul>
  <li>Lire un livre</li>
  <li>Préparer une soupe
    <ol>
      <li>Couper les légumes</li>
      <li>Mettre dans l'eau et cuire</li>
      <li>Mouliner</li>
    </ol>
  </li>
  <li>Relever le courrier</li>
</ul>
    </body>
</html>
