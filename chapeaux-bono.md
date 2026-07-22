# 🎩 Les Six Chapeaux de Bono - Analyse du Projet

## ⚪ Le Chapeau Blanc (Les Faits & Les Données)
Analyse objective de la situation : données chiffrées, faits vérifiables et informations disponibles.

* **Données connues :** Le chômage élargi au Sénégal a atteint 23,3% au quatrième trimestre 2025, en hausse de 3,3 points par rapport à la même période en 2024, et les jeunes sont les plus exposés, avec un taux de 27,4%. Côté équipement, le marché est porté par une pénétration des smartphones de 60,6%, et plus de 70% de la population a moins de 35 ans — soit exactement le public cible. Le smartphone est souvent, pour les jeunes, leur seul outil d'accès à l'éducation et à l'économie, ce qui valide une plateforme pensée « mobile d'abord ».
* **Informations à obtenir :** Quel est le pourcentage réel de lycéens de Terminale utilisant un smartphone personnel (vs partagé avec la famille) ? Quel budget internet mensuel moyen un élève peut-il consacrer ? Existe-t-il une base de données fiable et à jour des formations, certifications et débouchés au Sénégal pour alimenter les recommandations de l'IA ?

## 🔴 Le Chapeau Rouge (Les Émotions & Les Intuitions)
Expression libre des ressentis, pressentiments et réactions instinctives, sans besoin de justification logique.

* **Inquiétudes / Craintes :** Peur que les recommandations de l'IA soient perçues comme « froides » ou déconnectées de la réalité sénégalaise (métiers valorisés, pression familiale, contraintes financières). Crainte que les utilisateurs ne fassent pas confiance à un conseil donné par une machine plutôt que par un humain (parent, aîné, professeur).
* **Coups de cœur / Enthousiasme :** Forte conviction que rendre l'orientation accessible gratuitement depuis un téléphone peut réellement débloquer des jeunes paralysés par l'incertitude. Enthousiasme à l'idée qu'un rapport personnalisé donne un sentiment de contrôle et de confiance à un élève qui se sentait perdu.

## ⚫ Le Chapeau Noir (Le Pessimisme & Les Risques)
Identification des failles, des dangers, des limites juridiques, techniques et financières. Rôle de l'avocat du diable.

* **Risques majeurs :** Des recommandations erronées ou trop génériques (« hallucinations » de l'IA) qui orienteraient un élève vers une filière saturée ou inexistante localement — l'inverse de la mission du projet. Risque de dépendance à une IA sans validation humaine.
* **Contraintes techniques :** Qualité et fraîcheur des données sur les formations sénégalaises (une IE mal alimentée donne de mauvais conseils). Coût des appels à l'API du LLM à grande échelle. Fluctuation du réseau : les pannes fréquentes et la qualité fluctuante de l'Internet mobile peuvent rendre l'expérience frustrante.
* **Réglementation :** Le questionnaire collecte des données personnelles (âge, niveau, situation) — risque de non-conformité avec la loi sénégalaise sur la protection des données personnelles (CDP). Nécessité d'une politique de confidentialité claire, surtout si des mineurs (Terminale) sont concernés.

## 🟡 Le Chapeau Jaune (L'Optimisme & Les Opportunités)
Recherche des bénéfices, de la valeur ajoutée, des économies possibles et des raisons de croire au succès du projet.

* **Valeur ajoutée :** Centralise en un seul endroit une information aujourd'hui dispersée (formations, certifications, métiers) et la relie directement au profil de l'utilisateur — ce qu'aucun conseiller humain ne peut faire à grande échelle et gratuitement.
* **Opportunités :** S'inscrit parfaitement dans la dynamique « Sénégal Numérique 2025 » et la priorité gouvernementale donnée à l'emploi des jeunes. Le modèle est facilement adaptable à d'autres pays d'Afrique de l'Ouest ou à des partenariats (lycées, agences d'emploi, écoles privées qui souhaitent se référencer).

## 🟢 Le Chapeau Vert (La Créativité & Les Alternatives)
Génération d'idées neuves, de solutions originales aux problèmes soulevés par le chapeau noir et de pistes d'évolution.

* **Idées innovantes :** Intégrer un système de « validation » où chaque recommandation IA est confrontée à une base de données vérifiée d'établissements réels au Sénégal (l'IA propose, la base filtre). Ajouter des témoignages vidéo courts de professionnels sénégalais par métier pour humaniser et crédibiliser les résultats.
* **Alternatives techniques :** Prévoir un mode « léger » ou hors-ligne (mise en cache du questionnaire et affichage du rapport sans reconnexion) pour contourner l'instabilité réseau. Envisager une version accessible par un lien WhatsApp/USSD simplifié pour toucher ceux à faible connexion.

## 🔵 Le Chapeau Bleu (L'Organisation & La Synthèse)
Prise de hauteur sur le processus. Synthèse des autres chapeaux, définition de la stratégie et planification des prochaines étapes.

* **Constats clés :** La priorité absolue est la fiabilité des données et des recommandations (chapeau noir) : sans base de formations vérifiée et à jour, tout le reste s'effondre. Le second enjeu est la confiance de l'utilisateur envers l'IA (chapeau rouge), à traiter par la transparence et l'humanisation.
* **Décisions d'action :** (1) Constituer d'abord une base de données minimale mais fiable de formations/certifications/métiers sénégalais avant de développer l'IA. (2) Rédiger une politique de confidentialité conforme à la CDP. (3) Lancer un test d'utilisabilité sur un petit groupe d'élèves de Terminale réels pour valider le questionnaire et la clarté du rapport avant tout développement complet.
