## Getting started
- Install redux and react-redux
- Access redux store in the application
- Containers contains state which can be managed by redux
- No need to refactor UI state managed by containers/components, only manage state which is used globally.

- Made 2 actions - add ingredient and remove ingredient
- Handling 2 state properties from burgerbuilder.js
`ingredients and totalPrice`

### Inside index.js, set up the redux environment
If you're creating a SPA, you'll probably have one main page you render. In there, wrap the main React component with <Provider> just as shown in this course.