# ASSESSMENT 4: REACT ASSESSMENT
## Interview Practice Questions

Answer the following questions. First, without external resources. Challenge yourself to answer from memory. Then, research the question to expand on your answer. Even if you feel you have answered the question completely on your own, there is always something more to learn.  

1a. Indicate which of the following statements about React are false:

- React is a modern, efficient answer to complex UI applications: True
- React will only render on the server using Node.js: False
- React is a full stack framework for modern web applications: False
- React is a flexible library that plays the role of V in an MVC framework: True
- You should always update a component's state directly using this.state: False
- React is made up of encapsulated components that manage their own state: True
- React components render HTML: False. But the JSX is HTML syntax

1b. Add an interesting true fact about React to the list.
React can be used functionally or in an object oriented manner 
2. What are "smart" and "dumb" components? Explain the difference and also add why we bother to make the distinction between them.

  Your answer: Smart components have state and they can pass that state onto other children. Dumb components usually just display, but can also have state. It is important to make a distinction for state tree and organization purposes and for being to keep track of what state a component is

  Researched answer: Smart components (or container components) on the other hand have a different responsibility. Because they have the burden of being smart, they are the ones that keep track of state and care about how the app works. Dumb components are also called ‘presentational’ components because their only responsibility is to present something to the DOM. Once that is done, the component is done with it. 



3. When we use "yarn add ..." in the terminal - what is yarn doing? And what file will always be automatically updated after we add a package with yarn?

  Your answer: Yarn is adding a package to our dependencies

  Researched answer: This will automatically add the [package] to your dependencies in your package.json. It will also update your yarn.lock to reflect the change.



4. How would you explain state to a friend who doesn't know code?

  Your answer: Imagine you have a glass. There is no water in your glass and that is the default or your state. As you add more water you can say my glass is 1/4th full or 1/2 full etc. Every time you change the amount of water you are changing your state.

  Researched answer:



5. What is the difference between component state and props? Your answer should include a short explanation of both.

  Your answer: State is something that is unique to the component but props are states or variables that are passed from the parent component. It is a way of passing information from the parent component into the child component. 

  Researched answer: 
  State - This is data maintained inside a component. It is local or owned by that specific component. The component itself will update the state using the setState function.

  Props - Data passed in from a parent component. props are read-only in the child component that receives them. However, callback functions can also be passed, which can be executed inside the child to initiate an update.
