Métriques de Succès — Équipe TOP1HELP

MVP
Une plateforme Web responsive (React.js/FastAPI) orientant les étudiants et jeunes diplômés vers les meilleures formations et certifications grâce à un moteur de recommandation IA local, et facilitant leurs candidatures avec un générateur de CV intelligent.

⭐ Métrique Nord
Indicateur : % d'utilisateurs actifs ayant postulé à une opportunité d'emploi ou démarré un cours recommandé par l'IA.
Valeur cible à 30 jours : 50% des utilisateurs actifs inscrits.
Comment mesurer : Suivi des clics sur les boutons de redirection ("Postuler" ou "Commencer la formation") enregistrés dans notre base de données PostgreSQL.

📈 Métriques de Progression

Métrique P1
Indicateur : Temps de calcul et de réponse du moteur de recommandation de l'API.
Valeur cible à 30 jours : < 2,0 secondes en moyenne.
Comment mesurer : Enregistrement automatique du temps d'exécution (en millisecondes) à chaque appel de l'endpoint `/api/recommend`.

Métrique P2
Indicateur : Taux de complétion et de téléchargement du CV Intelligent.
Valeur cible à 30 jours : 80% des profils complétés génèrent et téléchargent au moins un CV ou une lettre de motivation.
Comment mesurer : Compteur d'événements de téléchargement sur l'action "Générer PDF".

Métrique P3
Indicateur : Niveau d'engagement avec l'Assistant IA conversationnel.
Valeur cible à 30 jours : > 150 sessions de chat tenues avec au moins 3 échanges de messages.
Comment mesurer : Requête SQL comptabilisant le nombre de messages par ID de session dans la table `chat_sessions`.

🚨 Métriques d'Alerte

Alerte A1
Signal : Consommation de budget excessive sur les clés d'API OpenAI.
Seuil : Coût quotidien de l'API supérieur à 5,00 $ pendant plus de 2 jours consécutifs.
Action corrective : Implémenter un limiteur de débit (rate limiting) par adresse IP et restreindre la longueur maximale des tokens de sortie du chatbot.

Alerte A2
Signal : Dégradation du temps de réponse du moteur de recommandation.
Seuil : Temps moyen de réponse supérieur à 3,0 secondes mesuré sur 20 requêtes consécutives.
Action corrective : Optimiser la vectorisation des compétences ou mettre en place un système de cache Redis/mémoire locale pour les profils similaires.

Tableau de Bord S6
À la démo S6, nous présenterons ces 3 chiffres :
*   **Métrique Nord** : % d'utilisateurs engagés vers un cours/emploi (valeur réelle vs cible de 50%)
*   **Métrique P1** : Temps de calcul moyen des recommandations (valeur réelle vs cible de < 2,0s)
*   **Alerte A1** : Coût quotidien cumulé de l'API OpenAI (déclenchée ou non)
