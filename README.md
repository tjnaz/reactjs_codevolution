Codevolution - ReactJS

1. Introduction
   Strong community backing
   Component based architecture
   Reusable code
   React is declarative
   ES6
   let & const
   arrow functions
   Template literals
   deault parameters
   object literals
   rest and spread operators
   destructuring assignment
   Plan
   Fundamentals
   HTTP
   Routing
   Redux - state management
   Utilities/Libraries

2. Hello world!
   npx create-react-app <project_name>
   npx\* vs. npm -g

3. Folder structure
   ./package.json
   ./node_modules/
   ./public/
   favicon.ico
   index.html
   `<div id=“root”></div>`
   manifest.json
   ./src/
   index.js -> starting point
   App.js
   App.css
   App.test.js -> unit tests
   index.css
   logo.svg
   serviceWorker.js -> concerned with Progressive Web App (PWAs)
   when running `<npm start>`
   index.html served in the browser
   contains the “root” id
   index.js -> ReactDOM renders the App.js component on to the root DOM node
   App.js component contains the HTML which renders in the browser

4. Components
5 main components
<HEADER />
<SIDENAV />
<MAIN CONTENT />
<FOOTER />
ROOT component which contains all the other components
Component types
stateless functional component
stateful class component

5. Functional components
   JS function
   Optionally receives a prop
   Returns HTML that describes UI
