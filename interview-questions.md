# ASSESSMENT 3: Interview Practice Questions

1. What is JSX? What is one syntax difference between HTML and JSX?

Your answer: JSX is a programming language that uses HTML & JavaScript, together and is combined with the JavaScript framwork, React. The difference between the syntax is, JSX requires camelCase while HTML does not.

Researched answer: JSX stands for JavaScript XML and it is an extension of JavaScript, with it we are able to use HTML- like syntax in React. The one difference between HTML and JSX is that all attributes in JSX use camelCase. JavaScript has a list of reserved words and so words like "class" would be written as className. 

2. What is yarn? What file(s) are modified in a React application when you run the command yarn in your terminal?

Your answer: Yarn is a software used for JavaScript projects and we've used in conjunction with React. Files that are modified in a React application when you run the yarn command in terminal are the Javascript files. 

Researched answer: Yarn is a package manager used for JavaScript projects. A developer might use Yarn to facilitate with installation of libraries and frameworks. For example, a developer might use the Yarn add react command to install the React library as a dependency for a project. When you run "yarn" in your terminal, the 'package.json" file will be modified and any changes made will be reflected. If working on a group project, the yarn.lock file may be modified to ensure that all developers are working on identical verions of the dependency.

3. What is a React component?

Your answer: A React component is used for functions. It is a needed to pass information from one file to another and aids in functionality. 

Researched answer: A React component plays a crucial role in the way information is displayed to a user. It is a peice of code that can be reused and defines the User Interface. Components can either be written as a class or a function. An example of a functional component would be:
import React from 'react';

function MyComponent(props) {
  return (
    <div>
      <h1>This book is written by, {props.author}!</h1>
      <p>The title of this book is {props.title} .</p>
    </div>
  );
}
export default MyComponent;

Here, our component accepted two props; 'author' and 'title'. The component returns a div and that div can be used in another part of the application. The nice thing about using your components in React is that it can make your code more managable by splitting your UI into multiple little pieces of code that helps construct your app.
 
4. What is the difference between state values and props in React?

Your answer: The difference between state values and props in React is the accessibility. You can deposit and withdrawl state values at any moment. Props is used to ...

Researched answer: Most times, State is used to store information in a component and can change over time. Props are strictly based on inputs passed to a component from its parent. You can use props to change the appearance of a "child" component and in general use a heirarchy. For example:
function MyComponent(props) {
  // Declare a state value using the useState hook
  const [count, setCount] = useState(0);
The State Value in this section of code is "count". The props are passed through can be passed through to change the data displayed.

5. What is the DOM?

Your answer: DOM is a tool used to make changes to a document and can be accessed from JavaScript code.  

Researched answer: Document Object Model is a programming interface for HTML and XML documents. Often modeled as a tree branch, the structure has different objects that represent different parts of a document. Using the DOM, a developer can delete, add or change elements of a HTML page and or change values of attributes. 

6. STRETCH: Which is the difference between a div and a span?

Your answer: A DIV stores information and is able to group together elements while a span allows you to work within the code.  

Researched answer: Div elements are block level while span elements are inline. Because divs are block level, they take up the entire width of their parent container and a new line is created after them. Span elements are inline and can be placed within a line of text and no new line is needed.

## Looking Ahead: Terms for Next Week
 
1. Object-oriented programming: Object-oriented programming, also known as OOP, is one of the most popular program paradigm used in software development. OOP uses the concept of objects and classes and used to provide structure to structure a software program. Simple code classes are created and they are able to be re-used to create individual instances of objects. Many programming languages use OOP, some of which include Javascript and Python. 

2. Ruby: Ruby is an object-oriented, scripting programming language that can be used on its on or in conjunction with the Ruby on Rails framework. Ruby can either be used for front or back end development. 

3. Implicit return: An Implicit Return is a return that does not need to have the word "return" in it. It is implied, for example the arrow function let func = x => 4+3 // there are no brackets needed for an implicit return
4. Ruby blocks: Ruby blocks are anonymous functions that can be used to pass in methods. The blocks are enclosed in a "do-end" statement OR curly braces and can have arguments, which would be defined in between two pipe characters, for example [3,4,5].each  {|n| puts n }
5. Ruby hashes: Ruby hashes are similar to arrays, it has unique keys that are attached to a specific value for example p Hash ["x", 25, "y", 20]
