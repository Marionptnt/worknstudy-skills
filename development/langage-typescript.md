# TypeScript

> ❌ A travailler

> ✔️ Auto validation par l'étudiant

## 🎓 J'ai compris et je peux expliquer

- l'intéret de TypeScript dans l'IDE ✔️
- les types de bases ✔️
- comment et pourquoi étendre une interface ✔️
- les classes et les decorators ❌ / ✔️

## 💻 J'utilise

### Un exemple personnel commenté ✔️

//création de l'interface pour typer notre user
interface Iuser {
name: string; //propriétée de type string
age?: number; //propriétée de type number
birthday?: string
}

//on ajoute l'interface sur le paramètre user en indiquant
//un tableau de propriétées typées
const prettyPrintWilder = (users: Iuser[]) => {
//on récupére la liste des user
users.map((user) => {
//en affichant le name et age typé précédemment dans l'interface
//et passé en param de la fonction
console.log(`${user.name} is ${user.age} years old`);

    });

};

### Utilisation dans un projet ❌ / ✔️

[lien github](https://github.com/WildCodeSchool/structure-mobile.git) MOBILE
[lien github](https://github.com/WildCodeSchool/2203-wns-etchebest-tfs-front.git) FRONT
[lien github](https://github.com/WildCodeSchool/2203-wns-etchebest-tfs-back.git) BACK

Description :

### Utilisation en production si applicable❌ / ✔️

[lien du projet](...)

Description :

### Utilisation en environement professionnel ❌ / ✔️

Description :

## 🌐 J'utilise des ressources

### Titre

- lien
- description

## 🚧 Je franchis les obstacles

### Point de blocage ❌ / ✔️

Description:

Plan d'action : (à valider par le formateur)

- action 1 ❌ / ✔️
- action 2 ❌ / ✔️
- ...

Résolution :

## 📽️ J'en fais la démonstration

- J'ai ecrit un [tutoriel](...) ❌ / ✔️
- J'ai fait une [présentation](...) ❌ / ✔️
