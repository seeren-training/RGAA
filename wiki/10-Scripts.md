# Scripts

*  🔖 **Critères**

> Observons les critères d'accessibilité concernant les Scripts

___

## 📑 [Critères](https://www.numerique.gouv.fr/publications/rgaa-accessibilite/methode/criteres/#topic)

Les critères des images sont disponibles sur le référentiel des critères.

### 🏷️ **[Compatibles](https://references.modernisation.gouv.fr/rgaa-accessibilite/glossaire.html#compatible-avec-les-technologies-dassistance)**

Un contenu ou une fonctionnalité doit être compatible avec les technologies d'assistance des utilisateurs ainsi qu'avec les fonctions d'accessibilité des navigateurs et des autres agents utilisateurs via une API d'accessibilité.

Cela concerne, à la fois, la technologie, ses fonctionnalités et ses usages :

* La façon dont la technologie web est utilisée doit être compatible avec les technologies d'assistance des utilisateurs. Cela signifie que la façon dont la technologie est utilisée a été testée dans une perspective d'interopérabilité avec des utilisateurs des technologies d'assistance dans la ou les langues du contenu ;
* La technologie fonctionne de façon native dans des agents utilisateurs largement distribués qui sont, eux-mêmes, compatibles avec l'accessibilité (comme HTML et CSS) ou avec un module d'extension largement distribué qui est, lui-même, compatible avec l'accessibilité.

La vérification de la compatibilité avec les technologies d'assistance nécessite de réaliser un certain nombre de tests spécifiques à la technologie utilisée, par exemple :
* Vérifier le nom, le rôle, le paramétrage et les changement d'états des composants d'interface ;
* Vérifier que la restitution d'un composant d'interface est correcte pour la ou les technologies d'assistance utilisées.

### 🏷️ **[Utilisables au clavier](https://references.modernisation.gouv.fr/rgaa-accessibilite/glossaire.html#accessible-et-activable-par-le-clavier-et-la-souris)**

* Un composant d'interface (lien, bouton, élément cliquable dans Flash…) est accessible au clavier et à la souris lorsque l'utilisateur peut prendre, indifféremment, le focus par le pointeur de la souris ou la touche tabulation.
* Un composant d'interface (lien, bouton, élément cliquable dans Flash…) est activable au clavier et à la souris lorsque l'utilisateur peut enclencher, indifféremment, l'action prévue par le composant d'interface par le clic de la souris ou la touche entrée du clavier.
* Attention : pour certains composants d'interface comme les sliders (bouton coulissant ou rotatif…), il n'est pas possible de contrôler le composant par la seule touche d'entrée. Dans cette situation, d'autres touches (comme les touches de direction) peuvent être utilisées.

Dans le référentiel, l'expression « contrôlable par le clavier et la souris » se rapporte également à la présente définition.

> Note importante : le recours à certaines technologies peut rendre la gestion du focus trop complexe ou trop instable pour ne reposer que sur la tabulation, les touches de direction et la touche entrée.

Dans ce cas, la mise à disposition de raccourcis clavier peut être la seule solution pour rendre le composant utilisable.

Le critère peut être considéré comme conforme à la condition que les raccourcis clavier utilisés soient correctement documentés et qu'ils soient fonctionnels quelle que soit la position du focus dans l'interface.

### 🏷️ **[Intégration ARIA](https://developer.mozilla.org/fr/docs/Accessibilit%C3%A9/ARIA)**

L'ensemble de l'affichage produit par les scrpts doit utiliser les attributs ARIA

### 🏷️ **[Application des profils du W3C](https://validator.w3.org/#validate_by_uri)**

Le script doit respecter les standards du W3C et passe au validator.