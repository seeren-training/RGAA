# Navigation

*  🔖 **Critères**

> Observons les critères d'accessibilité concernant la Navigation

___

## 📑 [Critères](https://www.numerique.gouv.fr/publications/rgaa-accessibilite/methode/criteres/#topic)

Les critères des images sont disponibles sur le référentiel des critères.

### 🏷️ **Evitement**

Des liens d'évitement accessible à chaque moment doivent être présents.

### 🏷️ **Ordre de tabulation**

Ordre dans lequel le focus se déplace (vers un élément suivant ou vers un élément précédent). L'ordre naturel est celui qui est implémenté via le code source. Lorsqu'il est modifié par l'utilisation de l'attribut TabIndex ou par l'utilisation d'une commande JavaScript, c'est l'ordre modifié qui fait référence.

Attention : lorsqu'un élément initie un changement dans la page (changement de contexte, gestion de zones cachées, ajout de contenu, gestion de champs de formulaire…) il est nécessaire d'activer l'élément qui initie le changement pour tester la cohérence de l'ordre de tabulation.

### 🏷️ **[TabIndex](https://developer.mozilla.org/fr/docs/Web/HTML/Attributs_universels/tabindex)**

Les liens doivent être accessibles au clavier et un élément ne doit pas avoir de valeur négative pour TabIndex