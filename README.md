## LIST FIVE SIGNIFICANT FEATURES OF REACT

- Component-based architecture: Reusable components are the foundation of React. An individual portion of the user interface is housed within a self-contained, modular piece of code known as a component. React makes it simpler to create and maintain complicated apps by decomposing the user interface into manageable, reusable components.

- Virtual DOM: React manages the UI via a virtual DOM. React stores a simplified version of the real DOM in memory, known as the virtual DOM. React updates the virtual DOM when the state of the application changes, and then efficiently updates the actual DOM by comparing the new virtual DOM with the old one. With this method, React may change the UI rapidly and effectively, perhaps improving performance.

- JSX syntax: The syntax used by React to define components is known as JSX. Writing HTML-like code inside JavaScript is possible with JSX. This syntax enables developers to work with HTML and JavaScript in the same file and makes it simple to design complicated UI components.

- Unidirectional data flow: Data passes through React's application in a single path thanks to the model's unidirectional data flow. Child components can update their parent's state by triggering events, and data flows from parent components to child components. With this method, it is simpler to reason about the application's state and it may be possible to avoid issues brought on by unforeseen state changes.

- React Native: React can also be used to build native mobile apps using React Native. React Native allows developers to write mobile apps using the same component-based architecture and JSX syntax used in React web apps. This approach makes it easier to build cross-platform mobile apps and can reduce development time and cost.

## LIST FIVE MAJOR ADVANTAGES OF REACT

- SEO friendly: React provides a simple and straightforward way to handle server-side rendering, which makes it easier for search engines to crawl and index content. This can improve the search engine optimization (SEO) of your application.

- Strong developer tools: React comes with a set of powerful developer tools that can help you debug and optimize your code. The React Developer Tools extension for Chrome and Firefox is particularly useful for inspecting the component hierarchy, inspecting props and state, and profiling performance.

- Supports reusable code components: React is built on the idea of reusable components, which makes it easy to reuse code across different parts of an application. This can help to reduce code duplication and improve code quality.

- React is declarative: In React, you describe the desired state of the UI, and the framework takes care of the rest. This declarative approach can make it easier to reason about the state of an application and can help to reduce bugs caused by unexpected changes to the state.

- React's JSX syntax is intuitive: React's JSX syntax is intuitive and easy to read, making it easier for developers to understand the code and collaborate with each other. The syntax is also similar to HTML, which can make it easier for designers to work with developers.

## WHAT IS THE NAME OF THE SOFTWARE ENGINEER THAT CREATED REACT? ALSO, WHICH COMPANY OWNS REACT?

- The name of the software engineer who created React is Jordan Walke, React was first developed by Jordan Walke, a software engineer at Facebook, in 2011 and React is an open-source project, meaning it is available for anyone to use and contribute to. Facebook continues to maintain and support the project, but ownership of the technology is not tied to any one company.

## WHAT ARE THE NOTABLE DIFFERENCES BETWEEN HTML & JSX? GIVE AT LEAST 3 OF THEM

- Self-closing tags: In HTML, some elements are self-closing, meaning they don't need a closing tag. For example, the <img> tag doesn't need a closing tag. In JSX, all elements must have a closing tag. However, you can use a self-closing syntax in JSX by adding a forward slash at the end of the opening tag, like this: <img src="example.jpg" />.

- Conditional rendering: In HTML, there is no built-in way to conditionally render elements based on the state of the application. In JSX, you can use JavaScript expressions to conditionally render elements. For example, you might use a ternary operator to render one element if a condition is true, and a different element if the condition is false.

- Syntax: HTML and JSX have different syntaxes. In HTML, you use angle brackets to define elements, and you use attributes to add additional properties to those elements. In JSX, you use angle brackets to define elements, but you use curly braces to embed JavaScript expressions within those elements.

## WHY CAN'T BROWSERS READ JSX?

- JSX is a syntactic extension of JavaScript that allows you to write HTML-like code in your JavaScript code. When you write JSX, you are essentially writing a template that will be used to create actual HTML elements when the code is executed in the browser. In other words browsers cannot read JSX directly because it is not a valid JavaScript syntax that can be interpreted by the browser. JSX needs to be transformed into regular JavaScript code that the browser can read and execute and to convert JSX into regular JavaScript code, you need to use a tool like Babel. Babel can parse the JSX code and transform it into plain JavaScript code that the browser can read and execute.

<!--
# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify) -->
