Base de données Topographiques du système karstique de la résurgence du Git dans la massif karstique du Vercors (Saint-Quentin-en-Isère, 38, France)
=====================================================================================================================================================

Overview
--------

Ce dépôt contient les données topographiques et les dessins associés des cavités du système du Git sur le Vercors (38, France).
Les données de la résurgence du Git été produites par les spéléologues du club Vulcain de (Lyon, France) https://www.groupe-speleo-vulcain.com, soit en numérisant la topographie de 1994, soit par leur relevés au cours de leurs explorations.

Ce dépôt est mis à jour à chaque fois qu'une nouvelle topographie est rajoutée à l'un des systèmes décrit dans cette base de données.

Si besoin, des templates pour Therion sont disponibles sur https://github.com/robertxa/Th-Config-Xav .

Description
-----------

Ce dépôt sauvegarde les données topographiques et de dessin. Ces fichiers sont pour le logiciel Therion (data + dessins).

Uniquement les fichiers sources sont sauvegardés pour des raisons de taille ; j'ai aussi choisi de ne pas uploader les dessins dessinés à la main sur papier :
	
	* .thc, .th, .th2 et .thconfig pour le logiciel Therion
	
Pour obtenir les topographies en plan, coupe et/ou 3D, il faut compiler les fichiers Therion.

L'ensemble de ces topographies est publié et décrit dans les différents Echos des Vulcains, revue annuelle du club Vulcain disponible sur le site internet (https://www.groupe-speleo-vulcain.com/publications/echo-des-vulcains/). Les topographies compilées peuvent aussi être téléchargées sur la page https://www.groupe-speleo-vulcain.com/explorations/topographies-effectuees-par-le-club/cavites-de-chartreuse/ .
Le scan des notes topographiques de terrain est disponible sur demande.

Une convention a été mise en place pour la gestion des points d'interrogation, avec la définition de différents champs :

	* le champ "Code" qui décrit le type de terminus. Il peut prendre les valeurs : 
	
		* A : il suffit d'y aller et de continuer, pas d'obstacles
		
		* D : Désobstruction nécessaire, 
		
		* E : Escalade nécessaire, 
		
		* P : Puits non descendu,
		
		* Q : non renseigné sur les topographie anciennes, c'est à voir/vérifier,
		
		* S : Siphon à plonger, 
		
		* T : Trémie à désobstruer
	
	* le champ "Cavite" qui donne le nom de la cavité en question,
	
	* le champ "CA" qui est rempli si présence de courant d'air, avec éventuellement des remarques/commentaires.

Licence
-------

L'ensemble de ces données est publié sous la licence libre Creative Commons Attribution-ShareAlike-NonCommercial (Attribution, partage à l'identique et non commerciale) :
	http://creativecommons.org/licenses/by-nc-sa/4.0/

Auteurs de la base de données
----------------------------

Xavier Robert (xavier.robert@ird.fr) et Stéphane Lips

How to cite
-----------

Robert, X., Lips S., Base de données Topographiques du système karstique du Git (Vercors, 38, France), https://github.com/robertxa/Git, 2026. 
