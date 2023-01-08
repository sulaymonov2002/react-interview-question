# React Interview Questions & Answers

> Agar sizga loyiha yoqsa :star: bosing. Pull so'rovi yuqori baholanadi. Texnik yangilanishlar uchun meni [sulaymonov2002](https://github.com/sulaymonov2002/react-interview-question) kuzatib boring.

---

**Eslatma:** Ushbu repository ReactJS uchun xosdir. Iltimos, asosiy javascript savollari uchun [JavaScript Interview questions](https://github.com/sulaymonov2002/javascript-interview-questions) tekshiring.

## Downloading PDF/Epub formats

Ushbu repository PDF VA Epub versiyasini ammallar yorlig'idagi so'nggi ishga tushirishdan yuklab olishingiz mumkin.

### Table of Contents

| No. | Questions                                                                                                                                                                                  |
| --- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
|     | **Core React**                                                                                                                                                                             |
| 1   | [React nima ?](#what-is-react)                                                                                                                                                             |
| 2   | [Reactning asosiy xususiyatlari qanday ?](#what-are-the-major-features-of-react)                                                                                                           |
| 3   | [JSX nima ?](#what-is-jsx)                                                                                                                                                                 |
| 4   | [Element va Component o'rtasidagi farq nima ?](#what-is-the-difference-between-element-and-component)                                                                                      |
| 5   | [React-da componentlarni qanday yaratish mumkin ?](#how-to-create-components-in-react)                                                                                                     |
| 6   | [Class componentidan Function componentidan qachon foydalanish kerak?](#when-to-use-a-class-component-over-a-function-component)                                                           |
| 7   | [Pure Components nima?](#what-are-pure-components)                                                                                                                                         |
| 8   | [React-dagi state nima ?](#what-is-state-in-react)                                                                                                                                         |
| 9   | [React-dagi props nima ?](#what-are-props-in-react)                                                                                                                                        |
| 10  | [State va props o'rtasidagi farq nima?](#what-is-the-difference-between-state-and-props)                                                                                                   |
| 11  | [Nega biz state(ni) to'g'ridan-to'g'ri yangilamasligimiz kerak ?](#why-should-we-not-update-the-state-directly)                                                                            |
| 12  | [setState() argumenti sifatida callback qilish funksiyasining maqsadi nima ?](#what-is-the-purpose-of-callback-function-as-an-argument-of-setstate)                                        |
| 13  | [HTML va React hodisalarini boshqarish o'rtasidagi farq nima ?](#what-is-the-difference-between-html-and-react-event-handling)                                                             |
| 14  | [JSX callback(larida) usullar yoki hodisalarni qayta ishlash vositalarini qanday ulash mumkin ?](#how-to-bind-methods-or-event-handlers-in-jsx-callbacks)                                  |
| 15  | [Parametrni event handler yoki callback(ga) qanday o'tkazish mumkin ?](#how-to-pass-a-parameter-to-an-event-handler-or-callback)                                                           |
| 16  | [What are synthetic events in React?](#what-are-synthetic-events-in-react)                                                                                                                 |
| 17  | [What are inline conditional expressions?](#what-are-inline-conditional-expressions)                                                                                                       |
| 18  | [What is "key" prop and what is the benefit of using it in arrays of elements?](#what-is-key-prop-and-what-is-the-benefit-of-using-it-in-arrays-of-elements)                               |
| 19  | [What is the use of refs?](#what-is-the-use-of-refs)                                                                                                                                       |
| 20  | [How to create refs?](#how-to-create-refs)                                                                                                                                                 |
| 21  | [What are forward refs?](#what-are-forward-refs)                                                                                                                                           |
| 22  | [Which is preferred option with in callback refs and findDOMNode()?](#which-is-preferred-option-with-in-callback-refs-and-finddomnode)                                                     |
| 23  | [Why are String Refs legacy?](#why-are-string-refs-legacy)                                                                                                                                 |
| 24  | [What is Virtual DOM?](#what-is-virtual-dom)                                                                                                                                               |
| 25  | [How Virtual DOM works?](#how-virtual-dom-works)                                                                                                                                           |
| 26  | [What is the difference between Shadow DOM and Virtual DOM?](#what-is-the-difference-between-shadow-dom-and-virtual-dom)                                                                   |
| 27  | [What is React Fiber?](#what-is-react-fiber)                                                                                                                                               |
| 28  | [What is the main goal of React Fiber?](#what-is-the-main-goal-of-react-fiber)                                                                                                             |
| 29  | [What are controlled components?](#what-are-controlled-components)                                                                                                                         |
| 30  | [What are uncontrolled components?](#what-are-uncontrolled-components)                                                                                                                     |
| 31  | [What is the difference between createElement and cloneElement?](#what-is-the-difference-between-createelement-and-cloneelement)                                                           |
| 32  | [What is Lifting State Up in React?](#what-is-lifting-state-up-in-react)                                                                                                                   |
| 33  | [What are the different phases of component lifecycle?](#what-are-the-different-phases-of-component-lifecycle)                                                                             |
| 34  | [What are the lifecycle methods of React?](#what-are-the-lifecycle-methods-of-react)                                                                                                       |
| 35  | [What are Higher-Order components?](#what-are-higher-order-components)                                                                                                                     |
| 36  | [How to create props proxy for HOC component?](#how-to-create-props-proxy-for-hoc-component)                                                                                               |
| 37  | [What is context?](#what-is-context)                                                                                                                                                       |
| 38  | [What is children prop?](#what-is-children-prop)                                                                                                                                           |
| 39  | [How to write comments in React?](#how-to-write-comments-in-react)                                                                                                                         |
| 40  | [What is the purpose of using super constructor with props argument?](#what-is-the-purpose-of-using-super-constructor-with-props-argument)                                                 |
| 41  | [What is reconciliation?](#what-is-reconciliation)                                                                                                                                         |
| 42  | [How to set state with a dynamic key name?](#how-to-set-state-with-a-dynamic-key-name)                                                                                                     |
| 43  | [What would be the common mistake of function being called every time the component renders?](#what-would-be-the-common-mistake-of-function-being-called-every-time-the-component-renders) |
| 44  | [Is lazy function supports named exports?](#is-lazy-function-supports-named-exports)                                                                                                       |
| 45  | [Why React uses className over class attribute?](#why-react-uses-classname-over-class-attribute)                                                                                           |
| 46  | [What are fragments?](#what-are-fragments)                                                                                                                                                 |
| 47  | [Why fragments are better than container divs?](#why-fragments-are-better-than-container-divs)                                                                                             |
| 48  | [What are portals in React?](#what-are-portals-in-react)                                                                                                                                   |
| 49  | [What are stateless components?](#what-are-stateless-components)                                                                                                                           |
| 50  | [What are stateful components?](#what-are-stateful-components)                                                                                                                             |
| 51  | [How to apply validation on props in React?](#how-to-apply-validation-on-props-in-react)                                                                                                   |
| 52  | [What are the advantages of React?](#what-are-the-advantages-of-react)                                                                                                                     |
| 53  | [What are the limitations of React?](#what-are-the-limitations-of-react)                                                                                                                   |
| 54  | [What are error boundaries in React v16](#what-are-error-boundaries-in-react-v16)                                                                                                          |
| 55  | [How are error boundaries handled in React v15?](#how-are-error-boundaries-handled-in-react-v15)                                                                                           |
| 56  | [What are the recommended ways for static type checking?](#what-are-the-recommended-ways-for-static-type-checking)                                                                         |
| 57  | [What is the use of react-dom package?](#what-is-the-use-of-react-dom-package)                                                                                                             |
| 58  | [What is the purpose of render method of react-dom?](#what-is-the-purpose-of-render-method-of-react-dom)                                                                                   |
| 59  | [What is ReactDOMServer?](#what-is-reactdomserver)                                                                                                                                         |
| 60  | [How to use InnerHtml in React?](#how-to-use-innerhtml-in-react)                                                                                                                           |
| 61  | [How to use styles in React?](#how-to-use-styles-in-react)                                                                                                                                 |
| 62  | [How events are different in React?](#how-events-are-different-in-react)                                                                                                                   |
| 63  | [What will happen if you use setState in constructor?](#what-will-happen-if-you-use-setstate-in-constructor)                                                                               |
| 64  | [What is the impact of indexes as keys?](#what-is-the-impact-of-indexes-as-keys)                                                                                                           |
| 65  | [Is it good to use setState() in componentWillMount() method?](#is-it-good-to-use-setstate-in-componentwillmount-method)                                                                   |
| 66  | [What will happen if you use props in initial state?](#what-will-happen-if-you-use-props-in-initial-state)                                                                                 |
| 67  | [How do you conditionally render components?](#how-do-you-conditionally-render-components)                                                                                                 |
| 68  | [Why we need to be careful when spreading props on DOM elements??](#why-we-need-to-be-careful-when-spreading-props-on-dom-elements)                                                        |
| 69  | [How you use decorators in React?](#how-you-use-decorators-in-react)                                                                                                                       |
| 70  | [How do you memoize a component?](#how-do-you-memoize-a-component)                                                                                                                         |
| 71  | [How you implement Server-Side Rendering or SSR?](#how-you-implement-server-side-rendering-or-ssr)                                                                                         |
| 72  | [How to enable production mode in React?](#how-to-enable-production-mode-in-react)                                                                                                         |
| 73  | [What is CRA and its benefits?](#what-is-cra-and-its-benefits)                                                                                                                             |
| 74  | [What is the lifecycle methods order in mounting?](#what-is-the-lifecycle-methods-order-in-mounting)                                                                                       |
| 75  | [What are the lifecycle methods going to be deprecated in React v16?](#what-are-the-lifecycle-methods-going-to-be-deprecated-in-react-v16)                                                 |
| 76  | [What is the purpose of getDerivedStateFromProps() lifecycle method?](#what-is-the-purpose-of-getderivedstatefromprops-lifecycle-method)                                                   |
| 77  | [What is the purpose of getSnapshotBeforeUpdate() lifecycle method?](#what-is-the-purpose-of-getsnapshotbeforeupdate-lifecycle-method)                                                     |
| 78  | [Do Hooks replace render props and higher order components?](#do-hooks-replace-render-props-and-higher-order-components)                                                                   |
| 79  | [What is the recommended way for naming components?](#what-is-the-recommended-way-for-naming-components)                                                                                   |
| 80  | [What is the recommended ordering of methods in component class?](#what-is-the-recommended-ordering-of-methods-in-component-class)                                                         |
| 81  | [What is a switching component?](#what-is-a-switching-component)                                                                                                                           |
| 82  | [Why we need to pass a function to setState()?](#why-we-need-to-pass-a-function-to-setstate)                                                                                               |
| 83  | [What is strict mode in React?](#what-is-strict-mode-in-react)                                                                                                                             |
| 84  | [What are React Mixins?](#what-are-react-mixins)                                                                                                                                           |
| 85  | [Why is isMounted() an anti-pattern and what is the proper solution?](#why-is-ismounted-an-anti-pattern-and-what-is-the-proper-solution)                                                   |
| 86  | [What are the Pointer Events supported in React?](#what-are-the-pointer-events-supported-in-react)                                                                                         |
| 87  | [Why should component names start with capital letter?](#why-should-component-names-start-with-capital-letter)                                                                             |
| 88  | [Are custom DOM attributes supported in React v16?](#are-custom-dom-attributes-supported-in-react-v16)                                                                                     |
| 89  | [What is the difference between constructor and getInitialState?](#what-is-the-difference-between-constructor-and-getinitialstate)                                                         |
| 90  | [Can you force a component to re-render without calling setState?](#can-you-force-a-component-to-re-render-without-calling-setstate)                                                       |
| 91  | [What is the difference between super() and super(props) in React using ES6 classes?](#what-is-the-difference-between-super-and-superprops-in-react-using-es6-classes)                     |
| 92  | [How to loop inside JSX?](#how-to-loop-inside-jsx)                                                                                                                                         |
| 93  | [How do you access props in attribute quotes?](#how-do-you-access-props-in-attribute-quotes)                                                                                               |
| 94  | [What is React PropType array with shape?](#what-is-react-proptype-array-with-shape)                                                                                                       |
| 95  | [How to conditionally apply class attributes?](#how-to-conditionally-apply-class-attributes)                                                                                               |
| 96  | [What is the difference between React and ReactDOM?](#what-is-the-difference-between-react-and-reactdom)                                                                                   |
| 97  | [Why ReactDOM is separated from React?](#why-reactdom-is-separated-from-react)                                                                                                             |
| 98  | [How to use React label element?](#how-to-use-react-label-element)                                                                                                                         |
| 99  | [How to combine multiple inline style objects?](#how-to-combine-multiple-inline-style-objects)                                                                                             |
| 100 | [How to re-render the view when the browser is resized?](#how-to-re-render-the-view-when-the-browser-is-resized)                                                                           |

## Core React

1. ### What is React?

   React is an **open-source front-end JavaScript library** that is used for building user interfaces, especially for single-page applications. It is used for handling view layer for web and mobile apps. React was created by [Jordan Walke](https://github.com/jordwalke), a software engineer working for Facebook. React was first deployed on Facebook's News Feed in 2011 and on Instagram in 2012.

   **[⬆ Back to Top](#table-of-contents)**

2. ### What are the major features of React?

   The major features of React are:

   - It uses **VirtualDOM** instead of RealDOM considering that RealDOM manipulations are expensive.
   - Supports **server-side rendering**.
   - Follows **Unidirectional** data flow or data binding.
   - Uses **reusable/composable** UI components to develop the view.

   **[⬆ Back to Top](#table-of-contents)**

3. ### What is JSX?

   _JSX_ is a XML-like syntax extension to ECMAScript (the acronym stands for _JavaScript XML_). Basically it just provides syntactic sugar for the `React.createElement()` function, giving us expressiveness of JavaScript along with HTML like template syntax.

   In the example below text inside `<h1>` tag is returned as JavaScript function to the render function.

   ```jsx harmony
   class App extends React.Component {
     render() {
       return (
         <div>
           <h1>{"Welcome to React world!"}</h1>
         </div>
       );
     }
   }
   ```

   **[⬆ Back to Top](#table-of-contents)**

4. ### What is the difference between Element and Component?

   An _Element_ is a plain object describing what you want to appear on the screen in terms of the DOM nodes or other components. _Elements_ can contain other _Elements_ in their props. Creating a React element is cheap. Once an element is created, it is never mutated.

   The object representation of React Element would be as follows:

   ```javascript
   const element = React.createElement("div", { id: "login-btn" }, "Login");
   ```

   The above `React.createElement()` function returns an object:

   ```
   {
     type: 'div',
     props: {
       children: 'Login',
       id: 'login-btn'
     }
   }
   ```

   And finally it renders to the DOM using `ReactDOM.render()`:

   ```html
   <div id="login-btn">Login</div>
   ```

   Whereas a **component** can be declared in several different ways. It can be a class with a `render()` method or it can be defined as a function. In either case, it takes props as an input, and returns a JSX tree as the output:

   ```javascript
   const Button = ({ onLogin }) => (
     <div id={"login-btn"} onClick={onLogin}>
       Login
     </div>
   );
   ```

   Then JSX gets transpiled to a `React.createElement()` function tree:

   ```javascript
   const Button = ({ onLogin }) =>
     React.createElement("div", { id: "login-btn", onClick: onLogin }, "Login");
   ```

   **[⬆ Back to Top](#table-of-contents)**

5. ### How to create components in React?

   There are two possible ways to create a component.

   1. **Function Components:** This is the simplest way to create a component. Those are pure JavaScript functions that accept props object as the first parameter and return React elements:

      ```jsx harmony
      function Greeting({ message }) {
        return <h1>{`Hello, ${message}`}</h1>;
      }
      ```

   2. **Class Components:** You can also use ES6 class to define a component. The above function component can be written as:

      ```jsx harmony
      class Greeting extends React.Component {
        render() {
          return <h1>{`Hello, ${this.props.message}`}</h1>;
        }
      }
      ```

   **[⬆ Back to Top](#table-of-contents)**

6. ### When to use a Class Component over a Function Component?

   If the component needs _state or lifecycle methods_ then use class component otherwise use function component.
   _However, from React 16.8 with the addition of Hooks, you could use state , lifecycle methods and other features that were only available in class component right in your function component._
   _So, it is always recommended to use Function components, unless you need a React functionality whose Function component equivalent is not present yet, like Error Boundaries _

   **[⬆ Back to Top](#table-of-contents)**

7. ### What are Pure Components?

   _`React.PureComponent`_ is exactly the same as _`React.Component`_ except that it handles the `shouldComponentUpdate()` method for you. When props or state changes, _PureComponent_ will do a shallow comparison on both props and state. _Component_ on the other hand won't compare current props and state to next out of the box. Thus, the component will re-render by default whenever `shouldComponentUpdate` is called.

   **[⬆ Back to Top](#table-of-contents)**

8. ### What is state in React?

   _State_ of a component is an object that holds some information that may change over the lifetime of the component. We should always try to make our state as simple as possible and minimize the number of stateful components.

   Let's create a user component with message state,

   ```jsx harmony
   class User extends React.Component {
     constructor(props) {
       super(props);

       this.state = {
         message: "Welcome to React world",
       };
     }

     render() {
       return (
         <div>
           <h1>{this.state.message}</h1>
         </div>
       );
     }
   }
   ```

   ![state](images/state.jpg)

   State is similar to props, but it is private and fully controlled by the component ,i.e., it is not accessible to any other component till the owner component decides to pass it.

   **[⬆ Back to Top](#table-of-contents)**

9. ### What are props in React?

   _Props_ are inputs to components. They are single values or objects containing a set of values that are passed to components on creation using a naming convention similar to HTML-tag attributes. They are data passed down from a parent component to a child component.

   The primary purpose of props in React is to provide following component functionality:

   1. Pass custom data to your component.
   2. Trigger state changes.
   3. Use via `this.props.reactProp` inside component's `render()` method.

   For example, let us create an element with `reactProp` property:

   ```jsx harmony
   <Element reactProp={"1"} />
   ```

   This `reactProp` (or whatever you came up with) name then becomes a property attached to React's native props object which originally already exists on all components created using React library.

   ```
   props.reactProp
   ```

   **Example: Props in Class Based Component**

   ```jsx
   import React from "react";
   import ReactDOM from "react-dom";

   class ChildComponent extends React.Component {
     render() {
       return (
         <div>
           <p>{this.props.name}</p>
           <p>{this.props.age}</p>
         </div>
       );
     }
   }

   class ParentComponent extends React.Component {
     render() {
       return (
         <div>
           <ChildComponent name="John" age="30" />
           <ChildComponent name="Mary" age="25" />
         </div>
       );
     }
   }
   ```

   **Example: Props in Functional Component**

   ```jsx
   import React from "react";
   import ReactDOM from "react-dom";

   const ChildComponent = (props) => {
     return (
       <div>
         <p>{props.name}</p>
         <p>{props.age}</p>
       </div>
     );
   };

   const ParentComponent = () => {
     return (
       <div>
         <ChildComponent name="John" age="30" />
         <ChildComponent name="Mary" age="25" />
       </div>
     );
   };
   ```

   **[⬆ Back to Top](#table-of-contents)**

10. ### What is the difference between state and props?

    Both _props_ and _state_ are plain JavaScript objects. While both of them hold information that influences the output of render, they are different in their functionality with respect to component. Props get passed to the component similar to function parameters whereas state is managed within the component similar to variables declared within a function.

    **[⬆ Back to Top](#table-of-contents)**

11. ### Why should we not update the state directly?

    If you try to update the state directly then it won't re-render the component.

    ```javascript
    //Wrong
    this.state.message = "Hello world";
    ```

    Instead use `setState()` method. It schedules an update to a component's state object. When state changes, the component responds by re-rendering.

    ```javascript
    //Correct
    this.setState({ message: "Hello World" });
    ```

    **Note:** You can directly assign to the state object either in _constructor_ or using latest javascript's class field declaration syntax.

    **[⬆ Back to Top](#table-of-contents)**

12. ### What is the purpose of callback function as an argument of `setState()`?

    The callback function is invoked when setState finished and the component gets rendered. Since `setState()` is **asynchronous** the callback function is used for any post action.

    **Note:** It is recommended to use lifecycle method rather than this callback function.

    ```javascript
    setState({ name: "John" }, () =>
      console.log("The name has updated and component re-rendered")
    );
    ```

    **[⬆ Back to Top](#table-of-contents)**

13. ### What is the difference between HTML and React event handling?

    Below are some of the main differences between HTML and React event handling,

    1. In HTML, the event name usually represents in _lowercase_ as a convention:

       ```html
       <button onclick="activateLasers()"></button>
       ```

       Whereas in React it follows _camelCase_ convention:

       ```jsx harmony
       <button onClick={activateLasers}>
       ```

    2. In HTML, you can return `false` to prevent default behavior:

       ```html
       <a
         href="#"
         onclick='console.log("The link was clicked."); return false;'
       />
       ```

       Whereas in React you must call `preventDefault()` explicitly:

       ```javascript
       function handleClick(event) {
         event.preventDefault();
         console.log("The link was clicked.");
       }
       ```

    3. In HTML, you need to invoke the function by appending `()`
       Whereas in react you should not append `()` with the function name. (refer "activateLasers" function in the first point for example)

    **[⬆ Back to Top](#table-of-contents)**

14. ### How to bind methods or event handlers in JSX callbacks?

    There are 3 possible ways to achieve this:

    1. **Binding in Constructor:** In JavaScript classes, the methods are not bound by default. The same thing applies for React event handlers defined as class methods. Normally we bind them in constructor.

       ```javascript
       class Foo extends Component {
         constructor(props) {
           super(props);
           this.handleClick = this.handleClick.bind(this);
         }
         handleClick() {
           console.log("Click happened");
         }
         render() {
           return <button onClick={this.handleClick}>Click Me</button>;
         }
       }
       ```

    2. **Public class fields syntax:** If you don't like to use bind approach then _public class fields syntax_ can be used to correctly bind callbacks.

       ```jsx harmony
       handleClick = () => {
         console.log("this is:", this);
       };
       ```

       ```jsx harmony
       <button onClick={this.handleClick}>{"Click me"}</button>
       ```

    3. **Arrow functions in callbacks:** You can use _arrow functions_ directly in the callbacks.

       ```jsx harmony
       handleClick() {
           console.log('Click happened');
       }
       render() {
           return <button onClick={() => this.handleClick()}>Click Me</button>;
       }
       ```

    **Note:** If the callback is passed as prop to child components, those components might do an extra re-rendering. In those cases, it is preferred to go with `.bind()` or _public class fields syntax_ approach considering performance.

    **[⬆ Back to Top](#table-of-contents)**

15. ### How to pass a parameter to an event handler or callback?

    You can use an _arrow function_ to wrap around an _event handler_ and pass parameters:

    ```jsx harmony
    <button onClick={() => this.handleClick(id)} />
    ```

    This is an equivalent to calling `.bind`:

    ```jsx harmony
    <button onClick={this.handleClick.bind(this, id)} />
    ```

    Apart from these two approaches, you can also pass arguments to a function which is defined as arrow function

    ```jsx harmony
    <button onClick={this.handleClick(id)} />;
    handleClick = (id) => () => {
      console.log("Hello, your ticket number is", id);
    };
    ```

    **[⬆ Back to Top](#table-of-contents)**

16. ### What are synthetic events in React?

    `SyntheticEvent` is a cross-browser wrapper around the browser's native event. Its API is same as the browser's native event, including `stopPropagation()` and `preventDefault()`, except the events work identically across all browsers.

    **[⬆ Back to Top](#table-of-contents)**
