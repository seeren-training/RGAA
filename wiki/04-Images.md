# Images

*  🔖 **Critères**

> Observons les critères d'accessibilité concernant les Images

___

## 📑 [Critères](https://www.numerique.gouv.fr/publications/rgaa-accessibilite/methode/criteres/#topic)

Les critères des images sont disponibles sur le référentiel des critères.

### 🏷️ **[Alt](https://www.numerique.gouv.fr/publications/rgaa-accessibilite/methode/glossaire/#alternative-textuelle-image)**

L'alternative est décrite par ordre de priorité suivante selon les éléments concernés.

*aria-labelledby*

```html
<img src="./dk982dp.png"  aria-labelledby="Nom accessible de l'image" />
```

*aria-label*

```html
<img src="./dk982dp.png"  aria-label="Nom accessible de l'image" usemap="#mymap" />

<map name="mymap">
  <area shape="rect"coords="0,1,2,3" alt="Nom accessible de la zone" />
</map>
```

*alt*

```html
<img src="./dk982dp.png"  alt="Nom accessible de l'image" />
```

*title*

```html
 <object data="./dk982dp.png" title="Nom accessible de l'image"></object> 
```

### 🏷️ **[Transcription](https://www.numerique.gouv.fr/publications/rgaa-accessibilite/methode/glossaire/#image-porteuse-d-information)**

Lorsqu’un bouton de formulaire, inséré avec l’élément `<button>`, ne contient qu’une image (balise `<img>`, `<object>`, `<embed>`, `<canvas>` ou `<svg>`), l’alternative de l’image est l’intitulé du bouton. 

### 🏷️ **[Background](https://www.numerique.gouv.fr/publications/rgaa-accessibilite/methode/glossaire/#image-de-decoration)**

Image n’ayant aucune fonction et ne véhiculant aucune information particulière par rapport au contenu auquel elle est associée. Exemples :
* Une image précédant chaque item d’une liste;
* Une image servant à caler la mise en page;
* Une image de coin arrondie pour habiller un bloc d’information;
* Une image d’illustration n’apportant aucune information nécessaire à la compréhension du texte auquel elle est associée.

Note : les balises possédant un attribut WAI-ARIA role="img" ne peuvent faire office d’image de décoration qu’à la condition qu’elles possèdent un attribut WAI-ARIA aria-hidden="true".


### 🏷️ **[Légende](https://www.numerique.gouv.fr/publications/rgaa-accessibilite/methode/glossaire/#legende)**

Lorsqu’une image est légendée il est nécessaire d’associer la légende de l’image à l’image par une relation de structure, de telle sorte que les technologies d’assistance puissent traiter l’image et sa légende comme un ensemble unique.

HTML5 propose d’associer une légende à une image via les éléments figure (l’ensemble de l’image et la légende) et figcaption (la légende).

```html
<figure>
    <img src="./dk982dp.png" alt="Nom accessible de l'image">
    <figcaption>Légende accessible de l'image</figcaption>
</figure>
```
Une image sans légende peut définir :

* Une image qui n’est pas insérée dans un élément figure;

* Une image insérée dans un élément figure sans élément figcaption.


### 🏷️ **[Captcha](https://www.numerique.gouv.fr/publications/rgaa-accessibilite/methode/glossaire/#captcha)**

Un CAPTCHA est un test utilisé pour distinguer un utilisateur humain d’un ordinateur. Le test utilise souvent des images contenant du texte déformé, mélangé avec d’autres formes ou utilisant des jeux de couleur altérées, que l’utilisateur est invité à retaper. D’autres formes de CAPTCHA peuvent être basées sur des questions logiques ou des extraits sonores.

L'indication d’information doit correspondre aux règles des images.