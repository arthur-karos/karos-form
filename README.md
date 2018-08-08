# Karos Form Challenge

Le karos form challenge est un petit exercise d'intégration d'un formulaire en Vue.js. Ce repo servira de template pour la suite de l'exercice.
L'enjeux de ce défi est de créer un formulaire constitué de plusieurs champs. Il doit répondre à une problèmatique technique ainsi qu'à des critères d'expérience utilisateurs .


## Exercice

Pour cet exercice vous devrez donc intégrer 4 champs input d'un formulaire Html, ainsi qu'un boutton qui vérifie les champs et qui effectue un `console.log()` ses valeurs.
Voici les différents champs à intégré :

##### Name

Ce champ est un input de text, il ne doit pas dépassé 30 caractères.

##### Email

Ce champ est un input de text, il contient une adresse email. Cette adresse doit être validé par une regex.

##### Password

Ce champ est un input de password, il doit renvoyé le password sous form de hashcode

##### Date

Ce champ est un input de date


Une fois le formulaire remplis, lorsque je clique sur le boutton, le log devrait ressembler à ça :
```json
{
  "name": "Arthur",
  "email": "donotreply@karos.fr",
  "password": 968540916,
  "date": "Wed Aug 08 2018"
}
```

### Bonus

Affiché l'output du `console.log()` directement sur la page mis en forme dans un élément HTML.


## Ressources:

Pour vous aidez dans l'exercice je vous conseils de vous appuyer sur ces liens :

[Vue.js](https://vuejs.org/v2/guide/)

[Ux Design For Form](https://uxdesign.cc/design-better-forms-96fadca0f49c)
