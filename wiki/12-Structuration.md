# Structuration

*  🔖 **Critères**

> Observons les critères d'accessibilité concernant la Structuration

___

## 📑 [Critères](https://www.numerique.gouv.fr/publications/rgaa-accessibilite/methode/criteres/#topic)

Les critères des images sont disponibles sur le référentiel des critères.

### 🏷️ **Liste**

Suite d'éléments pouvant être regroupés sous la forme d'une liste structurée ordonnée, non ordonnée ou de définition. Par exemple la suite des liens d'un menu de navigation est une liste de liens non ordonnée, les différentes étapes d'une procédure est une liste d'éléments ordonnés, le couple terme/définition d'un glossaire est une liste de définition. En HTML, les listes utilisent les balises suivantes :

* Liste ordonnée : balises ol et li (chaque élément de la liste est affecté d'un marqueur indexé) ;
* Liste non ordonnée : balises ul et li (chaque élément de la liste est affecté d'un marqueur non-indexé ;
* Liste de définition : balises dl, dt (terme à définir) et dd (définition).

### 🏷️ **Citation**

* Test 9.6.1 : Dans chaque page web, chaque citation courte utilise-t-elle une balise q ?
* Test 9.6.2 : Dans chaque page web, chaque bloc de citation utilise-t-il une balise blockquote ?

### 🏷️ **Titres**

Élément HTML (balise h) à 6 niveaux de hiérarchie (de h1 pour le titre le plus important à h6 pour le moins important) permettant de structurer l'information d'un contenu web.

La hiérarchie entre les titres doit être respectée dans une page web et les degrés de titre ne peuvent pas être sautés (un titre h3 ne peut pas venir directement après un titre h1, par exemple). Par contre, la hiérarchie ne doit pas obligatoirement débuter par un h1. Même si cet usage n'est pas encouragé, il est considéré comme conforme de débuter la hiérarchie des titres d'une page par un autre niveau que le niveau 1.

Dans chaque page web, il doit y avoir un titre h1, au moins.

### 🏷️ **Role**

* La zone d'en-tête de la page est structurée via une balise header.
* Les zones de navigation principales et secondaires sont structurées via une balise nav.
* La balise nav est réservée à la structuration des zones de navigation principales et secondaires.
* La zone de contenu principal est structurée via une balise main.
* La structure du document utilise une balise main unique.
* La zone de pied de page est structurée via une balise footer.

Il est conseillé d'utiliser les rôles de façon complémentaire afin de compléter ou requalifier des éléments: https://disic.github.io/guide-developpeur/9-utiliser-aria.html