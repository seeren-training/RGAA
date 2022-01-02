# Sémantique

*  🔖 **Critères**

> Observons les critères d'accessibilité concernant la Sémantique

___

## 📑 [Critères](https://www.numerique.gouv.fr/publications/rgaa-accessibilite/methode/criteres/#topic)

Les critères des images sont disponibles sur le référentiel des critères.

### 🏷️ **Doctype**

Ensemble de données de référence qui permet aux agents utilisateurs de connaître les caractéristiques techniques des langages utilisés sur la page web (balise doctype).

### 🏷️ **Lang**

Indication de la langue de traitement principale du document qui peut être présente sur l'élément racine html ou sur chaque élément de la page concerné via les attributs lang et/ou xml:lang selon le schéma suivant :

*  Pour HTML jusqu'à la version 4.01 : attribut lang obligatoire, attribut xml:lang non supporté
* Pour XHTML 1.0 servi en "text/html" : attribut lang et xml:lang obligatoires
* Pour XHTML 1.0 servi en "application/xhtml+xml" : attribut xml:lang obligatoire, attribut lang recommandé
* Pour XHTML 1.1 : attribut xml:lang obligatoire, attribut lang non supporté
* Pour HTML5 : attribut lang obligatoire

### 🏷️ **Title**

Contenu de la balise title d'une page web permettant d'identifier de manière claire, concise et unique les contenus/la nature de la page (« Plan du site www.nomdusite.fr » pour une page présentant le plan du site web, par exemple).

### 🏷️ **Changement de langue**

L'indication des changements de langue est nécessaire pour indiquer aux technologies d'assistance de modifier la restitution vocale d'un élément. Les changement de langue concernent tous les contenus, y compris les valeurs de certains attributs comme title.

Note : il n'est pas possible d'indiquer des changements de langue dans une valeur d'attribut elle-même, dans ce cas le changement de langue est indiqué sur l'élément qui contient l'attribut. Par exemple un lien affecté d'un title en anglais devra comporter un attribut lang="en". Lorsque l'attribut contient plusieurs passages de texte dans des langues différentes, le critère est non applicable.

### 🏷️ **Sens de lecture**

Indique le sens de lecture du document ou d'un passage de texte via l'attribut dir, dir="ltr", par exemple. Les deux valeurs reconnues sont :
* ltr (left to right) indique un sens de lecture de gauche à droite ;
* rtl (right to left) indique un sens de lecture de droite à gauche.

> En l'absence d'indication de sens de lecture via l'attribut dir sur l'élément html, body, ou un des parents du texte analysé, le sens de lecture par défaut est de gauche à droite (valeur ltr).