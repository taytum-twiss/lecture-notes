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
- a section tag

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
- Yes props can be sent back up to a parent component just like how it gets passed down.

13. How do you lift state?
- You can lift state by calling a function in a child component that is being defined in a parent component and passing it a new value for the state property you are trying to update/lift up so that the application can re-render and pass the new values back down in props.
  
  
  ---
  # create-react-app, Directory Structure, & package.json

1. What does CLI stand for?
    - command line interface
    - command line interpreter 
    - command line input 
    - AKA Linux Terminal 

2. What is the command line used for?
    - CLI is used by software developers and system administrators to configure computers, install software, and access features that are not available in the graphical interface.

3. What is the command that creates a new React app?
    - npx create-react-app name-my-app

4. What does create-react-app do?
    - Create React App is a comfortable environment for learning React, and is the best way to start building a new single-page application in React. It sets up your development environment so that you can use the latest JavaScript features, provides a nice developer experience, and optimizes your app for production. When we use create-react-app tool it creates a hierarchy of files and folder in an out-of-the-box, working application for us.

5. What does npx stand for?
    - Node Package Executer

6. What does npx do?
    - NPX comes built into npm. It is a node package runner and can execute any package/directory/library from the npm registry(the internet) without installing the package globally on your computer.

7. What does npm stand for?
    - Node Package Manager

8. What does npm do?
    - npm is the dependency/package manager you get out of the box when you install Node.js. It is a command line tool that aids you in installing packages both globally and locally; and manages their versions and dependencies.
  
9. What are the differences between npm and npx?
    - NPM is a tool that is used to install packages and NPX is a tool that is used to execute packages.

10. What is the command that starts the React server?
    - npm start

11. What URL do I navigate to in order to view my React app in the browser?
    - http://localhost:3000 (unless you already have something running on that port)

12. What is the purpose of a package.json?
    - It records important metadata about a project which is required before publishing to NPM. It also defines functional attributes of a project that npm uses to install dependencies, run scripts, and identify the entry point to our package. It specifies the dependencies being used in the project which helps npm setup the same environment on a different machine for our project.

13. What are node modules?
    - The node_modules folder is used to save all downloaded packages from NPM in your computer for the JavaScript project that you have.

14. What is the .gitignore?
    - This file specifies intentionally untracked files that Git should ignore. Any files listed in the .gitignore will NOT be pushed up to GitHub. This is useful to keep things like your secret keys safe, or to prevent pushing dependencies, like node_modules, to GitHub.

15. What is the purpose of the public directory?
    - This folder contains the HTML file, index.html. This is the page template and must be named exactly this because it is the template file which is served up when we start our script to launch our app. It is considered best practice not to create multiple html files in the public folder. You would normally only work in this folder when importing css libraries, images and fonts from JavaScript.

