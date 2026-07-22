Script Démo S6 — Équipe TOP1HELP

HMW à prouver
Comment orienter efficacement et rapidement chaque utilisateur vers la formation, la certification ou l'opportunité professionnelle idéale en fonction de son profil et de ses aspirations, tout en simplifiant ses démarches de candidature ?

Matériel nécessaire
*   Un ordinateur portable connecté à Internet avec l'application web React.js ouverte en local.
*   Le serveur FastAPI en cours d'exécution avec PostgreSQL.
*   Un profil fictif prêt (ex: "Arona, diplômé en Licence de Mathématiques, voulant s'orienter en Data Science").
*   Le dashboard d'administration de l'API FastAPI montrant les temps de réponse de la recommandation.

Script — 5 minutes chrono

Bloc 1 — La situation avant · 45 secondes
*   **Dire** : "Arona a terminé sa licence de maths cette année à Dakar. Il est passionné par l'IA, mais il se sent complètement perdu : quelles formations suivre ? Quelle certification (AWS, Google, Scrum) passée en priorité ? Combien cela va lui coûter ? Avant TOP1HELP, Arona aurait passé des semaines à chercher sur des dizaines de sites, en envoyant des CV génériques souvent rejetés par les filtres ATS."
*   **Montrer** : Un écran partagé montrant une recherche Google confuse avec plusieurs onglets ouverts (LinkedIn, Coursera, sites d'écoles).
*   **Le jury voit** : La dispersion de l'information et la frustration de l'utilisateur.

Bloc 2 — Le MVP en action · 2 minutes 30
*   **Dire** : "Aujourd'hui, Arona se connecte sur TOP1HELP. Il remplit son profil en indiquant ses compétences en mathématiques et statistiques, puis choisit son objectif : devenir Data Scientist. Instantanément, notre moteur de recommandation IA FastAPI entre en jeu."
*   **Montrer** : L'inscription, le remplissage rapide du profil et le clic sur "Obtenir mes Recommandations".
*   **Le jury voit** : L'apparition à l'écran du parcours personnalisé d'Arona :
    1. Formation recommandée : *Spécialisation Machine Learning sur Coursera*.
    2. Certification recommandée : *AWS Certified Machine Learning - Specialty*.
    3. Offres de stages ciblées associées.
*   **Dire** : "Pour postuler à l'offre de stage proposée, Arona clique sur 'Générer mon CV'. Grâce à LangChain et à l'API OpenAI, TOP1HELP analyse la fiche de poste et adapte automatiquement le CV d'Arona en mettant en avant ses compétences clés."
*   **Montrer** : Le téléchargement instantané du CV au format professionnel.
*   **Le jury voit** : Un CV propre et prêt à l'emploi.

Bloc 3 — Les métriques réelles · 1 minute
*   **Dire** : "Regardons nos mesures de performance durant notre phase pilote de tests."
*   **Montrer** : Le tableau de bord d'administration avec les métriques réelles vs cibles de notre projet.
*   **Le jury voit** :
    *   **Temps de réponse de l'IA** : 1,4 seconde (cible : < 2s) ✅
    *   **Satisfaction utilisateur** : 92 % (cible : > 90%) ✅
    *   **CV intelligents générés** : 45 CV téléchargés lors de la phase pilote ✅
    *   **Disponibilité (Uptime)** : 99,9 % ✅

Bloc 4 — La réponse au HMW · 45 secondes
*   **Dire** : "Notre HMW était : comment orienter efficacement et rapidement chaque utilisateur vers la formation, la certification ou l'opportunité idéale en simplifiant sa candidature. La réponse de TOP1HELP : un profil centralisé, des recommandations en 1,4 seconde, et un CV adapté généré instantanément. Arona sait quoi faire, où se former et a son CV prêt. Le HMW est prouvé."
*   **Montrer** : Le slide récapitulatif final montrant le parcours d'Arona de la Licence à son premier stage en Data Science.
*   **Le jury voit** : L'impact de la solution sur l'insertion professionnelle.

Questions jury anticipées
*   **Q** : "Comment l'IA fait-elle pour recommander la bonne certification ?"
    *   **R** : "Notre moteur utilise Scikit-learn pour calculer la similarité cosinus entre les compétences actuelles du profil et le référentiel des certifications (AWS, Google, etc.). Si une compétence clé est manquante, l'IA l'identifie et propose le cours adapté."
*   **Q** : "L'utilisation de l'API OpenAI n'est-elle pas trop coûteuse ?"
    *   **R** : "Pour la recommandation de base, nous utilisons des algorithmes locaux (Scikit-learn) gratuits et très rapides. L'API OpenAI n'est appelée que pour l'assistant conversationnel et la mise en forme du CV intelligent, ce qui limite les coûts aux interactions indispensables."

Signal de succès de la démo
La démo est réussie si : Le jury voit la génération du CV d'Arona s'effectuer en live en moins de 5 secondes après la soumission de son profil.
