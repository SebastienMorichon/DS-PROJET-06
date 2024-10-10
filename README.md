# Classifiez automatiquement des biens de consommation

<div class="oc-richContent root-0-3-1" data-translations="{&quot;forbiddenError&quot;:&quot;Vous ne pouvez actuellement pas accéder à ce projet. Assurez vous de bien être positionné sur ce projet par votre mentor.&quot;,&quot;genericError&quot;:&quot;Une erreur est survenue. Veuillez réessayer plus tard.&quot;}" data-videotitle="video" data-current-user-id="328418" data-project-id="1503"><p><img src="https://user.oc-static.com/upload/2023/10/10/16969371520395_Section%20mission.png" alt=""></p>
<h4>Comment allez-vous procéder&nbsp;?</h4>
<p><em><img src="https://user.oc-static.com/upload/2023/09/19/16951295813132_Barre%20titres.png" alt="Barres titres"></em></p>
<p>&nbsp;</p>
<p><span style="font-weight: 400;">Cette mission suit un scénario de projet professionnel.</span><span style="font-weight: 400;"><br></span></p>
<p>&nbsp;</p>
<p><span style="font-weight: 400;">Vous pouvez suivre les étapes pour vous aider à réaliser vos livrables.</span></p>
<p>&nbsp;</p>
<p><span style="font-weight: 400;">Avant de démarrer, nous vous conseillons de :</span></p>
<ul>
<li style="font-weight: 400;">lire toute la mission et ses documents liés ;</li>
<li style="font-weight: 400;">prendre des notes sur ce que vous avez compris ;</li>
<li style="font-weight: 400;">consulter les étapes pour vous guider ;&nbsp;</li>
<li style="font-weight: 400;">préparer une liste de questions pour votre première session de mentorat.</li>
</ul>
<p>&nbsp;</p>
<h4>Prêt à mener la mission ?</h4>
<p><em><img src="https://user.oc-static.com/upload/2023/09/19/16951295813132_Barre%20titres.png" alt="Barres titres"></em></p>
<p>&nbsp;</p>
<p>Vous êtes Data Scientist au sein de l’entreprise "<strong>Place de marché</strong>”, qui souhaite lancer une marketplace e-commerce.</p>
<figure><a class="oc-imageLink oc-imageLink--disabled custom-link" href="https://user.oc-static.com/upload/2019/02/24/15510259240381_Projet%20textimage%20logo.png"><a href="https://user.oc-static.com/upload/2019/02/24/15510259240381_Projet%20textimage%20logo.png" class="oc-imageLink oc-imageLink--disabled"><img src="https://user.oc-static.com/upload/2019/02/24/15510259240381_Projet%20textimage%20logo.png" alt="logo entreprise place de marché"></a></a></figure>
<p>Sur&nbsp;cette place de marché anglophone, des vendeurs proposent des articles à des acheteurs en postant une photo et une description.</p>
<p>&nbsp;</p>
<p>Pour l'instant, l'attribution de la catégorie d'un article est effectuée manuellement par les vendeurs, et est donc peu fiable. De plus, le volume des articles est pour l’instant très petit.</p>
<p>&nbsp;</p>
<p>Pour rendre l’expérience utilisateur des vendeurs (faciliter la mise en ligne de nouveaux articles) et des acheteurs (faciliter la recherche de produits) la plus fluide possible, et dans l'optique d'un passage à l'échelle,<strong>&nbsp;&nbsp;il devient nécessaire&nbsp;d'automatiser&nbsp;cette tâche d‘attribution de la catégorie.</strong></p>
<p>&nbsp;</p>
<p><strong>Linda</strong>, Lead Data Scientist, vous demande donc d'étudier la faisabilité d'un&nbsp;<strong>moteur de classification</strong>&nbsp;des articles en différentes catégories, à partir du texte (en anglais) et de l’image comme dans l’illustration ci-dessous.</p>
<p><img src="https://user.oc-static.com/upload/2023/03/30/1680170799854_Data%20Scientist-P6-01%20%281%29.png" alt="Une image et un texte décrivant un produit mènent à une flèche vers un label, pour illustrer l'assignation automatique."></p>
<p>Voici le mail qu’elle vous a envoyé.</p>
<p>&nbsp;</p>
<div class="oc-tableContainer">
<div class="oc-tableContainer"><table>
<tbody>
<tr>
<td>
<p><strong>De</strong> : Linda</p>
<p><strong>À</strong> : moi</p>
<p><strong>Objet&nbsp;</strong>: démarrage de la mission</p>
</td>
</tr>
<tr>
<td>
<p>Bonjour,&nbsp;</p>
<p>&nbsp;</p>
<p>Merci pour ton aide sur ce projet !</p>
<p>&nbsp;</p>
<p>Ta mission sera de réaliser<strong>&nbsp;une étude de faisabilité d'un moteur de classification</strong>&nbsp;<strong>automatique&nbsp;</strong>d’articles, en utilisant leur image et leur description sur le jeu de données d'articles disponible dans la première pièce jointe de ce mail.</p>
<p>&nbsp;</p>
<p>Pourrais-tu<strong>&nbsp;analyser</strong>&nbsp;les<strong>&nbsp;descriptions textuelles</strong>&nbsp;et les<strong>&nbsp;images des produits</strong>, au travers des étapes suivantes :&nbsp;</p>
<ul>
<li>Un<strong>&nbsp;prétraitement</strong>&nbsp;des données texte et image&nbsp;</li>
<li>Une&nbsp;<strong>extraction</strong>&nbsp;de features&nbsp;</li>
<li>Une&nbsp;<strong>réduction&nbsp;</strong>en 2 dimensions, afin de projeter les produits sur un graphique 2D, sous la forme de points dont la couleur correspondra à la catégorie réelle&nbsp;</li>
<li>Une<strong>&nbsp;analyse&nbsp;</strong>du<strong>&nbsp;graphique</strong>&nbsp;afin de conclure, à l’aide des descriptions ou des images, sur la&nbsp;<strong>faisabilité de regrouper automatiquement</strong>&nbsp;des produits de même catégorie&nbsp;</li>
<li>Une réalisation d’une&nbsp;<strong>mesure pour confirmer ton analyse visuelle</strong>, en calculant la similarité entre les catégories réelles et les catégories issues d’une segmentation en clusters</li>
</ul>
<p>&nbsp;</p>
<p>Pourrais-tu nous démontrer ainsi la faisabilité de regrouper automatiquement des produits de même catégorie ?</p>
<p>&nbsp;</p>
<ul>
<li>
<p>Afin d’extraire les&nbsp;<strong>features image</strong>, il sera nécessaire de mettre en œuvre :</p>
<ul>
<li>un algorithme de type SIFT / ORB / SURF ;</li>
<li>un algorithme de type CNN Transfer Learning.</li>
</ul>
</li>
</ul>
<p>&nbsp;</p>
<p>Afin d’extraire les<strong>&nbsp;features texte</strong>, il sera nécessaire de mettre en œuvre :&nbsp;</p>
<ul>
<li>deux approches de type bag-of-words, comptage simple de mots et Tf-idf ;</li>
<li>une approche de type word/sentence embedding classique avec Word2Vec (ou Glove ou FastText) ;</li>
<li>une approche de type word/sentence embedding avec BERT ;</li>
<li>une approche de type word/sentence embedding avec USE (Universal Sentence Encoder).</li>
</ul>
<p>&nbsp;</p>
<p>Pour t’aider, en deuxième pièce jointe, tu trouveras un&nbsp;<strong>exemple</strong>&nbsp;de Notebook mettant en œuvre les approches d’extraction de features d’images sur un autre dataset<strong>.</strong></p>
<p>&nbsp;</p>
<p>Merci encore,&nbsp;</p>
<p>Linda</p>
<p>&nbsp;</p>
<p>PS : J’ai bien vérifié qu’il n’y avait aucune contrainte de propriété intellectuelle sur les données et les images.</p>
</td>
</tr>
<tr>
<td>
<p>Pièces jointes :&nbsp;</p>
<ul>
<li>PJ 1 :&nbsp;<a class="custom-link" href="https://s3-eu-west-1.amazonaws.com/static.oc-static.com/prod/courses/files/Parcours_data_scientist/Projet+-+Textimage+DAS+V2/Dataset+projet+pre%CC%81traitement+textes+images.zip">Jeu de données d’articles</a></li>
<li>PJ 2 :&nbsp;<a class="custom-link" href="https://s3.eu-west-1.amazonaws.com/course.oc-static.com/projects/Data_Scientist_P6/Weather_Images_CNN_Transfer_Learning_Stage_1_feasibility_V1.0.ipynb">Notebook d’extraction de features d’images et d’étude de faisabilité</a></li>
</ul>
</td>
</tr>
</tbody>
</table></div>
</div>
<aside data-claire-semantic="information">
<p>Pour l’approche de type SIFT, n’hésitez pas à consulter le webinaire disponible dans les<a href="/projects/1503/resources"> ressources.</a></p>
</aside>
<p>&nbsp;</p></div>
