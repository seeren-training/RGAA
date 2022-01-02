# Formulaires

*  🔖 **Critères**

> Observons les critères d'accessibilité concernant les Formulaires

___

## 📑 [Critères](https://www.numerique.gouv.fr/publications/rgaa-accessibilite/methode/criteres/#topic)

Les critères des images sont disponibles sur le référentiel des critères.

### 🏷️ **Label**

Texte à proximité du champ de formulaire permettant d'en connaître la nature, le type ou le format des informations attendues. L'étiquette peut être associée au champ de formulaire de plusieurs manières :

* Par l'utilisation d'une balise label ;
* Par l'utilisation de la propriété WAI-ARIA aria-label ;
* Par l'utilisation d'une liaison entre le texte et le champ par la propriété WAI-ARIA aria-labelledby ;
* Par l'utilisation de l'attribut title.

### 🏷️ **Erreurs**

Ensemble des processus qui permettent de prévenir l'utilisateur des champs obligatoires, des indications de type ou de format attendus et des erreurs de saisie dans un formulaire. Ces contrôles de saisie peuvent être implémentés par l'auteur des contenus ou s'appuyer sur des attributs (comme required ou pattern), des propriétés WAI-ARIA (comme aria-required) ou des types de champ qui produisent de manière automatique des indications de saisie ou d'erreurs (comme les types url, email, date, time par exemple.

> Lorsqu'une page est renvoyée avec des erreurs de saisie le titre de la page doit comporter la mention « erreur sur le formulaire ».

### 🏷️ **Regrouper**

Dans un formulaire, ensemble des champs pouvant être regroupés par la nature des informations attendues. Le regroupement vise à identifier les champs devant être traités comme un ensemble.

* Trois champs successifs pour saisir une date (jour/mois/année).
* Champs successifs pour un numéro de téléphone.
* Un bloc destiné à saisir l'identité et l'adresse de l'utilisateur, lorsque le formulaire contient plusieurs blocs de contact.
* Un ensemble de boutons radio ou de cases à cocher qui se rapportent à une question.

Ces champs doivent être regroupés lorsque les intitulés de label ne sont pas suffisants pour informer l'utilisateur que les champs font partie d'un regroupement. HTML propose un dispositif natif par l'intermédiaire des éléments fieldset et legend.

### 🏷️ **Placeholder**

* Test 11.11.1 : Pour chaque formulaire, pour chaque erreur de saisie, les types et les formats de données sont-ils suggérés, si nécessaire ?
* Test 11.11.2 : Pour chaque formulaire, pour chaque erreur de saisie, des exemples de valeurs attendues sont-ils suggérés, si nécessaire ?

> Utilisation de placeholder : lorsque l'attribut placeholder est présent, il est susceptible d'être restitué à la place de l'attribut title. Par conséquent, lorsque ces deux attributs title et placeholder sont présents, ils doivent être identiques.