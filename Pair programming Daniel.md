# Pair programming Daniel

27.10.2017 - Pair Programming em JS com o Daniel

### Basic Tools

- [ ] JavaScript
- [ ] NodeJS
- [ ] npm - Node Package Manager

### Build Tools

- [ ] Yarn - Node Package Manager
- [ ] Gulp - Task Manager
- [ ] Webpack - Web Bundler

### Front-end Framework

- [ ] ReactJS
- [ ] Bootstrap 4

### Other Tools

- [ ] Git
- [ ] GitHub
- [ ] Linux Command Line/terminal
- [ ] Bash/zsh - Emuladores de prompt de comando
- [ ] Http Server - Protocolo de communicação
- [ ] API / Rest API

# Project



O objetivo do projeto é fazer uma **aplicação web** em **ReactJS** com um **servidor http** que tenha um campo de texto onde seja possível digitar o **nome de um usuário do github**. A aplicação deve ir na **api do github** (api.github.com), se o usuário existir, **pegar os dados** e exibir um card com sua **foto**, **nome** e **link para o perfil**, caso o usuário não exista, exibir um **alerta abaixo do campo de busca** informando tal erro. O **botão de busca** deve ficar **desativado** e com um **loader** enquanto a **requisição não é respondida**.

A cada **novo nome de usuário**, a aplicação deve **adicionar mais um card** à lista.



## Setup

### Basic Tools

1. Install a **GNU/Linux**
2. Create a **[Github](github.com)** account and add a photo
3. Install **node** and **npm** in your GNU/Linux.
   `sudo pacman -S node npm` 
4. install **git** in your linux to **control versions** of your code.
   `sudo pacman -S git`

### Build Tools

1. Install **yarn** to optimize your workflow.
   `npm install -g yarn`
2. Install **Gulp** to manage your tasks like: **compilation**, **test**, **publish**, and so on.
   `yarn add gulp`
3. Install **Webpack** to bundle/compile and link all your JS, CSS and HTML in how many files you wish.
   `yarn add webpack`
4. install **ReactJS**, **Bootstrap** and **React-Bootstrap** to implement your interface.
   `yarn add react react-bootstrap bootstrap`

or just: 

```sh
sudo pacman -S node npm git 	# Install global
npm install -g yarn 			# Install global
yarn add --dev gulp webpack react bootstrap react-bootstrap
```



## Setting git

Just need to initialize git navigating to the folder and use:

`git init`

You will need to config your user with name and email:

`git --config user.name "Daniel Ribeiro"`

`git --config user.email "dribeiro@gmail.com"`

With git you are done :)

## Setting your environment

Your enviroment isi where you work. To work you need to config some tools to be more productive.

First of all, we need to star a project

`yarn init` - Will setup a folder to download other libraries and frameworks

just awnser all questions and you are done.

Now you should create some tasks like compile your code. It's nice to use because it allow you to use the last version os JavaScript, even  if some browser don't allow it. The compiler make code be compatible with old versions. Also can make some optimizations. 

Our compiler is Babel:

`yarn add babel `

To bring all  your code togeter, use a bundler. We'll use `webpack` for that

`yarn add webapack`

Now we have to config our webpack