<p align="center">
  <img width="350" src="src/assets/prevue-large-green-bottom.png">
  <h1 align="center">PreVue </h1>
</p>

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/teamprevue/PreVue/pulls)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

<h3 align="center">
All in One Prototyping Tool 
For Vue Developers

</h3>

<h4 align="center">
From Component Architecture to Code Exporting
</h4>

<h4 align='center'>
  https://www.prevue.live
</h4>

PreVue allows users to conceptualize and visualize component architecture by allowing them to :

  1. Create components and preview their associated code
  2. Set up different routes and views
  3. Establish parent-child component relationships
  4. View application hierarchy in tree format
  5. Export the component architecture as a Vue application created with default Vite settings.

Use PreVue to create projects in single sessions or sign in with GitHub to save projects and update them anytime.
the component architecture as a Vue application created with the default Vue CLI settings.

<p align="center">
  <img width="1000" src="src/assets/pvv.png?raw=true">

</p>

## Getting Started


## How to use

---

#### Adding Components

- Double click on the application icon
- Create components by entering a name and clicking the HTML elements you need
- Clicked elements will be shown in the right sidebar
- Drag the elements to change their order
- Once you're satisfied, click the button to ‘add a component’ and it will show up in the working area. Resize and move components to fit the design you have in mind.


<img width="1000" src="src/assets/PreVueDemo.gif">

#### Editing Components

- Double click elements to bring up the modal view
- Add additional elements to a component with a live preview of the component code
- Drag elements on the right side bar to nest elements
- Establish parent-child component relationships via the dropdown menu when creating or editing components


<img width="1000" src="src/assets/componentdisplay.png?raw=true">

#### Adding Routes

- Create different routes that represent different Views for your app.
- Any components created on a given route will be automatically saved to that route
- See your application’s hierarchy by clicking the ‘Tree’ icon in the navigation bar

<p align="center">
<img width ="300" src="src/assets/routecreator.png?raw=true">
</p>

#### Tree View of Application Architecture

<p align="center">
  <img width="300" src="src/assets/treeview.png?raw=true">

</p>

#### Saving/Opening/Exporting Projects

- In order to utilize the saving and opening functionality of PreVue, please clone the repo to run on your local machine.
- If you're signed in with GitHub, click the ‘Save Project’ icon to save it to PreVue’s database
- Click ‘Open Project’ to retrieve past projects
- Once you're satisfied, click the export project icon to export your awesome project as new Vue application!
- Other users can use PreVue's playground to create and export projects in single sessions.


<img src='src/assets/PreVueExportDemo.gif'/>

##### Code Exporting

Below is the generated directory structure of the Vue application that is created when you export your design.

```
src/
  assets/
  App.vue
  components/
    UserCreatedComponent1.vue
    UserCreatedComponent2.vue
    ...
  views/
    HomeView.vue
    UserCreatedRouteComponent1.vue
    UserCreatedRouteComponent2.vue
    ...
```

## Running your own local version


### Setup

Coming soon!

## Built With

---

- [Vue.js](https://vuejs.org/)
- [Vue Router](https://router.vuejs.org/guide/#html)
- [Vuex](https://vuex.vuejs.org/)
- [Vite](https://vitejs.dev/)
- [Node.js](https://nodejs.org/en)
- [Express](https://expressjs.com/)
- [Vuetify](https://vuetifyjs.com/)
- [Jest](https://jestjs.io/)
- [Vue Test Utils](https://test-utils.vuejs.org/)
- [SuperTest](https://www.npmjs.com/package/supertest)

## Changelog

---

PreVue 2.0 Adds:
- Implementation of PreVue as a web application
- OAuth via GitHub
- TypeScript integration
- Backend infrastructure built with Node/Express
- General UI/UX enhancements
- Testing with Vitest and Supertest (and Jest)


## Contributing

---

We encourage you to submit issues for any bugs or ideas for enhancements. Please feel free to fork this repo and submit pull requests to contribute as well. Also follow PreVue on [LinkedIn](https://www.linkedin.com/company/prevue-live/) for more updates. Some ideas for future contributions include:

- Project livesharing (via Websockets)
- Migrate state management from Vuex to Pinia
- More thorough testing with Jest

## Authors

---

PreVue 2.0
- **Jason Boo** [@jasonboo123](https://github.com/jasonboo123)
- **Robert Drake** [@rmdrake8](https://github.com/rmdrake8)
- **Sean Flynn** [@seanflynn5](http://github.com/seanflynn5)
- **Zach Pestaina** [@zachpestaina](https://github.com/zachpestaina)

PreVue 1.0
- **Hubert Lin** [@hubelin](https://github.com/hubelin)
- **Franklin Pinnock** [@pinnockf](https://github.com/pinnockf)
- **Annette Lin** [@al2613](https://github.com/al2613)
- **Daniel Shu** [@danshuu](https://github.com/danshuu)

## License

---

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
