# Harold Cup - Orienteering Event Website (Work in Progress)

Live Demo: https://orienteering-event.firebaseapp.com/

Stack: Vue.js / Vuex/ Vuetify

This is an imaginary Orienteering Event website that I have created as a side project.
The goal is to create a website that will include all information about the event and handle new event entries.
Some additional features will be included such as chat or interactive map that will let the user add a mark on the map and inform other competitors that he has free space in his car and is willing to take other competitors to the event from his area (kind of blablacar).

# Subpages
## Finished

- Homepage (landing page with countdown)
- Invitation (basic info about the event)
- Entries - shows submitted entries - options to see by categories or clubs
- Adding new entries - dynamically updates fee of the current entry based on chosen options - with generateFakeData function in the code
- Chat - chat with other runners about the event

## To be done

- Getting here

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report



For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
