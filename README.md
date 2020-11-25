<h1 align="center">
    <img alt="Happy" title="#logo" src=".github/Logo.svg" width="250px" />
</h1>

<h2 align="center">
  Happy - Next Level Week #3
</h2>

<p align="center">
  <a href="#-About">Sobre</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-Layout">Layout</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-Tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-Installation and execution">Installation and execution</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-How to contribute">How to contribute</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-License">License</a>
</p>


<p align="center">
  <img alt="Happy" src=".github/happy.png" width="100%">
</p>

---

## 📃 **About**

happy is an application that was inspired by children's day, with the aim of connecting people to the nearest orphanages, informing the necessary information for visits. to visit see the web version click [**here**](https://nlw-3-happy-sable.vercel.app/)

## 🎨 **Layout**

Acesse o Layout tanto da versão web quanto da mobile pelos cards abaixo

<div>
  <a href='https://www.figma.com/file/eiJJl1sn5NHgrOiBroyaS1/Happy-Web-Copy?node-id=0%3A1'>
    <img src="https://img.shields.io/static/v1?label=Happy&message=Web&color=7159c1&style=for-the-badge&logo=figma"/>
  </a>
  <a href='https://www.figma.com/file/O62D1sRtutjBxUTx7B5xaI/Happy-Mobile-(Copy)?node-id=0%3A1'>
    <img src="https://img.shields.io/static/v1?label=Happy&message=Mobile&color=7159c1&style=for-the-badge&logo=figma"/>
  </a>
</div>

- Criado por [Tiago Lutchenberg](https://www.instagram.com/tiagoluchtenberg/)

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

$ gh repo fork Diego-DevsS
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

## 📲 **Contact**


## 📝 **License**

This project is under **MIT** license. Check file _**LICENSE**_ for more details.

---

<h5 align="center">
  &copy;2020 - <a href="https://github.com/Diego-DevsS/">Diego Silva</a>
</h5>
