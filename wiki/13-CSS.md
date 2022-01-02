# CSS

*  🔖 **Critères**

> Observons les critères d'accessibilité concernant le CSS

___

## 📑 [Critères](https://www.numerique.gouv.fr/publications/rgaa-accessibilite/methode/criteres/#topic)

Les critères des images sont disponibles sur le référentiel des critères.

### 🏷️ **Unité**

Valeur attribuée aux polices de caractères présentes sur une page web. Pour les contenus web, les tailles de caractères doivent être définies avec des unités relatives (%, em, rem, vw, vh, vmin ou vmax) ou des mots clés (xx-small, x-small, small, medium, large, x-large, xx-large, smaller, larger).

> L'utilisation du pixel (px) est proscrite.

### 🏷️ **[Background](https://www.w3.org/Translations/WCAG20-fr/#visual-audio-contrast-visual-presentation)**

* Test 10.8.1 : Pour chaque bloc de texte contenu dans une balise HTML, la couleur de fond est-elle contrôlable par l'utilisateur ?
* Test 10.8.2 : Pour chaque bloc de texte contenu dans une balise HTML, la couleur de police est-elle contrôlable par l'utilisateur ?
* Test 10.8.3 : Pour chaque bloc de texte contenu dans une balise object, embed, svg ou canvas, la couleur de fond est-elle contrôlable par l'utilisateur ?
* Test 10.8.4 : Pour chaque bloc de texte contenu dans une balise object, embed, svg ou canvas, la couleur de police est-elle contrôlable par l'utilisateur ?

### 🏷️ **Focus**

La prise de focus est l'état renvoyé par un élément qui reçoit l'attention suite à une action de l'utilisateur. Il y a trois moyens en HTML de donner le focus à un élément :

* En activant l'élément par un dispositif de pointage (souris) ;
* En activant l'élément par la touche tabulation ;
* En activant l'élément par un raccourci clavier (accesskey).

Certains éléments reçoivent naturellement le focus, par exemple : a, area, button, input, object, select, label, legend, optgroup, option et textarea. Le comportement de l'élément, lors de la prise de focus, dépend de sa nature ; un lien, par exemple, devra être activé après la prise de focus (sauf utilisation de script). En revanche, un élément de formulaire, comme textarea, devra autoriser la saisie suite à la prise de focus. Les éléments label et legend ne reçoivent la prise de focus que via le pointeur souris. Pour l'élément label, le comportement attendu est de transférer la prise de focus sur l'élément qui lui est associé.