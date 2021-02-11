# Prise en compte

*  🔖 **Recommandations**
*  🔖 **Évaluation**
*  🔖 **Suivi**

___

## 📑 Recommandations

![image](https://raw.githubusercontent.com/seeren-training/RGAA/master/wiki/resources/conformity.jpg)

La liste de recommandation à suivre correspond aux critères A, AA et AAA. Rappelons que le règlement européen estime le niveau AA suffisant.

La liste de recommandation concerne les éléments suivants:

* Images
* Cadres
* Couleurs
* Multimédia
* Tableaux
* Liens
* Scripts
* Éléments obligatoires
* Structuration de l'information
* Présentation de l'information
* Formulaires
* Navigation
* Consultation

[Critères](https://references.modernisation.gouv.fr/rgaa-accessibilite/criteres.html)

En fonction de la méthodologie de travail de l'entreprise, son support et sa vérification peut différer. Ces critères devrait faire partis de la **"Definition Of Done"** à respecter pour qu'une pull request soit fusionnée et la travail accepté.

Des guides par fonction sont proposés.

[Guide intégrateur](https://disic.github.io/guide-integrateur/)

[Guide developpeur](https://disic.github.io/guide-developpeur/)

___

## 📑 Évaluation

Afin de vérifier si un affichage est conforme aux critères selon un niveau d’accessibilité il faut élaborer une stratégie de test.

A la façon d'un recettage, une grille pour chaque critère est disponible au format Excel. Les ressources vers la grille de test sont disponibles à sur la section référence modernisation:

[Modèle de grille d’audit RGAA version 4,](https://www.numerique.gouv.fr/uploads/rgaa/rgaa4.0.modele-de-grille-d-audit.ods)

Le gouvernement nous oriente vers différents outils permettant d'effectuer les test: 

[Méthodologie de test](https://www.numerique.gouv.fr/publications/rgaa-accessibilite/methodologie-test/)

Une fois en production ou en préproduction il existe des services en ligne évaluant automatiquement le niveau d'accessibilité.

> A la place de perdre du temps à effectuer des vérification manuelles hors contexte de développement, j'insiste sur le fait qu'investir sur des tests d'intégration est opportun afin que pendant le développement, une automatisation indique le niveau d’accessibilité.

___

## 📑 Suivi

### 🏷️ **[Chef de projet](https://disic.github.io/guide-chef_projets/2-loi.html)**

Le chef de projet peut être en charge d'accepter et de valider le travail effectué, si c'est le cas il peut demander pour chaque fonctionnalité une grille d'évaluation et la passer en revue ou effectuer le test lui même avant d'accepter la fonctionnalité ou de déclarer des issues.

Pour les chefs de projet un guide est disponible, le suivi de l'accessibilité est décrit dans un guide.

[Guide chef de projets](https://disic.github.io/guide-chef_projets/)

Les obligations sont les suivantes:

* Mettre en place et publier un schéma pluriannuel ne pouvant pas dépasser 3 ans et décliné en plans annuels.
* Afficher sur la page d’accueil l’indication de conformité ou de non-conformité au RGAA.
* Permettre aux utilisateurs de signaler les manquements aux règles d’accessibilité du service.

Un modèle de déclaration de conformité est disponible.

[Déclaration De Conformite](http://disic.github.io/rgaa_modeles_documents/declaration-de-conformite.html#)

### 🏷️ **[Référent](https://references.modernisation.gouv.fr/4223-designation-dun-referent-accessibilite-0)**

La direction doit nommer un membre de l’encadrement de l’organisme en tant que " référent accessibilité ". Ce référent qui, nonobstant d’autres responsabilités, doit avoir la responsabilité et l’autorité en particulier pour :

* Assurer que les processus nécessaires à la prise en compte de l'accessibilité sont établis, mis en œuvre et entretenus.
* Rendre compte à la direction du niveau d'accessibilité et de tout besoin d’amélioration.
* Assurer que la sensibilisation aux exigences d'accessibilité dans tout l’organisme est encouragée.
* Être le point d'entrée unique sur les sujets d'accessibilité numérique.

> Le chef de projet et le référent technique peuvent être la même personne.

### 🏷️ **[Principes](http://references.modernisation.gouv.fr/accessibilite-numerique)**

Malgré l’évaluation et la conformité aux critères il est là pour s'assurer que 4 principes sont respectés.

Principe 1 : un site perceptible

* Faire en sorte que chaque information soit perceptible par tout utilisateur, et par tous les sens (équivalents textuels pour tout contenu non textuel afin de permettre une synthèse vocale ou une transcription brailles, grands caractères, audio-description, langage simplifié…).
* Proposer des versions de remplacement aux médias audio, vidéo ou animations Flash. Créer un contenu présentable de différentes manières sans perte d’information (ex. : mise en page simplifiée).

Principe 2 : un site utilisable

* Rendre toutes les fonctionnalités accessibles au clavier.
* Laisser à l’utilisateur suffisamment de temps pour lire et utiliser le contenu.
* Ne pas concevoir de contenu susceptible de provoquer des crises.
* Fournir à l’utilisateur des éléments d’orientation pour naviguer, trouver le contenu et se situer dans le site.

Principe 3 : un site compréhensible

* Rendre le contenu textuel lisible et compréhensible.
* Faire en sorte que les pages apparaissent et fonctionnent de manière prévisible.
* Aider l’utilisateur à éviter et à corriger les erreurs de saisie.

Principe 4 : un site robuste

* Optimiser la compatibilité avec les agents utilisateurs actuels et futurs, y compris avec les technologies d’assistance.

> Le respect de ces principes et leur adoption et l'objectif du référent.