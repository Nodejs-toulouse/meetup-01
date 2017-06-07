## Le fil rouge !
<br>
<span>Fonctionnement du fil rouge</span>
<br>
<span>L'application</span>
<br>
<span>La roadmap</span>
<br>
<span>Let's start !</span>

---

<div class="logo">
![Maxime Sangoï](assets/selfie.png)
</div>

Maxime Sangoï

`@MaximeSangoi`

---

### Fonctionnement du fil rouge

- But : rien ne vaut un peu de code :)
- Une application step by step

Note:
- Tenter de faire 1 événement meetup = 1 fil rouge
- Framework
- Authentification
- Modèles et BDD
- Déploiement
- Tests
- Sécurité

---

### Votre participation sera plus qu'appréciée
<br>
- Choix techniques
- Idées fonctionnelles 
- Vos contributions (PR, issues, etc)
<br>
![GIF-Together-Trump](assets/trump-together.gif)

Note:
- Vote dispo sur issues de meetup-01
- /
- Création de repo github avec l'appli (seulement les sources et les prez sont sur github actuellement)

---

### L'application
<br>
### Call For Proposals !

---?image=assets/cfp-liste-talks.png

---?image=assets/cfp-proposer-talk.png

---?image=assets/cfp-admin-liste-talks.png

---

### Let's start
<br>
![GIF-Lets-start](assets/jim-carey-typing.webp)

---

### Une stack 2017

- Yarn (ou NPM 5)
- Bulma | 
- Typescript |    

Note: 
- Forcément dernière version de Node : 8

---

### Typescript

- Développé par Microsoft
- Sur-ensemble de ECMAScript 2015 / ES6 (Node.js a déjà implémenté la plupart des features avec V8)
<span class="fragment">
> "The value in TypeScript is not in the writing less code. The value of TypeScript is in writing safer code." 
> - John Papa
</div>

Note:
- Anders Hejlsberg

---

### Typescript

- Types
- Interfaces
- Fonctionnalités d'ES2016 et + 
<br><br>
- Identification automatique des problèmes : paramètre de fonction manquant ou du mauvais type |
- Autocomplete / Intellisense |

Note:
- Fonctionnalités : Annotations/Decorators et async/await (ajouté par ECMA2017)

---

### Typescript

- Les libs externes ne sont pas écrites en TypeScript ! Comment utiliser leurs fonctions correctement ? 
<span class="fragment">
    <li> https://github.com/DefinitelyTyped/DefinitelyTyped </li>
</span>

Note: 
- Plus de 3000 types

---

### Présentation du starter
<br>
- Structure dossiers/fichiers
- Débogage

Note:
- Licence MIT
- Tsconfig.json
    - module : quel type de module après compilation: commonJS utilisé par node
    - noImplicityAny : strict typage
    - modeResolution : où aller chercher les modules 
        - relatif => moduleB.js ou moduleB/ with package.son
        - non-relatif => dans /nodes_modules/ des parents
- package.json
    - devDep
    - Dep
- npm start
- VS Code
    - settings.json
    - launch.json : que faire pour débogage
    - tasks.json
- Débogage

- Visual Studio Code => TypeScript + Debogage
- Package.json => Scripts + dépendances
- /src
- Démo Débogage 