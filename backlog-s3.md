Backlog S3 — Équipe TOP1HELP

HMW Définitif
Comment orienter efficacement et rapidement chaque utilisateur vers la formation, la certification ou l'opportunité professionnelle idéale en fonction de son profil et de ses aspirations, tout en simplifiant ses démarches de candidature ?

User Stories MUST
(À construire obligatoirement en S3)

US-01
Story : En tant qu'Arona, je veux renseigner mon niveau d'étude, mes diplômes et mes compétences actuelles sur mon profil afin que la plateforme comprenne mon profil professionnel.
Priorité : MUST
Outil : Bolt.new (interface React.js) + FastAPI (PostgreSQL)
Effort : moyen
Adresse : Job To Be Done #1 — S'orienter
Critère d'acceptation : Les données du profil sont sauvegardées avec succès en base de données et affichées dans l'espace utilisateur.

US-02
Story : En tant qu'Arona, je veux recevoir instantanément des recommandations de certifications (AWS, Cisco, Scrum, etc.) adaptées à mon profil afin d'identifier mon plan de formation.
Priorité : MUST
Outil : FastAPI (calcul de similarité local avec Scikit-learn) + Bolt.new
Effort : moyen
Adresse : Gain Creator #1 — Moteur de recommandation de parcours IA local
Critère d'acceptation : Le moteur affiche les recommandations de certifications pertinentes à l'écran en moins de 2 secondes après la validation du profil.

US-03
Story : En tant qu'Arona, je veux générer un CV au format PDF optimisé pour les systèmes ATS à partir d'une offre d'emploi ciblée afin de simplifier mes démarches de candidature.
Priorité : MUST
Outil : Dify (agent de génération de documents OpenAI) + Bolt.new + API PDF
Effort : moyen
Adresse : Pain Reliever #2 — Générateur de CV/LM optimisé pour les filtres ATS
Critère d'acceptation : L'utilisateur peut copier-coller une offre et télécharger un CV PDF formaté avec ses compétences ajustées en moins de 5 secondes.

User Stories SHOULD
(À construire si le temps le permet)

US-04
Story : En tant qu'Arona, je veux poser mes questions de carrière en langage naturel ("Comment devenir Data Scientist ?") à un assistant d'orientation interactif afin d'obtenir des conseils immédiats.
Priorité : SHOULD
Outil : Dify (Agent conversationnel LLM) + Bolt.new
Effort : moyen
Adresse : Gain Creator #3 — Assistant d'orientation conversationnel
Critère d'acceptation : L'utilisateur reçoit une réponse structurée de l'assistant décrivant les cours, certifications et salaires associés à sa question.

US-05
Story : En tant qu'Arona, je veux m'inscrire et me connecter via mon compte Google afin d'accéder plus rapidement à la plateforme sans mémoriser de mot de passe.
Priorité : SHOULD
Outil : Bolt.new (Intégration Firebase / Google Auth API)
Effort : faible
Adresse : Pain Reliever #3 — Système d'authentification sécurisé
Critère d'acceptation : L'inscription et la connexion s'effectuent avec succès en un clic via le widget Google.

User Stories COULD
(Roadmap post-MVP)

US-06
Story : En tant qu'Arona, je veux effectuer des simulations d'entretien avec un recruteur virtuel IA afin de m'entraîner et de réduire mon stress.
Priorité : COULD
Outil : Dify (Agent de chat interactif avancé) + Bolt.new
Effort : élevé
Adresse : Gain Creator #2 — Simulateur d'entretien d'embauche interactif
Critère d'acceptation : Le chatbot interagit en simulant 3 questions d'entretien adaptées au poste et fournit un feedback détaillé à l'utilisateur à la fin.

Sprint S3 — Ce qu'on construit en priorité
*   Semaine 1 : US-01 (gestion et enregistrement du profil) + US-02 (recommandations de certifications via Scikit-learn sous FastAPI).
*   Semaine 2 : US-03 (générateur de CV intelligent via agent Dify) + US-04 (assistant conversationnel si avance).
*   Démo S6 : US-02 (recommandations en direct) et US-03 (téléchargement du CV généré par IA) démontrés en live sur l'application Web.
