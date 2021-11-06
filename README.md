VUE CLI OVERVIEW

public:


	index.html: link in anything you need in your html header. Then for the body calls the id #app for the vue
	images:

src:


assets:
components: (Any 'component' that you want on multiple pages')
router: (links up all the .vue files)
	index.js (This is the  file you will ever have in this folder)
		This will allow you to created 'routes' to your pages without having to reload. It will re-rending)
views:
	Home.vue, ect.
App.vue: (header and footer); global css
	It will call the router to take to the correct route
main.js: We are calling vue function, and importing router and declaring data

# creative-project

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
