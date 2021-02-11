# Liens

*  🔖 **Critères**

> Observons les critères d'accessibilité concernant les Liens

___

## 📑 [Critères](https://www.numerique.gouv.fr/publications/rgaa-accessibilite/methode/criteres/#topic)

Les critères des images sont disponibles sur le référentiel des critères.

### 🏷️ **[Intitulé](https://references.modernisation.gouv.fr/rgaa-accessibilite/glossaire.html#titre-de-lien)**

Contenu de l'attribut title d'un lien. Ce contenu ne doit être présent que s'il est nécessaire pour identifier la destination du lien de manière explicite. Un titre de lien doit reprendre l'intitulé de lien en y ajoutant des informations. Un titre de lien sera considéré comme non-pertinent dans les cas suivants :

* Le titre de lien est vide ;
* Le titre de lien est identique à l'intitulé du lien (Cf. note 1) ;
* Le titre de lien ne reprend pas l'intitulé du lien.

### 🏷️ **[Image/Icones](https://references.modernisation.gouv.fr/rgaa-accessibilite/glossaire.html#lien-image)**

Lien dont le contenu entre `a href="…"` et </a> est uniquement constitué d'une image. L'intitulé de lien pour un lien image est le contenu de l'alternative textuelle de l'image.

Un lien image peut être constitué :

* D'une image (balise img), l'alternative est le contenu de l'attribut alt ;
* D'une zone cliquable (balise area) possédant un attribut href, l'alternative est le contenu de l'attribut alt ;
* D'une image objet (balise object), l'alternative est contenue entre `object`;
* D'une image bitmap (balise canvas), l'alternative est contenue entre `canvas`;
* D'une image vectorielle (balise svg), l'alternative est contenue dans l'attribut aria-label ou la balise `title`.

### 🏷️ **[Evitement](https://references.modernisation.gouv.fr/critere-1211-dans-chaque-page-web-des-liens-devitement-ou-dacces-rapide-aux-groupes-de-liens-0)**

Les liens d'évitement doivent être présents et répondre à ces différents tests.

* Test 12.11.1 : Dans chaque page Web, un lien permet-il d'éviter chaque groupe de liens importants identifié ou d'y accéder ?
* Test 12.11.2 : Dans chaque page Web, un lien permet-il d'éviter la zone de contenu identifiée ou d'y accéder ?
* Test 12.11.3 : Dans chaque page Web, chaque lien d'évitement ou d'accès rapide est-il fonctionnel ?
* Test 12.11.4 : Dans chaque ensemble de pages, les liens d'évitement ou d'accès rapide vérifient-ils ces conditions ?
* Chaque lien est situé à la même place dans la présentation
* Chaque lien se présente toujours dans le même ordre relatif dans le code source
* Chaque lien est visible à la prise de focus de tabulation au moins

### 🏷️ **Bouton**

Les boutons `button` / `input` permettent de déclencher des actions.

Ils sont par exemple à employer pour soumettre des informations, afficher l’élément suivant ou précédent dans un carrousel, fermer une fenêtre modale, etc.

Ce ne sont pas des liens.