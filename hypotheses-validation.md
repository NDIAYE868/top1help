Hypothèses de Validation — Équipe TOP1HELP

HMW Définitif
Comment orienter efficacement et rapidement chaque utilisateur vers la formation, la certification ou l'opportunité professionnelle idéale en fonction de son profil et de ses aspirations, tout en simplifiant ses démarches de candidature ?

Hypothèses CRITIQUES
(Si fausse → le MVP ne fonctionne pas)

Hypothèse C1
Affirmation : Nous croyons que les recommandations de parcours (formations/certifications) générées par notre algorithme local de similarité sont considérées comme pertinentes et actionnables par les étudiants.
Indicateur : Nous le saurons si 4 étudiants sur 5 évaluent le parcours proposé comme "très pertinent" ou "pertinent" lors de la première démonstration.
Méthode : Entretien terrain avec démonstration de prototype papier/maquette
Qui valide : Étudiants de Master 1 à l'université Swiss UMEF Dakar
Délai S3 : 7 jours (Semaine 1)

Hypothèse C2
Affirmation : Nous croyons que le coût d'appel à l'API OpenAI pour la génération de CV et l'assistant IA peut être maintenu en dessous de 0,05 $ par requête grâce à l'optimisation des prompts et de la mise en cache.
Indicateur : Nous le saurons si la facturation moyenne sur 100 générations de CV tests ne dépasse pas 5,00 $.
Méthode : Tests techniques et monitoring de consommation API
Qui valide : Serigne Arona SENE (Lead Dev)
Délai S3 : 10 jours (Semaine 2)

Hypothèses IMPORTANTES
(Si fausse → l'expérience est dégradée mais le MVP reste utilisable)

Hypothèse I1
Affirmation : Nous croyons que les CV générés par TOP1HELP obtiennent un taux de passage supérieur à 80% lors de l'analyse par les logiciels de tri automatique (ATS) des recruteurs dakarois.
Indicateur : Nous le saurons si les fichiers PDF générés obtiennent un score de lisibilité de plus de 80% sur des outils de test ATS de référence.
Méthode : Test de comptabilité ATS automatisé
Qui valide : Experts en recrutement ou logiciels de simulation ATS
Délai S3 : 14 jours (Semaine 2-3)

Hypothèses SECONDAIRES
(À valider après le MVP)

Hypothèse S1
Affirmation : Nous croyons que les utilisateurs se connecteront à l'assistant d'orientation conversationnel de manière récurrente (au moins 3 fois par mois) pour affiner leur projet professionnel.
Indicateur : Nous le saurons si nous enregistrons un taux d'utilisation récurrente supérieur à 30% sur nos 50 premiers utilisateurs actifs à J+30.
Méthode : Analyse des logs de la base de données PostgreSQL
Qui valide : Utilisateurs actifs de la plateforme
Délai S3 : 30 jours (Roadmap post-MVP)

Priorité de Validation S3
La première chose à tester en S3 : Soumettre une simulation de parcours recommandé par notre algorithme de matching de compétences à un panel de 5 étudiants pour s'assurer que les cours et examens suggérés correspondent à leurs ambitions réelles de carrière.
