# Multimedia

*  🔖 **Critères**

> Observons les critères d'accessibilité concernant le Multimedia

___

## 📑 [Critères](https://www.numerique.gouv.fr/publications/rgaa-accessibilite/methode/criteres/#topic)

Les critères des images sont disponibles sur le référentiel des critères.

### 🏷️ **[Contrôle](https://references.modernisation.gouv.fr/rgaa-accessibilite/glossaire.html#contrle-de-la-consultation-dun-media-temporel)**

Liste des fonctionnalités obligatoires de contrôle de la consultation

* L'objet multimédia doit toujours avoir les fonctionnalités suivantes, au minimum : lecture, pause ou stop.
* Si l'objet multimédia a du son, il doit avoir une fonctionnalité de contrôle du volume.
* Si l'objet multimédia a des sous-titres, il doit avoir une fonctionnalité de contrôle de l'apparition/disparition des sous-titres.
* Si l'objet multimédia a une audiodescription, il doit avoir une fonctionnalité de contrôle de l'apparition/disparition de l'audiodescription.

### 🏷️ **[Access](https://references.modernisation.gouv.fr/rgaa-accessibilite/glossaire.html#controle-son)**

* Chaque fonctionnalité doit être accessible par le clavier, via la touche de tabulation, et par la souris au moins.
* Chaque fonctionnalité doit être activable par le clavier et par la souris, au moins.

### 🏷️ **[Sous-Titre](https://references.modernisation.gouv.fr/rgaa-accessibilite/glossaire.html#soustitres-synchroniss-objet-multimdia)**

Texte des informations audio (paroles d'un personnage, bruit important pour comprendre l'action…) présentes dans un média temporel et affiché de manière synchrone avec le flux de l'objet multimédia.

Note 1 : pour différencier les sources sonores (différents personnages, voix off…), il est recommandé d'utiliser un mécanisme approprié (mise entre crochets, mise en italique, annonce explicite du type « voix off : … »).

Note 2 : il ne faut pas confondre le sous-titrage pour la traduction (kind="subtitles" en HTML5 par exemple) et le sous-titrage pour sourds et malentendants (kind="captions" en HTML5 par exemple). Ces deux types de sous-titrage poursuivent des buts différents. Seule la présence et la pertinence d'un sous-titrage pour sourds et malentendants permet d'être conforme.

### 🏷️ **Transcription**

Contenu textuel associé à un média temporel par la technique appropriée (texte codé en HTML ou dans un fichier texte qui se trouve dans la même page ou consultable suivant un lien). Ce contenu donne accès à l'utilisateur (de manière indépendante de la consultation de l'objet multimédia) à:
* La totalité de ce qui y est exprimé oralement ;
* Toutes les informations descriptives nécessaires à une compréhension équivalente de l'action.
* Ces informations textuelles doivent être présentées dans l'ordre chronologique de leur apparition dans le média temporel.

Note : la transcription textuelle doit se situer à l'extérieur de la balise object.