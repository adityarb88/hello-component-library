# Hello Component Library
A quick demo of one of the approaches to package a React component library.

# Steps
1. Add a component in the `lib` directory.
2. `npm start` to test the component locally.
3. `npm build` to build the component before publishing.
4. `npm publish` to publish the component to npm.

# Publishing Notes
1. Before publishing, you need to do the following things:
    - Create a npm account
    - Install npm
    - Run `npm login`
    
2. You should be added as one of the maintainers in the `@theoffice` org: https://www.npmjs.com/package/@theoffice/hello-component-library. (Contact https://www.npmjs.com/~adityarb88 for this)

# Consuming the Library
1. Create an app using `create-react-app`.
2. Add ` "@theoffice/hello-component-library": "0.0.4",` as one of the dependencies.
3. Run `npm install`.
4. Import `import {Hello} from '@theoffice/hello-component-library';` into your app and use the `<Hello></Hello>` component.

# References 
https://hackernoon.com/creating-a-library-of-react-components-using-create-react-app-without-ejecting-d182df690c6b
