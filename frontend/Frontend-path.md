# 🗺️ Blubito's Learning Path for Front-end developers 

## What is this?
This page is a **guide** for starting to learn to be a frontend developer. The topics are defined in such order that makes most sense going in a straight path from one topic to the next one. If you already have knowledge for specific topic - skip it directly and go to the next one. The resources that we have provided are mainly a reference points, you're free to use whatever resource/lesson/tutorial/etc. you like.

## 📚 Topics - Introduction and basics

### 📘 Programs
Install these programs:
- Git
- Node LTS
- VisualStudio Code

Understand how VS Code works
- Visual Studio Code Tutorial for Beginners - Introduction https://www.youtube.com/watch?v=VqCgcpAypFQ
- 25 VS Code Productivity Tips and Speed Hacks https://www.youtube.com/watch?v=ifTF3ags0XI


---


### 📘 Terminal/Command Line
Know the basics of working with terminal:
- 15+ Terminal Commands Every Developer Must Know https://www.youtube.com/watch?v=CV-ven_rxhw


---


### 📘 Git
Understand how git works, what's: repository, branch, pushing, pulling, commit message, Pull-Request(PR)/Merge-Request(MR).
1. Git and GitHub for Beginners - Crash Course https://www.youtube.com/watch?v=RGOj5yH7evk
2. Git for Professionals Tutorial - Tools & Concepts for Mastering Version Control with Git https://www.youtube.com/watch?v=Uszj_k0DGsg


---


### 📘 HTML & CSS

**🤝 What we exepct from you to know and understand**
- HTML
  - Most used tags
  - Semantics
  - Structure
- CSS
  - specificity
  - writing good selectors
  - working with
    - colors
    - fonts
    - sizes (width & height)
  - Box model
  - Units (px, rem, vw/vh)
  - Flow (normal flow, floats, position & z-index)
  - Flex
  - Grid
  - Responsive layouts and designs

**⭐ Plan**
1. Start with Traversy Media's Crash courses so you get a basic overview as fast as possible
   - HTML Crash Course For Absolute Beginners https://www.youtube.com/watch?v=UB1O30fR-EE
   - CSS Crash Course For Absolute Beginners https://www.youtube.com/watch?v=yfoY53QXEnI
   - JavaScript Crash Course For Beginners https://www.youtube.com/watch?v=hdI2bqOjy3c
2. Go through our own internal course to connect everything from the crash courses about HTML & CSS
   - Blubito HTML & CSS Basics Jun 2022 https://web.microsoftstream.com/channel/8d2ca42b-0b0b-4fc4-ac10-9cf2f44575be (you need your Blubito account here)
   - It's an internal course
   - We take a look at some more specific points in addition to everything basic
3. Responsive design
   - Introduction To Responsive Web Design https://www.youtube.com/watch?v=srvUrASNj0s


---


### 📘 Programming basics and Computer Science
Whatever programming language you choose the main part of programming is always the same - What are Variables? What are Conditional Statements? What are Array’s? What are Loops? What are Errors? Etc., etc... 

Here you can understand the universal basics of programming before going into JavaScript and its own syntax.

- Introduction to Programming and Computer Science - Full Course https://www.youtube.com/watch?v=zOjov-2OZ0E


---


### 📘 JavaScript
Here you can take any "big" course so you understand the basics of JS. We have linked a course that we think covers the most important parts in a nice and understandable way.

**🤝 What we exepct from you to know and understand**

**JS fundamentals**
- Data types
- Scope
  - global, function
  - var, let, const
  - hoisting
- Comparisons
- Type conversion, particularly to boolean
- Logical Operators
- Conditions
- Logging and Debugging

**Functions**
- return values of functions
- null vs. undefined
- conditional returns
- parameters & their scope
- default params
- destructuring parameters
- rest operator
- callback functions