16. What is the purpose of the public/index.html?
    - It is the page template. Only files inside the public file can be used from public/index.html. When the application starts this is the first page that is loaded. This will be the only html file in the entire application since React is generally written using JSX. This file has a code of `<div id='root'></div> . This line is very significant since all the application components are loaded into this div.

17. What is the purpose of the src directory?
    - In simplest form it’s the mind of our app. It's containing all the components, tests, css files etc. 

18. What is the purpose of the src/index.js?
    - It is the JavaScript entry point and the JavaScript file corresponding to index.html . This is the most top level script that controls all the components under it.

19. What is significant about this line of code?
`ReactDOM.render(<App />, document.getElementById(‘root’));`
    - It is saying that the App Component has to be loaded into an html element with an id of root. This corresponds with the div element, that has the id of root, in the index.html. We call this a “root” DOM node because everything inside it will be managed by React DOM. Applications built with just React usually have a single root DOM node. To render a React element into a root DOM node, pass both to ReactDOM.render().

20. What is `ReactDOM`?
    - ReactDOM is an API that provides DOM specific methods that can be used at the top level of a web app, to manage those DOM elements. ReactDOM provides the render method and a few others. ReactDOM.render() controls the contents of the container node you pass in.

21. What is a difference between render() and ReactDOM.render()?
    - ReactDOM.render renders your components to the DOM while a component's render returns the elements that make up the component.

22. What is React.StrictMode?
    - Strict mode is a developmental tool and you don't need to worry about it impacting your production build. It is a helper component that will help you write better react components, you can wrap a set of components with <StrictMode /> and it will:
    - Verify that the components inside are following the recommended practices and warn you if not in the console.
    - Verify the deprecated methods are not being used, and if they're used strict mode will warn you in the console.
    - Help you prevent some side effects by identifying potential risks.

23. What can I get rid of when I am ready to start customizing my React application?
    - public/favicon.ico

  ---
  #Java-Script Built in Methods 
  1. List some of JavaScript's data types:
-objects, strings, arrays, and booleans and numbers are all data types. There are more as well.
  
2. In JavaScript, ______ __________ is an object.
- almost everything is an object in JS -arrays, booleans, more All JS values, except primitives, are objects

3. What are "JavaScript Primitives"?
- A primitive value is a value that has no properties or methods. A primitive data type is data that has a primitive value.

4. How many primitive data types are there?
- There are 7 data types. string, number, boolean, undefined, symbol, and null.

5. What are the three JavaScript Primative Wrapper types?
- JS provides three primitive wrapper types, : Boolean, Number, and string types.

6. What does a JavaScript Primative Wrapper do?
- make it easier to call JS built in methods on the primitive value.

7. What is the Primative Wrapper doing under the hood when you call a method on a variable that holds a number, a string, or a boolean?
- JS will create an object of a coresponding type. Then call the method on the instance. JS deletes the instance immediatly after it is finished with it and moves onto the next script.

8. What are functions that are binded to an object called?
- methods

9. So if almost everything in JavaScript is an object, what does that mean for most data types?
- most data types will have their very own special methods built into JS.

10. What do these special built-in methods do?
- a method can accomplish any number of poplar tasks in programming. A few popular tasks are: adding values, removing values, moving values, modyfying values or reading values.

11. How do we access a method on an object?
- dot notation 

12. How do we use a built-in method on a JavaScript data type?
- We use dot notation on the variable name to invoke the method.

13. What kind of built-in methods are we going to learn about in 301?
- string methods
- array methods
- object methods
- number methods
- math methods

14. Where can you go to learn about the different methods avaiable to each data type?
- google it
- MDN web docs
- w3Schools

15. How am I suppose to know what to search for in Google?
- An easy way to search for methods that would help solve your algorithm is to use this pattern: -"how to" + :do the thing" + "data type" + "JS"
  
  ---
  # How to solve a code challenge 
 
1.  Research that week's method or concept
- What are we learning this week
- Look it up on MDN or W3Schools
- Search for articles on the topic
- Watch videos on it
- Review notes
- Participate in class
  
2. Understand the problem
- Read the problem
- Identify key words or hints
- Identify the requirements
- Identify inputs
- Identify outputs
- View the test for input/output examples
  
3. Create a step-by-step plan (algorithm) for how you'll solve it
- Think about how this week's method/topic can be applied to solve it.
- Create a visual example with inputs
- Create a checklist of everything the function needs
- When creating an algorithm usually focus on example input/outputs
- Consider how the inputs will help get the outputs
  
4. Carry out the plan and write actual code
- Use your checklist, write code that will accomplish the tasks one at a time
- Complete your function
- Correct any syntax/linter errors.
- Don't forget to return solution
- Get the test to pass
  
5. Look back and possibly refactor your solution if it could be better
- Is the test passing?
- Does solution meet requirements?
- Does solution use this week's method?
- Can you understand code?
- Are there other ways to refactor?
- How did others solve it?
  
  ---
 # Array Review 
1. What is an array in JavaScript?
   - The JavaScript array is a list-like object.
  
2. What syntax do I use to create an array?
    - const, var, and let 
  
3. Is it common practice to use `var`, `let`, or `const` to declare an array?
    - It is common practice to use 'const' to declare an array.
  
4. Can an array that has been declared with const be reassigned?
    - no
  
5. Can an array that has been declared with const change the elements of the array?
    -  no, but you can add in more elements
  
6. Can we use spaces and line breaks between the elements of an array?
    - yes
  
7. How do you access an array element?
    - console.log(students[3]);
  
8. What number does an array index start at?
    - 0
  
9. Arrays are a special type of ______ in JavaScript.
    -  objects 
  
10. What does "traversal and mutation operations" mean?
    -  they mean that we can move through an array. Mutation means we can chnage the way it looks.
  
11. What does `array.length` do?
    -  the length property of returns the length
  
12. What does `array.push()` do?
    - the easiest way to add a new element to an array is using the push() method.
  
---
  # Review for Loops and Intro to Callback Functions 
  
 1. What are loops used for in programming?
For running the same code over and over again, with a different value every time.
  
2. What are the 5 different types of loops we work with in JavaScript?
for loop
while loop
do...while
for...in
for...of
  
3. What is the definition of a for loop?
It creates a loop that consists of three optional expressions, enclosed in parentheses and seperated by semicolons, followed by a statement (usuallty a block statement to be executed in the loop.
  
4. What is the syntax and pseudocode of a for loop?
for(initialExpression; conditionalExpression; iteratorExpression) { code block to run at every iteration; };
  
5. What does the initial expression do?
Ran once at the very beginning of the for loop and it initializes the variable used in the loop.
  
6. Why is it important to use let when declaring the i variable in a loop?
When let is used to declare the i variable in a loop, the i variable will only have scope within the loop.
  
7. What does the conditional expression do?
Defines the condition for the loop to run. If condition returns true, the loop will start over again, if it returns false, the loop will end.
  
8. What does the iterator expression do?
increments/decrements the value of the initial variable and moves the loop to the next iteration.
  
9. When a for loop executes, the following occurs:
STEP 1: The initializing expression is executed once and initializes a loop counter.
STEP 2: The conditional exression is evaluated. If it evaluates true, the loop statements execute. If it evaluates to false, the loop ends.
STEP 3: The statements inside the code block execute.
STEP 4: Then the iterator expression is executed and either increments or decrements the loop to the next iteration.
STEP 5: Lastly, we circle back up to STEP 2 and the for loop continues to run until the condition returns false.
  
10. What is a callback function?
  - a callback function is a function passed as an argument to another function. 
  
11. When do we use a callback function?
  - callback functions can run after another function has finished 

 ---
  # Intro to array.forEach

1. What is the definition of forEach?
    - array.forEach allows you to iterate through an array and executes a provided function once for each array element. forEach is more declarative or functional in nature.
  
2. What data type can you call forEach on?
    - array.forEach is implemented by as a method on an array.
   
3. What does the pseudocode for forEach look like?
    - array.forEach(callback(currentValue, index, arr), thisValue);
  
4. What are the 2 input arguments for forEach?
    - callback function 
    - currentValue
  
5. What are the arguments the callback function takes in?
    - index
    - array
    - thisValue
  
6. What is currentValue referring to?
    - the value of the current element in the array that map is looking at.
  
7. What is the output of forEach?
   - undefined 
  
8. Does forEach mutate the original array?
   - by default for.each doesn't mutate the original array.
  
9. What does it mean when an argument is optional?
   - An optional argument means that forEach does not care if you pass it a value or not
---  
# ✍️ Intro to Array.map

1. What is the definition of Array.map?
    * The map() method creates a new array populated with the results of calling a provided function on every element in the calling array.

2. What data type can you call map on?
    * key-value pair elements 

3. What does the pseudocode for map look like?
    * array.map(callback(currentValue, index, arr), thisValue);
  
4. What are the 2 input arguments for map?
   * callback function 
   * Contextual thisArg (optional)

5. What are the arguments the callback function takes in?
    * currentValue: The value of the current element in the array that map is looking at.
    * index(Optional): The index place of the currentValue
    * an array(Optional): The from which the currentValue belongs to

6. What is currentValue referring to?
    * The value of the current element in the array that map is looking at.

7. What is the output of map?
    * A new array with each element being the result of the callback function.

8. Does map mutate the original array?
    * Map does NOT mutute the original array

9. What does it mean when an argument is optional?
    * An optional argument means that map does not care if you pass it a value or not

10. What is the only difference between Array.forEach and Array.map?
    * The only difference between forEach and map is that .map() will always return a new array of the same length as the original array comprised of your return values and forEach will always return undefined.
---

# Functional Programming Reading 
1. What is functional porgramming?
    * Functional programming is a way of building the structure/elements that uses mathematical evaluations rather than changing-state.
2. What is a pure function and how do we know if something is a pure function?
    * A pure function returns the same result if givent he same arguments. It doesn't cause any observable side effects.
3. What are the benefits of a pure function?
    * The benefits of a pure function are that the code becomes easier to test and that creates a more straight foreward code. 
4. What is immutability?
    * Immutability means that the data's state cannot change after it has been created. If you need to change the data you must create a new object with a new             value. 
5. What is Referential transparency?
    * pure functions + immutable data = referential transparency. 
6. What is a module?
    * A module is a split section of code that has a certain functionallity in the application 
7. What does the word ‘require’ do?
    * It's a global object that you pass a string through that is required in the file. 
8. How do we bring another module into the file the we are working in?
    * You do './' with the name of your module also in your quotations 
9. What do we have to do to make a module available?
    * You have to specify which part need to be required and export it 

