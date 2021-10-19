<!-- <h3 align="center"><a href="class-07/README.md">👈 Back to Table of Contents</a></h3>

--- -->

# ES6 Notes
- What is ES6?
  -  ES6 is a standardized version of Javascript.

- When was ES6 released?
  -  ES6 was released in 2015 and added many powerful features.

- List 5 new features of ES6.
  -  arrow functions: simpler way to create a function 
  -  let & const: in place of var
  -  classes: to create different objects based on different types of data 
  -  promises: when someone makes a call to a data base and java promises that when it gets that info it'll give it to you
  -  modules (modulization): sectioning, import & exporting things into code that allow it ot stay organized

- What are the new type of functions called that we will be using in 301?
  -  arrow functions 

- What do the keywords `let` and `const` do?
  -  let and const are essentially the same thing as var

---
# Classes Notes
1. What is a class?
- a class is a template for creating objects.

2. What is an object?
- an object is one of Javascript's data types. It is used to store various keyed collections and more complex entities. 

3. How do we identify an object?
- you can identify an object by its syntax. key/value pairs, curly brackets

4. What is the data inside the object called?
- 

5. How did we create objects in 201?
- we used constructor functions

6. Explain the difference between a parameter and an argument:
- arguments are the data that fufill the parameters in the function

7. What is special about a class's name?
- it is capitalized

8. What does the constructor method do?
- a special methed for creating and initializing an object. there can only be one method with the name "constructor" in the class. 

9. What keyword will allow a constructor to call the constructor of a super class?
- the keyword "super"

10. What keyword creates a new instance of a class?
- the keyword "new"

---
# App Component
1. What does the import statement do?
- The static import statement is used to import read only live bindings which are exported by another module.

2. How does React know you are referring to a React component?
- To define a React component class, you need to extend React.Component

3. What is `<Header />`, `<Main />` and `<Footer />`?
- HTML 

4. Why must a user-defined component be capitalized?
- If the component name is not capitalized, React will think it is an HTML tag instead 

5. What is a fragment?
- Fragments let you group a list of children without adding extra nodes to the DOM.

6. What does the keyword `class` tell us about this App Component?
- It tells us it's an ES6 class.

7. What does the keyword `extends` do?
- The extends keyword is used to create a class that is a child of another class.

8. What data type is React.Component?
- It's a class

9. When do you not need to implement a constructor method?
-If you don’t initialize state, you don’t need to implement a constructor for your React component.

10. What does `super(props)` do?
- The super keyword is used to access and call functions on an object's parent.

11. What do we know about the state object?
-  The state object is where you store property values that belongs to the component.When the state object changes, the component re-renders.

12. What does `render()` do?
- The render() method is the only required method in a class component. When called, it should examine this.props and this.state and can return React elements, arrays, strings, numbers, booleans or null

13. What does `export default` do?
- The export statement is used when creating JavaScript modules to export live bindings to functions, objects, or primitive values from the module so they can be used by other programs with the import statement.

---
# JSX Notes 
1. What is this particular syntax called?
> `const element = <h1>Hello, world!</h1>;`
- The class attribute is a much used attribute in HTML, but since JSX is rendered as JavaScript, and the class keyword is a reserved word in JavaScript, you are not allowed to use it in JSX. JSX solved this by using className instead. When JSX is rendered, it translates className attributes into class attributes.

2. What is JSX?
-  JSX allows us to write HTML elements in JavaScript and place them in the DOM without any createElement() and/or appendChild() methods.

3. What does React use to render JSX to the DOM?
- JSX uses react's rendering API called ReactDom.

4. In order to write HTML on multiple lines, what syntax do we need to put the HTML inside of?
- <section>

5. What is a "top level element"?
- The HTML code must be wrapped in ONE top level element(parent element), like a fragment

6. What attribute can we use in JSX to assign a CSS class selector?
- You use the className answer.

7. With JSX you have to write JavaScript expressions inside of what syntax?
- You have to write it in curly brackets

---
# Component State Notes 
1. Class Components have a built-in object called what?
- They have a built in state object.

2. What do you store in the state object?
- It's where you store property values that belongs to that particular component.

3. What happens to make the component re-render?
- The state object changes or updates the component re-renders.

4. If your component has a constructor, what needs to be passed to it?
- The props should always be passed to the constructor and also to the React.Component via the super() method.

5. What happens if `super(props)` isn't called?
- The state object won't be initialized in the constructor.

6. How many properties can your state object have?
- You can have as many properties in the state object as you want.

7. What happens when a value in the state object changes?
- The component will re-render, it will output the change according to the new values.

8. What method do you use to update the state object?
- Use the setState() method to make changes to state object.

9. What syntax allows us to access to a value in state?
- Use this.state.propertyname syntax

10. What does onClick do?
-  A button with an onClick event that will update our state properties.

11. What kind of function do we use when defining our custom methods?
- A render function.

  
---
# Props and One Way Data Flow 
1. What does the term "props" stand for?
- props stands for properties.

2. What are props in React?
- Props are arguments passed into React Components. 

3. What are props typically used for in React?
- They are used to pass data from one component to another.

4. How are props passed to components?
- Props are passed to components via HTML attributes.

5. What syntax is used to pass props to a component?
- Props use the same syntax as HTML attributes. 

6. A component will receive props as what kind of data type?
- A component will receive props as an object.

7. In order to access the data inside of props, what kind of notation should we use?
- Use dot notation.

8. If we are trying to send a variable in props to a component, what syntax does the variable need to be wrapped in?
- The variable needs to be wrapped in curly brackets.

9. Can you send a custom method in props to another component?
- Yes 

10. Where is the most popular place we are going to get values from to send in props to other components?
- 

11. When accessing a value in props, what syntax do we use?
-  this.props.propertyName syntax
  
12. Can you send props back up to a parent component?
- 

13. How do you lift state?
- 


## 📚 Resources 
- [ES6 Features](http://es6-features.org/#Constants)
- [W3 Schools: ES6](https://www.w3schools.com/js/js_es6.asp)
- [Free Code Camp: ES6](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/#es6)
