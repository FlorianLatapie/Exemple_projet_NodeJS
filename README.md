# Comment créer son premier projet Node.js

## Introduction

Ce projet est un exemple de projet Node.js. Il est destiné aux novices qui souhaitent vérifier que leur environnement de développement est correctement installé.

[Source du tuto](https://code.visualstudio.com/docs/nodejs/nodejs-tutorial#_an-express-application)

## Les outils à installer

### Un éditeur de texte ou IDE

[Visual Studio Code](https://code.visualstudio.com/) : Simple et efficace, gratuit ([lien direct Windows](https://az764295.vo.msecnd.net/stable/6261075646f055b99068d3688932416f2346dd3b/VSCodeUserSetup-x64-1.73.1.exe))  
❗Smash le bouton `next` sur l'installeur

ou

[JetBrains WebStorm](https://www.jetbrains.com/fr-fr/webstorm/) : Très complet, gratuit si tu possèdes un compte étudiant JetBrains  
❗Bon si tu connais pas les outils JetBrains, tu peux te contenter de VSCode

ou

[Vim](https://www.youtube.com/watch?v=dQw4w9WgXcQ) : Pour les vrais hackers 😉

### Node.js

[Node.js](https://nodejs.org/fr/) : Version LTS ([lien direct Windows](https://nodejs.org/dist/v18.12.1/node-v18.12.1-x64.msi)) C'est un Framework qui permet de faire du JavaScript

### Git

**Prérequis :** Avoir un compte [GitHub](www.github.com)

[Git](https://git-scm.com/) : C'est un logiciel de gestion de version, il permet de travailler en équipe sur un projet. ([lien direct Windows](https://objects.githubusercontent.com/github-production-release-asset-2e65be/23216272/feedcd26-ed37-474b-9c28-bbe47ae4fb35?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAIWNJYAX4CSVEH53A%2F20221127%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20221127T142838Z&X-Amz-Expires=300&X-Amz-Signature=96b9684cb64a9b5777ce1e2560af67da7cd06d095dd52a728753fc3bc36342ba&X-Amz-SignedHeaders=host&actor_id=0&key_id=0&repo_id=23216272&response-content-disposition=attachment%3B%20filename%3DGit-2.38.1-64-bit.exe&response-content-type=application%2Foctet-stream))

[Github Desktop](https://desktop.github.com/) : C'est un logiciel graphique qui permet de gérer les dépôts Git. ([lien direct Windows](https://desktop.githubusercontent.com/github-desktop/releases/3.1.2-7cd66717/GitHubDesktopSetup-x64.exe)). N'oubliez pas de vous connecter avec votre compte GitHub avant de suivre le reste du tutoriel.

## Lancer le projet d'exemple "myExpressApp"

- Clonez le dépot en cliquant sur le bouton vert `Code` en haut à droite de la page, puis sur `Open with GitHub Desktop`

- Lancez un terminal dans le dossier que vous venez de cloner

```cmd
cd myExpressApp
```

- Installez les dépendances du projet

```cmd
npm install
```

- Lancez le serveur

```cmd
npm start
```

- Ouvrez votre navigateur à l'adresse [http://localhost:3000](http://localhost:3000) et vous devriez voir la page suivante :

IMAGE ICI

- Pour arrêter le serveur, appuyez sur `Ctrl+C` dans le terminal

## Créer son premier projet Node.js

- Créez un dossier dans lequel vous allez coder votre projet.
- Ouvrez un terminal dans ce dossier et tapez les commandes suivantes

```cmd
npm install -g npm@9.1.2
```

Cela installe la version 9.1.2 de npm (gestionnaire de paquets de Node.js)

```cmd
npm install -g express-generator
```

Cela installe un générateur de projet Express (un framework Node.js)

- Continuons vers la création du projet d'exemple

```cmd
express myExpressApp --view pug
```

Cela crée un projet Express dans le dossier `myExpressApp` avec le moteur de template Pug

- Installez les dépendances du projet

```cmd
cd myExpressApp
npm install
```

- Lancez le serveur

```cmd
npm start
```

- Ouvrez votre navigateur à l'adresse [http://localhost:3000](http://localhost:3000) et vous devriez voir la page suivante :

IMAGE ICI

- Pour arrêter le serveur, appuyez sur `Ctrl+C` dans le terminal

Vous pouvez ouvrir le projet dans votre editeur de texte ou IDE et commencer à coder !
