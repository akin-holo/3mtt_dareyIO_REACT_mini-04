# 3MTT Academy - Darey.io - Simple React App

This is a solution to the _#4 Mini Project Assesment_.  

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  

## Overview
This project is done with __Vite__ *(npm create vite@latest)* using react template. This is because _create-react-app_ has been depreciated by REACT.

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.


### The challenge
1. Setting Up the React App:
 - Initialize a new React project using Vite or Create React App (CRA)

2. Rendering "Hello World":
 - Modify the main component (e.g., App.js or App.jsx) to display the text "Hello World" in the browser.

 - Use Use JSX syntax to structure the content properly


### The screenshot

![](./src/assets/Preview%20-%203MTT-DareyIO_SimpleHelloWorldApp.png)

### Links

- Solution URL: [github repo]


## My process
Solution to instruction 1:
```html
<samp>npm create</samp>
```

Solution to instruction 2:
```html
The page component <b>Hello World</b> is structured inside App.jsx
<code>
   function App() {
   const Head = "Simple React App";
   const para = "Create with vite";

   return (
      <>
         <h1>{Head}</h1>
         <p>{para}</p>
      </>
      )
   }
</code>
```

The App.jsx is exported to main.jsx and wrapped in the <code>createRoot()</code> which target the index.html through the (Id="root") which enable rendering the page 



### Built with

- React
- Custom CSS



