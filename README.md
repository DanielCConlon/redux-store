# redux-store

- Github URL: https://github.com/DanielCConlon/redux-store
- Heroku URL: updating heroku deployment
<!-- https://glacial-tundra-57936.herokuapp.com/ -->

# Goal

Refactor the e-commerce platform from the module project so that it uses Redux.

## Table-of-Contents

- [User Story](#user-story)
- [Description](#description)
- [Installation](#installation)
- [Requirements](#requirements)
- [Application](#application)

## [User Story](#table-of-contents)

- AS a senior engineer working on an e-commerce platform
- I WANT my platform to use Redux to manage global state instead of the Context API
- SO THAT my website's state management is taken out of the React ecosystem

## [Description](#description)

Refactor the e-commerce platform from the module project so that it uses Redux

## [Installation](#table-of-contents)

fork the repo and run npm install

## [Requirements](#table-of-contents)

- GIVEN an e-commerce platform that uses Redux to manage global state
- WHEN I review the app’s store
- THEN I find that the app uses a Redux store instead of the Context API
- WHEN I review the way the React front end accesses the store
- THEN I find that the app uses a Redux provider
- WHEN I review the way the app determines changes to its global state
- THEN I find that the app passes reducers to a Redux store instead of using the Context API
- WHEN I review the way the app extracts state data from the store
- THEN I find that the app uses Redux instead of the Context API
- WHEN I review the way the app dispatches actions
- THEN I find that the app uses Redux instead of the Context API

## [Application](#table-of-contents)

![Website image](./server/utils/application.PNG)
