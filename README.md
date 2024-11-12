# **REACT JS**

A **library** is a collection of prewritten code snippets that developers can use and reuse to perform various JavaScript functions. The purpose of a library is to equip developers with prewritten structures of code with specified functions to make coding faster, more efficient, and less repetitive for the developers. [React](https://react.dev/) is one such library. React is an open-source JavaScript library created by Facebook in 2011 designed to help developers build the front-end  of a website, or the user interface. React is currently the most popular JavaScript library for building user interfaces. It is important to remember that React is only a library and not a framework like [Angular](https://angular.dev/) or [Vue](https://vuejs.org/), as React is not an all-in-one development solution.

&nbsp;

## ***Key Features*** 

**1. JSX (JavaScript Syntax Extension):**
While HTML structures web pages, JavaScript brings interactivity through programming logic and functions. JSX takes the relationship between these technologies a step further by allowing JavaScript code to seamlessly integrate within HTML tags. Rather than separating JavaScript code from the HTML layout it controls, JSX lets JavaScript objects nest directly inside elements. Though browsers are unaware of JSX, the Babel transpiler translates it to standard JavaScript that browsers can interpret. 

**2. Virtual DOM:**
DOM, Document Object Model, serves as the architectural foundation for dynamic web pages. Traditionally, JavaScript frameworks directly update the actual DOM whenever any changes occurs, slowing the rendering of updates. In contrast, React employs a virtual DOM - a purely in-memory representation mirroring the real DOM. On each re-render, the virtual DOM efficiently reconciles by calculating the precise changes required and only applying the necessary updates to the real DOM. 

**3. One-way Data Binding:**
As the name implies, one-way data binding flows solely downstream or one-way. Under React, information can only transfer from parent component to child component in a unidirectional fashion. While child components return data to the parent, they can communicate to the parent to initiate state changes in response to various inputs. 

**4. Performance:**
Because React uses virtual DOM and only updates the updated portions, the DOM operates faster and more efficient. 

**5. Extension:**
With the help of React's numerous extensions, we can build whole user interface applications. Both server-side rendering and mobile app development are supported. To assist us design visually appealing user interfaces, React has been expanded with Flux, Redux, React Native, and other tools.

**6. Conditional Statements:**
It is possible to write conditional statements using JSX. The data in the browser is based on the conditions specified inside the JSX.

**7. Components:**
Because React.js is component-based, it separates the page into several parts. Every component has its own logic and design and is a part of the UI design. As a result, the JavaScript-written component logic makes things simple, quick, and reusable.

**8. Simplicity:**
React.js employs JSX, a blend of HTML and JavaScript, and is component-based, making the code reusable. This reduces the amount of code and makes it easier to comprehend and troubleshoot.

&nbsp;

## ***How to Setup React***
#### **Prerequisite requirements** 
Before installing React JS, the following software should be installed in your computer.

-	Node.js must exist on your computer. If not yet installed, visit [Node JS official website to install.](https://nodejs.org/en) 
  
    - Download Node.js on the provided link above. When finished downloading, open it then just click `next` on every step until the `install`. When the install button appears, click it and wait for, then click `finish`.

-	To use React JS, a code editor should be installed in the computer. A good code editor like [Visual Studio Code](https://code.visualstudio.com/download) is recommended for React development.

In command prompt:

    node -v
    npm -v
    code --version

`node -v` and `npm -v` will check if the installation of Node JS is successful, while  `code --version` will check the version of the VS code installed in your computer. If you see the version of the node you installed, then you are good to go. Similarly, you can check if a Node JS version already exist in your computer by writing the same code. You can also check if Node JS installation was successful by clicking `🪟` (windows logo) then type Node JS. You should see a Node JS app as you type.

&nbsp;

#### **React Installation Step-by-Step** 
## ***Step 1***
Create a new folder. For the sake of this example, name the folder as **REACTJS**. Once the folder is created, open the **Visual Studio Code** and navigate in the `menu bar`. Under file, select **`open folder`** then select the folder you just created.
## ***Step 2***
Make sure that you are in the correct folder, if not repeat step 1.  Inside Visual Studio Code, click `view` in the `menu bar`, then select **`terminal`**. 
## ***Step 3***
Inside the terminal, write this command:

    npx create-react-app react-first-project

`npx create-react-app` enables an easy setup of a new React project with all necessary folder structure, dependencies, and configuration files. In our example, `react-first-project` is the name of our project. After a couple of minutes, the process of installation will be done and you should now be able to use React in your computer. 
## ***Step 4***
Run Node JS application:

    cd react-first-project (this is the name of the file) 
    npm start

React JS should now appear in your browser. 

&nbsp;

**Congratulations!** You have now successfully set up a React project on your computer. You can now create interactive and dynamic user interfaces using React. **Happy coding!** For more information on how to setup React JS, visit [setup](https://blog.hubspot.com/website/react-js) or you can watch this [video tutorial](https://www.youtube.com/watch?v=HIdPpm-0ZNQ).


