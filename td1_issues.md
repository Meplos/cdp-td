# TD1 - Issues / Features / User Story

## Cahier des charges du CNRS

Lisez le cahier des charges du CNRS et considérez que vous êtes une jeune start-up dont le business consiste à réaliser des projets de développement.

**Q1 -** Quelles sont les parties du cahier des charges que votre start-up est capable de réaliser ?

- #1 : Formulaire en ligne permettant la création d'une fiche sythétique de leur ateliers (titre, thème, type, date, laboratoire, lieux, durée capacité).
- #2 : Listage des différent attelier et possibilité d'ajouter des filtre (Thème, date, ect..)
- #3 Modification/suppression de crénaux d'annimation (de manière protégé)
- #4 Accès en temps réel des infos des atelier de la part des enseignant.
- #5 Inscription des enseignant à un atelier
- #6 Inscription des enseignant.
- #7 Récapitulatif des atelier (atelier, contact, horraire).
- #8 Espace du site public (visite ) et privé (doit être authentifié).
- #9 Les différente rubrique de fin

**Q2 -** Quelles sont les parties du cahier des charges que votre start-upn’est pas capable (ou ne souhaite pas) réaliser ?

- Carte géographique des lieux
- Les récapitulatif des trajet
- Intervention sous 24h.

## User Story (1ere phase)

Une société partenaire a déjà réalisé une partie du BackLog :

- US1 : **En tant que** visiteur, **je souhaite** m’enregistrer comme laboratoire, **afin de** gérer mes ateliers.
- US2 : **En tant que** laboratoire, **je souhaite** ajouter un nouvel atelier, **afin de** permettre aux enseignants de s’y inscrire.
- US3 : **En tant que** laboratoire, **je souhaite** lister mes ateliers, **afin de** les modifier ou les supprimer.
- US4 : **En tant que** laboratoire, **je souhaite** pouvoir visualiser un de mes ateliers, **afin de** voir ce que les enseignants voient.
- US5 : **En tant que** laboratoire, **je souhaite** pouvoir me déconnecter.
- US6 : **En tant que** laboratoire, **je souhaite** activer/ désactiver un ateliers, **afin de** permettre aux enseignants de s’y inscrire ou de ne pas s’y inscrire.
- US7 : **En tant que** laboratoire, **je souhaite** exporter un PDF de mes ateliers, **afin de** faire ma propre promotion.
- US8 : **En tant que** laboratoire, **je souhaite** que mes ateliers soient sauvegardés dans la base de données, **afin de** pouvoir les retrouver si le serveur redémarre.
- US9 : **En tant que** laboratoire, **je souhaite** que l’interface soit agréable à utiliser, **afin de** faciliter l’édition des ateliers.
- US10 : **En tant que** laboratoire, **je souhaite** que l’interface soit réalisée avec Bootstrap, **afin de** pouvoir l’utiliser sur des terminaux mobiles.
- US11 : **En tant que** visiteur, **je souhaite** visionner une carte géographique localisant les ateliers **afin de** pouvoir me préparer un itinéraire.
- US12 : **En tant que** client, **je souhaite** qu'une maintenance corrective soit mise en place pendant 12 mois, 24/7 **afin de** garantir le bon fonctionnement de la solution.

**Q3 -** Les issues (user story) sont-elles identifiées de manière unique ?

Oui elles ont chacune un identifiant.

**Q4 -** Les issues (user story) sont-elles précises ? En outre pouvez-vous décrire ce qu’est un « laboratoire » ? Seriez-vous capable de décrire une validation pour chacune d’entre elle ?

laboratoire doit être modifié en animateur.

**Q5 -** Les issues (user story) sont-elles homogènes ? Est-ce qu’elles décrivent toutes des fonctionnalités (feature) ? Est-ce qu’elles ciblent toutes un besoin exprimé dans le cahier des charges ?

Non certaines parle de feature d'autre de maintenance, d'autre de technologie.

**Q6 -** Qualifiez les issues en précisant leur type, leur importance et leur difficulté.

| ID   | Type        | Importance | Difficulté |
| ---- | ----------- | ---------- | ---------- |
| US1  | Feature     | Forte      | 1          |
| US2  | Feature     | Forte      | 1          |
| US3  | Feature     | Moyenne    | 1          |
| US4  | Feature     | Faible     | 1          |
| US5  | Feature     | Forte      | 1          |
| US6  | Feature     | Forte      | 1          |
| US7  | Feature     | Moyenne    | 3          |
| US8  | Performance | Forte      | 1          |
| US9  | Performance | Moyenne    | 3          |
| US10 | Performance | Faible     | 3          |
| US11 | Feature     | Faible     | 5          |
| US12 | NotFeature  | /////////  | ////////// |

## A faire

Préparez le Backlog complet de ce cahier des charges pour la semaine prochaine.

Utilisez un outil comme IceScrum ou Jira et saisissez votre BackLog.
