Contraintes MVP — Équipe TOP1HELP

Persona
Arona, 24 ans, jeune diplômé en Licence de Mathématiques, résidant à Dakar (Sénégal). Équipé d'un smartphone Android, d'un ordinateur portable, d'une connexion internet mobile et d'un compte Wave.

Contraintes Non Négociables

Contrainte 1
Critère : Le MVP DOIT renvoyer des recommandations IA de parcours (formations/certifications) en moins de 2 secondes.
Origine : Chapeau Blanc (besoin de rapidité pour surmonter le temps de recherche moyen de 6h).
Élimine : Les requêtes d'IA générative synchrones trop lourdes à chaque rechargement de page.

Contrainte 2
Critère : Le MVP DOIT s'appuyer sur un moteur de recommandation local (Scikit-learn / similarité cosinus) pour le catalogue.
Origine : Chapeau Noir (risque d'explosion des coûts liés aux appels de clés d'API OpenAI).
Élimine : L'utilisation exclusive de LLMs payants pour trier et filtrer les cours et examens.

Contrainte 3
Critère : Le MVP DOIT être développé sous forme d'application Web responsive (React.js) accessible via n'importe quel navigateur moderne.
Origine : Chapeau Blanc (accessibilité immédiate et réduction de la friction).
Élimine : Le déploiement d'une application mobile native sur les stores iOS/Android pour la version de lancement.

Fonctionnalités Éliminées
*   Application mobile native iOS/Android → Éliminée pour concentrer les ressources de développement S3 sur l'application Web fluide (React.js).
*   Module de paiement des formations → Éliminé parce que la facturation en ligne n'adresse pas le problème de l'orientation et ajoute une contrainte légale superflue.
*   Plateforme de recrutement interne pour les entreprises → Éliminée pour focaliser le MVP uniquement sur le matching de profil et l'employabilité du candidat.

Critère de Validation Final
Le MVP est valide si et seulement si : Arona peut saisir ses compétences, obtenir une recommandation de certification pertinente en moins de 2 secondes, et télécharger son CV optimisé au format ATS en direct.
