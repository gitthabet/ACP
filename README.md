# ACP & Kmeans

###L’objectif est d’effectuer une PCA puis un K-means.
Ceci étant dit, les autres objectifs sont aussi d’obtenir :
> une représentation des données permettant de comprendre les premières dimensions de la PCA (càd leur traduction/interprétation)

> les raisons associées à l’utilisation du Kmeans après cette PCA spécifique (càd pourquoi faire un Kmeans au vu des résultats de la PCA)

> les explications des étapes du Kmeans permettant d’aboutir au regroupement optimal.


###Concernant les données:
> l’ensemble des données sont numériques (pour certaines catégorielles)

> elles ont été sélectionnées à partir d’un ensemble de données plus grand

###Les features incluent:
NREF (le n° de référence du prêt <==> identifiant),<br>
MNT_PRET (le montant du prêt)
ENCOURS_PRET (l’encours du prêt)
NBRE_ECHEANCE (le nombre d’échéance)
pret_echu (le flag prêt échu, indiquant si le prêt a été échu)
FLAG_IMP (le flag prêt impayé, indiquant si le prêt a été au moins une fois impayé)
TOT_ENCOURS_DEPOTS (le total des encours de dépôt associés à n° de prêt)
TOT_ENCOURS_PRETS (le total des encours de prêt,  associés à n° de prêt détenu par un client)
flag_pret       (le type de prêt)
cd_agenteco     (le code agent économique)
cd_agence       (le code agence)
civil (la civilité de l’emprunteur)
