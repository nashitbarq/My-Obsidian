

## Week 1

---
### COURSE INTRODUCTION
---

#### Introduction to the course

**Module 1**

- map() methods
- Keys
- Controlled Components
- Props and State
- Context application programming interface (Context API)

By the end of this module you will be able to:

- Outline React and various career opportunities.
- Render and transform lists with keys in React.
- Distinguish between controlled and uncontrolled React components.
- Create a controlled form component in React.
- Share component state by lifting state up to the closest common ancestor.
- Share global state using React Context.

**Module 2**

- In-depth understanding of Hooks: Use, Rules and Building
- useState hook
- useEffect hook
- useReducer hook

By the end of this module you will be able to:

- Explain the uses and purpose of React hooks.
- Detail the concept and nature of state and state change.
- Use the State hook to declare, read and update the state of a component.
- Use the Effect hook to perform side-effects within a React component.
- Use hooks to fetch data in React.
- Create appropriate custom hooks in React.

**Module 3**

- Adv JSX concepts, such as components and elements.
- Children types
- Component composition
- Children prop
- How to manipulate children in JSX
- Spread operator in react
- Creating Higher-order components
- Render props
- Croscutting concerns
- Testing
- Debugging
- Writing integration tests

By the end of this module, you will be able to:

- Define the types of children within JSX.
- Describe the process and purpose of creating render props.
- Describe the process and purpose of creating higher-order components.
- Use Jest and the React Testing Library to write and perform tests on your applications.

**Module 4**

- Lab Project: Code portfolio app

By the end of this module, you will be able to:

- Synthesize the skills from this course to create a portfolio.
- Reflect on this course's content and on the learning path that lies ahead.

## **React and your career opportunities**

- FB and Insta are powered by React
- Different JS flavors can be used with react, at Meta they use a flow flavor of JS, that allows them to ensure type safety through the use of developing React comps.
    - Other ways React compos can be built:
        - using TypeScript

## **Grid layouts**

- Bootstrap grids
- You need to do a lot of calculation with JS for doing what you can do with just one line of code using CSS grids.
- Develop a good understanding of how to use grids in your app.

---

### Rendering Lists in React

---

#### Transforming Lists in JavaScript

Chances are you'll need to transform various elements before displaying the final list to your users. Here, we will use the map() method in JavaScript to transform lists of data.

- **List:** a list is a simple collection of elements which, translated to JavaScript terms, represents an array. These arrays can contain any type of data. But the most common type you'll encounter per element is an object.
    - Lists are core building blocks of app development.
- **Map() method:** Say, Little Lemon uses an external service to query a list of its most requested desserts by users. However, when fetching data from a third party like this, you are generally provided with more data than you need. The data will be provided in a format or shape that is determined by the third party. This means that you may need to write more code to handle the data in order to retrieve just the information you need. That's where the map method comes in as a way to ignore everything that you do not want displayed on screen and extract only the data that your users care about.

#### Render a simple list component

- In react, it is possible to transform any list of items into a collection of React components.
- **Displaying a simple version of a collection using Map() function:**
    1. Create a new variable called "listItems" to store the result of the transformation.
    2. Loop through the array of desserts using the JavaScript map function.
    3. Inside the map function, return a React component or JSX element to represent each item in the array.
    4. Use the **`<li>`** (list item) tag as the component to represent each item.
    5. Create a new variable called "itemText" to store the text content of each list item.
    6. Set the value of "itemText" to be the concatenation of the dessert's title and price, separated by a dash.
    7. Wrap the "itemText" variable with curly braces **`{}`** to include it as part of the JSX transformation.
    8. In the render method, embed the "listItems" variable inside an HTML list wrapper component (e.g., **`<ul>`** for an unordered list).
    9. Complete the rendering by adding the closing tag for the list wrapper component.
    10. Now, the desserts will be displayed in a simpler format, showing only the title and price.


![[Untitled.png]]

## Exercise: Create a basic List component