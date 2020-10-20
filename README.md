<h1 align="center">
    <img alt="Happy" title="#logo" src=".github/Logo.svg" width="250px" />
</h1>

<h2 align="center">
  Happy - Next Level Week #3
</h2>

<h3 align="center">
  <img alt="GitHub Language Count" src="https://img.shields.io/github/languages/count/Dev-DC-Silva/Happy">
  
  <img alt="GitHub Repo Size" src="https://img.shields.io/github/repo-size/Dev-DC-Silva/Happy">
  
  <a href="https://github.com/Dev-DC-Silva/Happy/commits/master">
    <img alt="GitHub Last Commit" src="https://img.shields.io/github/last-commit/Dev-DC-Silva/Happy">
  </a>
  
  <img alt="GitHub Issues" src="https://img.shields.io/github/issues/Dev-DC-Silva/Happy">
  
  <a href="https://github.com/mathrb22/Happy/blob/master/LICENSE">
    <img alt="GitHub License" src="https://img.shields.io/github/license/Dev-DC-Silva/Happy">
  </a>
</h3>

<p align="center">

  <a href='#Layout'>Sobre</a> • 
  <a href='#About'>Funcionalidades</a> • 
  <a href='#Tecnologias'>Como Executar</a> • 
  <a href='#InstallationAndExecution'>Layout</a> • 
</p>

<p align="center">
  <img alt="Happy" src=".github/happy.svg" width="100%">
</p>
---

## 🎨 **Layout**

Acesse o Layout tanto da versão web quanto da mobile pelos cards abaixo

<div>
  <a href='https://www.figma.com/file/eiJJl1sn5NHgrOiBroyaS1/Happy-Web-Copy?node-id=0%3A1'>
    <img src="https://img.shields.io/static/v1?label=Happy&message=Web&color=7159c1&style=for-the-badge&logo=figma"/>
  </a>
  <br>
  <a href='https://www.figma.com/file/O62D1sRtutjBxUTx7B5xaI/Happy-Mobile-(Copy)?node-id=0%3A1'>
    <img src="https://img.shields.io/static/v1?label=Happy&message=Mobile&color=7159c1&style=for-the-badge&logo=figma"/>
  </a>
</div>

- Criado por [Tiago Lutchenberg](https://www.instagram.com/tiagoluchtenberg/)

## 📃 About

Happy is an application that was inspired by the children's day, with the aim of connecting people with the nearest orphanages, informing necessary information for visits.

## 🔨 **Tecnologias**

**Website** ([React](https://reactjs.org) + [TypeScript](https://typescriptlang.org))

- [React Router Dom](https://github.com/ReactTraining/react-router/tree/master/packages/react-router-dom)
- [Feather Icons](https://feathericons.com/)
- [Axios](https://github.com/axios/axios)
- [Mapbox](https://mapbox.io/)
- [React Leaflet](https://react-leaflet.js.org/)

**Server** ([NodeJS](https://nodejs.org) + [TypeScript](https://typescriptlang.org))

- [Express](https://expressjs.com/)
- [CORS](https://expressjs.com/en/resources/middleware/cors.html)
- [TypeORM](https://typeorm.io/#/)
- [SQLite](https://github.com/mapbox/node-sqlite3)
- [Multer](https://github.com/expressjs/multer)
- [ts-node](https://github.com/TypeStrong/ts-node)

**Mobile** ([React Native](https://reactnative.com) + [TypeScript](https://typescriptlang.org))

- [Expo](https://expo.io/)
- [Expo Google Fonts](https://github.com/expo/google-fonts)
- [React Navigation](https://reactnavigation.org/)
- [Axios](https://github.com/axios/axios)

**Utilitários**
- Protótipo no Figma
- Leaflet
- Visual Studio Code
- Insomnia
- GitKraken
- BeekepperStudio


## 🚀 **Installation and execution**

Para poder executar o projeto é preciso ter o [NodeJS](https://nodejs.org), [Git](https://git-scm.com) e um editor de código instalado em seu computador, indico o [Visual Studio Code](https://code.visualstudio.com), e como opcional o [Yarn](https://yarnpkg.org) para usar com o NodeJS

## 🎲 **Rodando o Back-end (servidor)**


```bash
# Starting from the project root folder, go to backend folder
$ cd backend

# Install the dependencies
$ yarn

# Use the script to run the migrations
$ yarn typeorm migration:run

# To finish, run the api service
$ yarn dev

# Well done, project is started!
```

## 🧭 **Rodando a aplicação web (Frontend)**

```
# Starting from the project root folder, go to web folder
$ cd web

# Install the dependencies
$ yarn

# Be sure the file 'src/services/api.ts' have the IP to your API

# Start the client
$ yarn start
```
## :iphone: **Rodando a aplicação no celular (Mobile)**

```
# Starting from the project root folder, go to mobile folder
$ cd mobile

# Be sure the file 'src/services/api.ts' have the IP to your API

# Start the expo service and scan the QR code with Expo Client
$ yarn start
```

## 💡 **How to contribute**

**Make a fork of this repository**

```bash
# Fork using GitHub official command line
# If you don't have the GitHub CLI, use the web site to do that.

$ gh repo fork Dev-DC-Silva
```

**Follow the steps below**

```bash
# Clone your fork
$ git clone your-fork-url && cd Happy

# Create a branch with your feature
$ git checkout -b my-feature

# Make the commit with your changes
$ git commit -m 'feat: My new feature'

# Send the code to your remote branch
$ git push origin my-feature
```

After your pull request is merged, you can delete your branch

## 📲 Contact


## 📝 License

This project is under **MIT** license. Check file _**LICENSE**_ for more details.

---

<h5 align="center">
  &copy;2020 - <a href="https://github.com/Dev-DC-Silva/">Diego Silva</a>
</h5>