**Objects**
- creating and manipulating objects (adding properties, deleting properties, extracting properties)
- nesting objects and objects with functions
- understanding referential vs. primitive types
- copying objects
- spread operator
- destructuring objects and setting default values
- iterating over object properties/values
- conditional properties
- computed properties

**Working with iterables**
- Arrays
  - creating and manipulating arrays (adding elements, removing elements, finding elements, splitting arrays, joining arrays)
  - copying arrays
- Loops (for-in vs. for of)
- map, filter, reduce
  - learn when to use map, filter and reduce
  - functional vs. procedural programming

**Misc**
- Asynchronous JS
  - creating promises
  - then and callbacks vs. async/await syntax
  - understanding the event loop
- Error handling
- Code splitting
  - ES modules vs. CommonJS modules
  - dynamic asynchronous imports
- Closure
  - understanding what problems the concept solves
- DOM
  - understanding the relationship between HTML and the DOM
  - finding elements in the DOM
  - attaching and removing event-listeners through the DOM
  - adding to and removing elements from the DOM


**⭐ Plan**
- Jonas Schmedtmann: The Complete JavaScript Course 2023: From Zero to Expert! https://www.udemy.com/course/the-complete-javascript-course/


---


### 📘 CSS Advanced
**🤝 What we exepct from you to know and understand**
- SASS
- CSS Variables
- `.module` usage (CSS/SASS modules)
- structure and reusage of code
- Conventions
  - BEM CSS
  - CUBE CSS
  - Atomic CSS


**⭐ Plan**
-  The Net Ninja: SASS Tutorial (Build Your Own CSS Library) https://www.youtube.com/playlist?list=PL4cUxeGkcC9jxJX7vojNVK-o8ubDZEcNb
- Kevin Powell: CSS Custom Properties https://www.youtube.com/playlist?list=PL4-IK0AVhVjOT2KBB5TSbD77OmfHvtqUi
- Harry Wolff: CSS Modules: Why are they great? https://www.youtube.com/watch?v=pKMWU9OrA2s


---


### 📘 TypeScript
Understand how TypeScript (TS) works and how you can use it to write better and safer code. We advize on taking both courses - while TypeScript Speedrun will help you grasp the basics pretty fast, Understanding TypeScript goes through multiple topics, which you **will** be needing sooner or later.

- TypeScript Speedrun: Crash Course for Beginners https://www.youtube.com/watch?v=YmxwicpROps
- Understanding TypeScript https://www.udemy.com/course/understanding-typescript/


---


## 🤖 Frameworks - ![](https://img.shields.io/badge/-React-blue?logo=react&logoColor=white)

The main resources we recommend here is:
- React - The Complete Guide https://www.udemy.com/course/react-the-complete-guide-incl-redux/
- React's new docs - https://beta.reactjs.org/
  - ! While this is "just a documentation" there's a lot of information not only about the syntax, but also in general what React is and how to use it.

### 📘 Step 1: Basics
**🤝 What we exepct from you to know and understand**
- Setuping a project
- JSX
- Syntax
- What's a component, when and why to create one
- Functional components
- Props
- State
- The concept of hooks (useState)
- Conditional rendering
- Component lifecycles

**💻 Tasks & homework**

🟢 01 - [Register page](tasks/react/register/Readme.md)

---

### 📘 Step 2: Context and hooks
**🤝 What we exepct from you to know and understand**
- useEffect
- useCallback
- useRef
- useMemo
- useReducer
- Creating custom hooks
- Context API

**💻 Task**

🟢 02 - [Meme generator](tasks/react/meme-generator/Readme.md)

🟡 03 - [Kanban Board](tasks/react/kanban-board/Readme.md)

🟠 04 - [Access Page](tasks/react/access-page/Readme.md)

--- 

### 📘 Step 3:  State management
- Why do we need state management
- MobX

**💻 Task**
> Coming soon


## 🤖 Frameworks - ![](https://img.shields.io/badge/-Angular-red?logo=angular&logoColor=white)
> Comming soon