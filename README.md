# ACP & Kmeans

###L’objectif est d’effectuer une PCA puis un K-means.<br>
Ceci étant dit, les autres objectifs sont aussi d’obtenir :<br>
- une représentation des données permettant de comprendre les premières dimensions de la PCA (càd leur traduction/interprétation)<br>
- les raisons associées à l’utilisation du Kmeans après cette PCA spécifique (càd pourquoi faire un Kmeans au vu des résultats de la PCA)<br>
- les explications des étapes du Kmeans permettant d’aboutir au regroupement optimal.


###Concernant les données:<br>
- l’ensemble des données sont numériques (pour certaines catégorielles)<br>
- elles ont été sélectionnées à partir d’un ensemble de données plus grand<br><br>

###Les features incluent:<br>
- NREF (le n° de référence du prêt <==> identifiant),<br>
- MNT_PRET (le montant du prêt)<br>
- ENCOURS_PRET (l’encours du prêt)<br>
- NBRE_ECHEANCE (le nombre d’échéance)<br>
- pret_echu (le flag prêt échu, indiquant si le prêt a été échu)<br>
- FLAG_IMP (le flag prêt impayé, indiquant si le prêt a été au moins une fois impayé)<br>
- TOT_ENCOURS_DEPOTS (le total des encours de dépôt associés à n° de prêt)<br>
- TOT_ENCOURS_PRETS (le total des encours de prêt,  associés à n° de prêt détenu par un client)<br>
- flag_pret       (le type de prêt)<br>
- cd_agenteco     (le code agent économique)<br>
- cd_agence       (le code agence)<br>
- civil (la civilité de l’emprunteur)<br>
