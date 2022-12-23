<div align="center">

[![Open In Collab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Naereen/badges)
[![GitHub license](https://img.shields.io/github/license/Naereen/StrapDown.js.svg)](https://github.com/Naereen/StrapDown.js/blob/master/LICENSE)
![Markdown (https://camo.githubusercontent.com/6e875655730cdaa9ea24491042a944e3895f51e13552ff18305aace236853dba/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4d616465253230776974682d4d61726b646f776e2d626c61636b2e737667)
<br>
[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity)
![If usefull](https://camo.githubusercontent.com/deab10366c6377e3d4cc454a26f96225e2cc196214b129b95c9d5284207b64d7/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f6c6162656c3d254630253946253843253946266d6573736167653d496625323055736566756c267374796c653d7374796c653d666c617426636f6c6f723d424334453939)
<br>
<br>
<br>
[![ForTheBadge built-with-love](http://ForTheBadge.com/images/badges/built-with-love.svg)](https://GitHub.com/Naereen/)
[![ForTheBadge uses-css](http://ForTheBadge.com/images/badges/uses-css.svg)](http://ForTheBadge.com)


  <h1> ⭐SASS/SCSS INSTALLATION LOCALE FR <img src="https://cdn-icons-png.flaticon.com/512/197/197560.png" width="26"/> </h1>

  <samp>
   <h6>Ceci est mon tout premier tuto ✌️ destiné initialement à des camarades de promotion en développement web Simplon, soyez indulgent avec ce travail
   et n'hésitez pas à me faire remonter tous les bugs rencontrer ou des axes d'améliorations potentielles. 💕 </h6>
   </samp
   
   <br>
   <br>
   <br>
    
  Dans ce tutoriel nous allons apprendre à installer le préprocesseur *SASS* en version locale sans passé par *Npm*. Sass va nous permettre de rédiger du     *CSS* de manière plus organiser et plus propre. On retrouve actuellement *SASS* sur bons nombres de projet web, car son efficacité n'est plus à prouver. Une fois Sass en votre possesions vous aurez à intégré toutes ces notions en travaillant avec quelques fonctionnalités performantes de *Sass* telles que : les *variables, les fonctions, les conditions, les mixins et les extensions*. 

  <h3> START HERE </h3>

  <br>
  <br>

  **I.** Pour la première étape, vous allez vous rendre sur <b>le site officiel de SASS</b> et vous rendre dans la section <b>"Install"</b>. <br>
    [SASS Site Officiel](https://sass-lang.com/")
  <br>
  <br>

  <img src="img/etape01.png" width="60%" height="100%">

  <br>
  <br>
  <br>
 
  **II.** Une fois sur la page "Install", vous devez click sur <b>"From Github"</b> dans la partit installation dite en <b>"Command Line"</b>. <br>
    [SASS Install section](https://sass-lang.com/install)

  <br>
  <br>
  <br>

<img src="img/etape02.png" width="60%" height="100%">

  <br>
  <br>
  <br>

  **III.** Une fois sur la page de téléchargement, vous devrez choisir <b>la version correspondante a votre systeme</b>, dans mon cas Windows x64.

  <br>
  <br>
  <br>

  <img src="img/etape03.png" width="80%" height="100%">

  <br>
  <br>
  <br>

  **IV.** Une fois l'archive winrar <em>"dart-sass-1.XX.X"</em> en votre possession, vous trouverez a l'intérieur de cette archive un <em>"dossier"</em> nommée <em>"dart-sass"</em>. 
  Il faudra alors prendre et placer ce <em>"dossier" "dart-sass"</em> dans votre <em>"dossier"</em> de travail à l'endroit ou vous allez commencer a codé votre projet, 
  dans mon cas un dossier <em>"Tuto_sass"</em>.

  <br>
  <br>
  <br>

  <img src="img/etape04.png" width="60%" height="100%"> 
  <img src="img/etape05.png" width="70%" height="100%">

  <br>
  <br>
  <br>
  
  **V.**  Une fois dans mon dossier *"Tuto_sass"*, avec à l'intérieur mon dossier *"dart-sass"*. 
    Je vais créer un autre dossier dans *"Tuto_sass"* que je vais appeler *"sass"*. 
    Dans ce dossier "sass" je viens crée un *"fichier"* qui se nomme *"style.scss"*. 
    Voici a quoi doit ressembler à ce stade votre arborescence de projet.

  <br>
  <br>
  <br>

  <img src="img/arborecense_check.png" width="50%" height="100%">

  <br>
  <br>
  <br>

  **VI.** à ce moment-là vous aller ouvrir un nouveau *terminal dans mon cas VSCode,* et taper dans ce terminal : <br> 
 ``` ./dart-sass/sass sass/style.scss ``` 
 <br>
  Cette commande va indiquer a *Sass* que nous travaillons dans le fichier *"style.scss"*.

  <br>
  <br>
  <br>

  <img src="img/etape06.png" width="60%" height="100%">

  <br>
  <br>
  <br>

  **VII.** Toujours dans ce même terminal vous allez ensuite taper : <br> 
  ``` ./dart-sass/sass sass/style.scss style.css ``` 
 <br>
  Cette commande va ainsi crée un fichier "style.css" ainsi qu'un "style.css.map" c'est normal. 

  <br>
  <br>
  <br>

  <img src="img/etape07.png" width="60%" height="100%">
  <img src="img/etape07.5.png" width="30%" height="100%">

  <br>
  <br>
  <br>

  **VIII.** Pour finir avec le terminal, il vous faudra taper cette dernière commande : <br> 
 ``` ./dart-sass/sass sass/style.scss style.css --watch ```
 <br>
  Qui va permettre à *Sass* d'auto save et de *syncroniser* toutes vos modifications sur *"style.scss"* directement et en parralel dans le fichier *"style.css"*.

  <br>
  <br>
  <br>

  <img src="img/etape08.png" width="70%" height="100%">

  <br>
  <br>
  <br>

   Pensez bien a créer un fichier *index.html* et y link votre fichier *style.css* dedans.<br>
   Avec le classique : 
  ``` <link rel="stylesheet" href="style.css"> ```
 <br>
 <br>
 <br>
 <br>
 
  <samp>
  <h6> Voila vous êtes enfin prêt a codé avec *Sass* dans votre fichier "style.scss". 😎 :star: <br>
  Ah ouais t'es chaud! Ca rigole pas ici, bababababa!
  Génie sérieux! </h6>

  [![Ask Me Anything !](https://img.shields.io/badge/Ask%20me-anything-1abc9c.svg)](https://GitHub.com/Naereen/ama) 
  [![GitHub stars](https://badgen.net/github/stars/KurumiRockbell/Sass_instalation_tuto_fr)](https://GitHub.com/KurumiRockbell/Sass_instalation_tuto_fr)
  </samp>
</div>
