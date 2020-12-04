# Ismin-2020-project - Mobile App
By Ines Ben Amor and Steven Betesh

[![License](https://img.shields.io/github/license/saluki/nestjs-template.svg)](https://github.com/saluki/nestjs-template/blob/master/LICENSE)


## 1. Getting started

### 1.1 Requirements

Before starting, make sure you have at least those components on your workstation:

- An up-to-date release of [NodeJS](https://nodejs.org/)
- NPM
 
### 1.2 Project configuration

Start by cloning this project on your workstation.

``` sh
https://github.com/inesbenamor/etablissement-app.git```

The next thing will be to install all the dependencies of the project.

```sh
cd ./etablissement-app
npm install
```

Once the dependencies are installed, you can now configure your project by creating a new `.env` file containing your environment variables used for development.

```
cp .env.example .env
vi .env
```

### 1.3 Launch and discover

You are now ready to launch the NestJS application using the command below.

```sh
npm run start

# Launch the development server with TSNode
npm run start:dev
```

You can now head to `http://localhost:3000/etablissements` and see your API endpoint. 
