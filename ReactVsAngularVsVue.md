# React vs Angular vs Vue
## React

### History of React
- React was created by Jordan Walke, a software engineer at Facebook, who released an early prototype of React called "FaxJS".
- He was influenced by XHP, an HTML component framework for PHP.
- It was first deployed on Facebook's News Feed in 2011 and later on Instagram.com in 2012.
- It was open-sourced at JSConf US in May 2013.

### What is React?
- React is a JavaScript library for building user interfaces.
- React is used to build single page applications.
- React allows us to create reusable UI components.
- React was first created by Jordan Walke, a software engineer working for Facebook.
- React was first deployed on Facebook's News Feed in 2011 and on Instagram.com in 2012.

### Why React?
- React is a declarative, efficient, and flexible JavaScript library for building user interfaces.
- It lets you compose complex UIs from small and isolated pieces of code called "components".

### React Features
- JSX − JSX is JavaScript syntax extension. It isn't necessary to use JSX in React development, but it is recommended.
- Components − React is all about components. You need to think of everything as a component. This will help you maintain the code when working on larger scale projects.
- Unidirectional data flow and Flux − React implements one-way data flow which makes it easy to reason about your app. Flux is a pattern that helps keeping your data unidirectional.

### React Advantages
- Uses virtual DOM which is a JavaScript object. This will improve apps performance, since JavaScript virtual DOM is faster than the regular DOM.
- Can be used on client and server side as well as with other frameworks.
- Component and Data patterns improve readability which helps to maintain larger apps.
- React can be used with any other framework (Backbone.js, Angular.js) as it is only a view layer.

### React Limitations
- Covers only the view layer of the app, hence you still need to choose other technologies to get a complete tooling set for development.
- Uses inline templating and JSX, which might seem awkward to some developers.
- The library of React is too large.

### Code Funcational Example
```javascript
import React from 'react';
import ReactDOM from 'react-dom';

class Hello extends React.Component {
  render() {
    return <h1>Hello World</h1>
  }
}

ReactDOM.render(<Hello />, document.getElementById('root'));
```


## Angular

### History of Angular
- AngularJS was originally developed in 2009 by Misko Hevery and Adam Abrons.
- It was initially released in 2010.
- AngularJS is now referred to as Angular 1.x.
- Angular 2.0 was released in 2016.
- Angular is a TypeScript-based open-source front-end web application platform led by the Angular Team at Google and by a community of individuals and corporations.

### What is Angular?
- Angular is a TypeScript-based open-source front-end web application platform led by the Angular Team at Google and by a community of individuals and corporations.
- Angular is a complete rewrite from the same team that built AngularJS.

### Why Angular?

### Angular Features
- Angular is a framework for building client applications in HTML and either JavaScript or a language like TypeScript that compiles to JavaScript.

### Angular Advantages
- Angular combines declarative templates, dependency injection, end to end tooling, and integrated best practices to solve development challenges.
- Angular empowers developers to build applications that live on the web, mobile, or the desktop.

### Angular Limitations
-  Steep learning curve
-  Not SEO friendly
-  Poor performance
-  Not suited for small applications

### Code Funcational Example
```javascript
import { Component } from '@angular/core';

@Component({
  selector: 'app-root',
  template: '<h1>Hello World</h1>',
  styleUrls: ['./app.component.css']
})
export class AppComponent {
  title = 'app';
}
```

## Vue

### History of Vue
- Vue.js was created by Evan You, and first released in February 2014.
- Vue.js is an open-source Model–view–viewmodel JavaScript framework for building user interfaces and single-page applications.

### What is Vue?
- Vue.js is a progressive framework for building user interfaces.
- Vue.js is designed from the ground up to be incrementally adoptable.
- Vue.js is a library for building interactive web interfaces.
- Vue.js is focused on the view layer only.

### Why Vue?

### Vue Features
- Unlike other monolithic frameworks, Vue is designed from the ground up to be incrementally adoptable.
- The core library is focused on the view layer only, and is easy to pick up and integrate with other libraries or existing projects.
- On the other hand, Vue is also perfectly capable of powering sophisticated Single-Page Applications when used in combination with modern tooling and supporting libraries.

### Vue Advantages
- Vue is a lightweight framework
- Vue is easy to understand and develop
- Vue is easy to integrate with other applications
- Vue is easy to test
- Vue is easy to maintain

### Vue Limitations
- Vue is not suited for large applications
- Vue is not SEO friendly

### Code Funcational Example
```javascript
new Vue({
  el: '#app',
  data: {
    message: 'Hello World'
  }
})
```

## Comparison

### React vs Angular vs Vue
- React is a JavaScript library, supporting both front end web and being run on the server, for building user interfaces and web applications.
- Angular is a TypeScript-based open-source front-end web application platform led by the Angular Team at Google and by a community of individuals and corporations.
- Vue.js is an open-source Model–view–viewmodel JavaScript framework for building user interfaces and single-page applications.





