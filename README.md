# OmniRepo by RocketSeat

Project for a [Video](https://www.youtube.com/watch?v=k5TkBcUTJus) made by [Rocketseat](https://github.com/Rocketseat) that has the purpose to build a generic monorepo using Yarn Workspaces. Here i'm exploring the benefits of a mono repo, such as shared node_modules (if the versions are compatible), multiple packages, etc.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development.

### Prerequisites

Node, Yarn, Expo and a text editor. I'm using VSCode on Ubuntu.

## Installing
cd to the cloned folder
```
$ yarn
```
To install all the dependencies.

## BackEnd
cd to the server folder.
```
$ yarn start
```
The Backend will be running in the http://localhost:3333.

## FrontEnd
Go to another terminal.
```
$ cd /web
$ yarn start
```
Go to http://localhost:4000 and the Web project is up and running!

## Mobile
I'm using Expo, so make sure that you have it. Go to another terminal.
```
$ cd /app
$ yarn start
```
Go to the expo page and connect.

## Testing
```
$ yarn test
```
This will run every test on the mono repo.

## Built With

* [Typescript](https://devdocs.io/typescript/) - Main Language
* [Node.js](https://nodejs.org/en/) - The web framework used
* [Jest](https://jestjs.io/) - Js Testing Framework
* [React](https://reactjs.org/) - Js framework for WEB
* [React Native](https://facebook.github.io/react-native/) - JS framework for APPs
* [Expo](https://expo.io/) - Used to improve the app development

## Authors

* **Renan Oliveira** - [GitHub](https://github.com/lmaoclost), [LinkedIn](https://www.linkedin.com/in/renansmoliveira/)
* **RocketSeat** - [GitHub](https://github.com/Rocketseat), [Website](https://rocketseat.com.br/)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

Made with ❤️ by Renan Oliveira.