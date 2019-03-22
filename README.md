## Podcaster - Front End

This React web app was deisgned to be the responsive front-end which allows users to find, learn more and listen to their favorite podcasts.  
  + Built a front end with React that made our components tree easy to use and understand 
  + Used React Router to route users to different pages 
  + Imported React libraries to add additional functionality and a more user friendly experience

## Contents

- [Libraries](#libraries)
- [Installation](#installation)
- [Structure](#structure)
- [Components](#components)
- [User Accounts](#user-accounts)
- [Future Development](#future-development)

## Libraries & Middleware

Podcaster was built using [create-react-app](https://github.com/facebook/create-react-app) and comes with the dependencies therein. [React Materialize](https://github.com/react-materialize/react-materialize) was used to style and add the web player. [React Router](https://github.com/ReactTraining/react-router) handles component rendering and navigation based on the URL/browse history. [React Audio Player](https://github.com/justinmc/react-audio-player) allows the user to listen to events through a react interface.  

## Installation 

To get started with Podcaster, fork this repository and clone it to your hard drive. CD into the folder and run ```npm install```. Once the dependencies have been installed, you can run ```npm start``` to get your app running. For more information about how the back-end is structured, visit [this](https://github.com/d-collins2/Podcaster-Backend) repository.

## Structure

The top-level folder of Podcaster includes a `public` folder, which holds the `index.html` file where the app is officially rendered by React, an `src` folder which holds the application itself, and then a few other files: .gitignore, README, and package.json. 

The `src` folder includes: `components`, which organizes the bulk of the app's logic and content, and `index.js` handles how the app is mounted into the `index.html` file in the top-level folder. 

## Components

### AllPodcasts

This component acts as the right tool bar which has all of the podcasts in the app in alphabetical order and a search function (```SearchForm.js```). The search function causes filter the podcasts with the given parameter and returns the result. Once the search field is empty the podcasts are shown in alphabetical order. 

### AudioPlayer

This component uses the [React Audio Player](https://github.com/justinmc/react-audio-player) library to allow for the podcasts to seemlessly play in the app.

### SelectedPodcast 

## User Accounts 


## Future Developments 

