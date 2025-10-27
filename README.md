# html-css

- [html-css](#html-css)
  - [HTML](#html)
    - [Objectifs](#objectifs)
    - [Démos](#démos)
  - [CSS](#css)
    - [Objectifs](#objectifs-1)
    - [Démos](#démos-1)
  - [Exercices](#exercices)
  - [Références](#références)
    - [Liens utiles](#liens-utiles)
    - [Ouvrages utiles](#ouvrages-utiles)

Apprendre à développer et intégrer des pages web structurées et accessibles, les fondamentaux en HTML et CSS.

## HTML

### Objectifs

- A quoi sert le HTML;
- Connaître les **éléments importants** pour **structurer** et donner une **sémantique** correcte aux documents : html, head, meta, body, header, footer, main, section, h1..h6, article, a, form, div;
- Comprendre le *flux* normal d'un document HTML (`position: static;`) et les propriétés des éléments `block`, `inline` et `inline-block` (propriété `display`);
- Comprendre comment altérer le flux normal du document via la propriété `position` : relative, absolute, fixed, sticky, float (images);
- Connaitre et utiliser les attributs génériques des éléments : `id`, `name` (input de formulaire), `class`;
- Faire de la veille : HTML évolue en permanence, éléments (plus ou moins) récemment introduits : [canvas](https://developer.mozilla.org/fr/docs/Web/HTML/Reference/Elements/canvas), [summary](https://developer.mozilla.org/fr/docs/Web/HTML/Reference/Elements/summary), [details](https://developer.mozilla.org/fr/docs/Web/HTML/Reference/Elements/details), [dialog](https://developer.mozilla.org/fr/docs/Web/HTML/Reference/Elements/dialog), [abbr](https://developer.mozilla.org/fr/docs/Web/HTML/Reference/Elements/abbr), etc.

### Démos

- [Les éléménts HTML **à connaître**](html-feuille-de-route.md);
- [Page HTML illustrant l'usage des balises principales](./demos/html-les-bases/);
- [Flux normal (et propriété `display`) et altéaration avec la propriété `position`](./demos/flux-html-normal-et-alteration/);

## CSS

### Objectifs

- A quoi sert le CSS ;
- [Styles en cascade](https://css-tricks.com/css-cascade-layers/#introduction-what-are-cascade-layers) dans l'arbre des noeuds et priorités des règles CSS (lesquelles s'appliquent) ?
- Connaître quelques propriétés de base ;
- Savoir utiliser les sélecteurs CSS ;
- Savoir Débuguer la pile de règles CSS via les *devtools* ;
- Savoir utiliser Flexbox (*flexible boxes*)
- Connaître Grid
- Comprendre ce qu'est le *responsive design* et l'usage des *media querries*.

### Démos

- [Flexbox](./demos/css-flexbox/) ;
- [Grid](./demos/css-grid/) ;
- [Utiliser les pseudo-éléments](./demos/pseudo-elements/)
- [Responsive font size](./demos/responsive-font-size-dynamique/)

## Exercices

- [Exercice d'intégration à partir d'un template donné](./exercices/tp-integration/), avec des **connaissances de base** en CSS (quelques sélecteurs, propriétés, *sans flexbox ni grid* !);
- [TP responsive 1 avec grid](./exercices/tp-responsive-grid/);
- [TP responsive 2](./exercices/tp-responsive/);

## Références

### Liens utiles

- [MDN Web Docs](https://developer.mozilla.org/fr/), **la documentation (semi)officielle** sur les technologies et standards du web;
- [Liste des éléments HTML5](https://developer.mozilla.org/fr/docs/Web/HTML/Element). Parcourir la doc en cas de besoin ou découvrir de nouveaux éléments utiles;
- [Markup Validation Service du W3C](https://validator.w3.org) pour valider son markup HTML avant de le mettre en production;
- [Structurer le document HTML](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Structuring_content) et [Flux normal du document](https://developer.mozilla.org/fr/docs/Learn_web_development/Core/CSS_layout/Introduction), sur la MDN;
- [Flexbox](https://developer.mozilla.org/fr/docs/Learn_web_development/Core/CSS_layout/Flexbox) et [Grid](https://developer.mozilla.org/fr/docs/Learn_web_development/Core/CSS_layout/Grids), sur la MDN;
- [Design responsive avec les media querries](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/CSS_layout/Media_queries), [syntaxe améliorée récemment](https://developer.mozilla.org/fr/docs/Web/CSS/CSS_media_queries/Using_media_queries#am%C3%A9liorations_syntaxiques_avec_la_sp%C3%A9cification_de_niveau_4), MDN
- [CSS Tricks](https://css-tricks.com/), excellent site sur le CSS. Notamment [le guide consacré à Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) et [celui consacré à CSS Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)

### Ouvrages utiles

> À avoir à portée, feuilleter, "vivre avec"

- [HTML5 Pocket Reference, 5th Edition](https://www.oreilly.com/library/view/html5-pocket-reference/9781449368777/), de Jennifer Robbins, publié chez O'Reilly Media, 2013. Pour se rafraichir la mémoire ou découvrir des éléments HTML utiles;
- [Know Your Onions: Graphic Design](https://www.amazon.com/Know-Your-Onions-Creative-Businessman/dp/9063692587), de Drew de Soto, publié chez Laurence King Publishing, 2014. Excellent condensé de conseils sur le design graphique, utile au design web;