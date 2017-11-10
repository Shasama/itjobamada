ITJOBMADA - Estimation du cahier des charges fin octobre 2017

I- Crération et gestion des publicités
	A- En BO
		1- Création table clients pub + Classe client pub (30min)

		2- Création table pubs + classe pub (30min)

		3- Menu de création et de gestion des pubs (pour chaque rubrique)
			a) interface création(insertion) pub 
				- interface (2h)
				- upload image (validation de l’image)
					-> taille
					-> extension fichier
					-> résolution
					(2h)
				- champ société, suggestion au remplissage (3h)
				- fenêtre modal création client (4h)
				- calendrier ajout date début (2h)
				- calendrier ajout date fin (2h)
				- vérification règle de date début et date fin + date début pas avant date du jour (2h)
				- champs numéro facture + champ durée slide 					  (1h)
				- enregistrement pub (2h)

			b) Datagrid (liste des pubs)
				- interface (2h)
				- mise à jour de la liste après enregistrement d'un pub (2h)
				- tri par colonnes (10h)
				- activation - désactivation – suppression (6h)
				- interface de modification (4h)

		TOTAL : 44 + 22*6 = 176h 
		(44h pour une rubrique et j'ai estimé que pour les 6 autres rubriques c'est la moitié du temps chacune)

		4- Menu historique (pour chaque rubrique)
			a) Liste des clients
				- interface + bouton "Tous les clients" (2h)
				- tri par colonne (10h)
				- recherche par nom de client (2h)
				- interface des informations du client + modification (4h)
			
			b) Historique des pubs
				- interface + mise à jour au clic du nombre de pub(sur la liste des clients) (2h)
				- tri par colonnes (10h)

		TOTAL : 30 + 15*6 = 120h 
		(30h pour une rubrique et j'ai estimé que pour les 6 autres rubriques c'est la moitié du temps chacune)

	B- En FO
		1- Implémentation et choix des outils à utiliser (4h)

		2- Gestion des règles d'affichage du slider : date – statut (6h)

	TOTAL : 10h

	C- Notification expiration d'une pub  (8h)


GRAND TOTAL : 315h 


II- Rajout du sexe du candidat en FO

	1) Modification de l'insertion de CV (1h)

	2) Modification des CV ayant le titre Mademoiselle par Madame dans la base de données (1h)

	3) Modification de la présentation du CV dans Demandeur d'emploi (1h)

TOTAL : 3h


III- Limiter les choix du candidat
	1) Limiter le candidat à n'insérer que 3 numéro au maximum
	   BO+FO (4h)

	2) Limiter le candidat à ne choisir que 2 emplois recherchés
		- modification du type de champs "emploi recherché" + modification de l'enregistrement dans la base de données ,BO+FO
		  (4h)
		- modification du méthode d'affichage,BO+FO (4h)

  	3) Limiter le candidat à ne choisir que 9 logiciels maîtrisés,
		BO+FO (4h)

TOTAL : 16h


IV- Modification impression CV

	1) Mettre un slash entre les numéros (1h)

	2) Emploi recherché
		- Retour à la ligne automatique si le nom de l'emploi est trop long (3h)
		- ajuster à 2 lignes maximum le nom de l'emploi (3h)

	3) Modification l'affichage des logiciels maîtrisés (6h)

	4) Ajoute de coordonnées en bas de page (3h)

TOTAL : 16h


V- Ajout menu déroulant
	1- Front Office
	    Rubrique Annonce
			- Modification de texte (15mn)
			- Ajout de nouveau champs select (45mn)

	2- Back Office
		Rubrique Annonce
			- Modification de texte (15mn)
			- Ajout de nouveau champs select (45mn)

TOTAL : 2h



VI- Annonce-BO
	- Ajout de nouvelle information sur la liste des annonceurs avec nombre d'annonce d'un utilisateur (1h)

	- Création de nouvelle page liste annonce d'un utilisateur (2h)

	- Modification de la page détail annonce (1h)

