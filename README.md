# Section 1: What is React?

Official Web Page: https://react.dev/
React is a JavaScript library for building user interfaces.
You don't have to wait for web pages to load, just like mobile apps.

-   It uses JavaScript on the browser to update the page without reloading the page.
-   JavaScript runs in the background

## Why not use only JavaScript?

-   It quickly becomes cumbersome (large or heavy and therefore difficult to carry or use).
-   It quickly becomes error-prone.
-   It quickly becomes hard to maintain or edit.
-   React offers a way simpler "mental model".

React is good for building complex user interfaces for complex applications like Netflix web app.

## React JS vs Vanilla JavaScript: Why use React?

React = Declarative UI Programming (Define the goal, not the steps).
With React, you define the target UI state(s) - not steps to get there.
Instead, React will figure out & perform the necessary steps.

Vanilla JavaScript = Imperative Programming.
Define the steps needed to get there, not the goal.
Which is cumbersome and difficult with very many steps.

## Creating React Projects Locally.

-   You will need to install Node JS. Helps to use commands with the command line.
-   Always run _npm install_ to download dependencies for a given project.
-   To start the project: _npm start_ and click on the link
-   To quit the project: _ctr c_
-   To restart the project: _npm start_ and click on the link

### Creating a Brand New react project

-   To create a brand new project: _npx create-react-app my-app_
-   Navigate to the folder where you want to create the project: _cd react-project_
-   The create the app: _npx create-react-app project-name_

### Ignoring node modules on git

-   Create a git ignore file (ignore files when you make a commit)
-   This is already included automatically when the project is created

### Using React in the Browser

-   Use link: _react.new_

# Section 2: JavaScript Refresher

## Adding JavaScript to a Page.

-   JavaScript can be executed in the browser (as part of the websites).
-   JavaScript can also be executed outside of the browser (Server-side code) - This is due to Node JS.
-   JavaScript can also be executed on Mobile Devices. (e.g via embedded websites) - E.g using technologies like React Native.

### Adding JavaScript Code to a Website.

-   Between _Script_ tags
-   Via _script_ import (with src attribute) - Recommended option (Separate JS files).
    -   You can add the script tags either in the head section or body section
    -   The defer attribute can be added, to allow the JS code to be executed only after the html code has been passed.
    -   For modern JS, instead of defer, use _type_ attribute and set it to _module_
    -   For react projects, the script tags are created through the build process.
