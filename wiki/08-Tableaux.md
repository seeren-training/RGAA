# Tableaux

*  🔖 **Critères**

> Observons les critères d'accessibilité concernant les Tableaux

___

## 📑 [Critères](https://www.numerique.gouv.fr/publications/rgaa-accessibilite/methode/criteres/#topic)

Les critères des images sont disponibles sur le référentiel des critères.

### 🏷️ **[Résumé](https://references.modernisation.gouv.fr/rgaa-accessibilite/glossaire.html#rsum-de-tableau)**

La spécification propose plusieurs méthodes pour lier un résumé à un tableau (tableau lié à un passage de texte avec aria-describedby, tableau groupé via figure avec le résumé en texte adjacent, tableau groupé avec figure avec le résumé dans un élément `figcaption`, résumé dans un élément details dans l'élément `caption`).

### 🏷️ **[Liaison](https://references.modernisation.gouv.fr/rgaa-accessibilite/glossaire.html#entte-de-colonne-ou-de-ligne)**

#### En-tête de colonne ou de ligne

Contenu d'une cellule dans un tableau de données (la première cellule d'une colonne ou d'une ligne, généralement) qui sert d'intitulé pour la totalité ou une partie des cellules de la colonne ou de la ligne. Une colonne ou une ligne peut contenir plusieurs en-têtes (en-tête intermédiaire). Les en-têtes doivent utiliser une balise `th`.

### 🏷️ **[Scope](https://developer.mozilla.org/fr/docs/Apprendre/HTML/Tableaux/Advanced)**

Aux balises th, sujet de l'article précédent, ajoutons l'attribut scope. Il peut être mentionné dans un élément th pour indiquer précisément à un lecteur d'écran si la cellule contient un en-tête de colonne ou de ligne — par exemple, sommes‑nous dans un en-tête de ligne, ou de colonne ? En revenant à notre exemple d'enregistrement de dépenses vu plus tôt, il est possible de définir sans ambiguïté un en-tête de colonne comme étant un en-tête de colonne ainsi.