TOTAL : 4h

VII- Cahier des charges du 25 Octobre 2017
	1- FO / Demandeur d’emploi
		a) Ajout d’une option de sélection du corps du métier
			- Mis en place d'un module de recherche en FO, dans l’onglet « demandeur d’emploi » au niveau des autres filtres. (2h)
			- Restriction et redirection du filtre par rapport au type de compte (2h)
			- Activation du filtre pour un recruteur venant de son espace client (4h)
		b) Notifications / recruteurs (3h)

	2- FO / Recruteur
		- Notification par email d'un recruteur pour déposer une offre (4h)
		- Création d'alerte (4h)
		- Notification de validation de cv à chaque matin (4h)
		- Prolonger la date limite de candidature (4h)
		- Envoie mail au recruteur une semaine avant la date limite de candidature des offres postées (3h)
		- Notifications commerciales itjobmada (4h)

	3- BO / Demandeur d’emploi -> Tous les emplois recherchés 
		- Ajout de nouveau colonne « Nbre de candidats » (2h)
		- Création de nouvelle page liste des CV (3h)

	4- FO / Demandeur d’emploi -> formulaire inscription
		- Dans le formulaire des candidats donner la possibilité à ces derniers de rentrer 2 vœux avec le premier en champs obligatoire et le reste 	facultatif. Attention bannir les caractères spéciaux (exemple anti slash). (2h)
		- Il faut faire se superposer les vœux des candidats pas sur une même ligne comme c’est le cas actuellement (1h)

	5- FO / Revendeur informatique 
		- Modification revendeur informatique (2h)

	6- BO / Liste de toutes les entreprises
		- Desactivation d'une entreprise (1h)

	7- FO / Espace Client
		- Dans espace Client / Recruteur/ Bouton « visualiser les offres postées »  Rajouter une colonne « Statut » après « date de sélection ». Dans cette colonne mettre le mot « gratuit » tant que le recruteur n’a pas dépassé les 5 CV. A partir du 6° CV y mettre « payant » (1h)

	8- FO / Les annonces
		- Possibilité d’ajouter /modifier/supprimer une photo, 2 photos par annonces (2h)
		- Filtre par type (1h)
		- Modification du titre d'annonce par rapport au choix d'annonceur (1h)
		- Ajout de deux champs dans le formulaire des annonces 		  (1h)
			a)	paraitra uniquement dans le site
			b)	dans le site et dans le journal 
		- Possibilité à l’annonceur de choisir le lieu de parution de son annonce comme pour les recruteurs (1h)

	9- BO / Devis
		- Modification du table, ajout de nouvelle colone « Nombre de caractères » (1h)

	10- FO/ Recruteur
		- Modification du secteur d’activité (1h)

	11- BO / Ecoles
		- Nous donner la possibilité de créer une école en BO       		  (1h)

	12- BO / Dîplômes
		- Nous donner la possibilité de créer des diplômes en BO 		  (1h)

	13- FO / Annonces
		- Quand un annonceur s’inscrit pour la première fois et qu’il a rempli son formulaire lui permettre de déposer directement son annonce sans lui demander de voir dans sa boite mail auparavant. (30mn)

	14- FO / Formulaire demandeur d’emploi
		- Rajouter les permis C et D dans le formulaire des candidats svp (1h)

	15- BO / FO Annonces
		- Mettre une vraie référence sur chacune des annonces. 		  (1h)

	16- Une annonce apparait 60 jours ou 30 jours ? 
			Je souhaiterais paramétrer cela en BO (2H)

	17- FO / Les demandeurs d’emploi
		+Serait il possible de mettre en violet la pastille du candidat dès qu’il sélectionne une autre région que  Analamanga dans son adresse quand il rempli son formulaire (1H)

TOTAL : 61h30min


VIII- OUTIL BACK OFFICE
	Liste annonce - Triage par simple clic sur le titre des colonnes (8h)
TOTAL : 8h
