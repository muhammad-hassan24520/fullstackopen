# Full Stack Open - Part 1

## Student Information

* Name: Muhammad Hassan
* Course: Full Stack Open
* Part: Part 1 - Introduction to React

---

## Overview

In Part 1, I learned the fundamentals of React and modern JavaScript. I created simple React applications using Vite and practiced building reusable components, passing data through props, and working with JavaScript objects and arrays.

---

## Topics Covered

### 1. React Basics

* Creating React applications with Vite
* Understanding React components
* JSX syntax
* Rendering content to the browser

### 2. Components

* Creating functional components
* Reusing components
* Organizing code into smaller parts

Example:

```jsx
const Header = ({ course }) => {
  return <h1>{course}</h1>
}
```

### 3. Props

* Passing data from parent components to child components
* Using destructuring for cleaner code

Example:

```jsx
const Part = ({ part }) => {
  return (
    <p>
      {part.name} {part.exercises}
    </p>
  )
}
```

### 4. JavaScript Fundamentals

* Variables (`const`, `let`)
* Arrays
* Objects
* Functions
* Arrow Functions
* Array methods (`map`, `forEach`)
* Destructuring

### 5. Course Information Application

Built a React application that displays:

* Course name
* Course parts
* Number of exercises
* Total exercises

---

## Exercises Completed

### Exercise 1.1

* Created the initial React application.
* Displayed course information.

### Exercise 1.2

* Extracted content into reusable components.

### Exercise 1.3

* Stored course data inside JavaScript objects.

### Exercise 1.4

* Created reusable `Part` components.

### Exercise 1.5

* Used arrays of objects and passed data using props.

---

## Technologies Used

* React
* Vite
* JavaScript (ES6+)
* Node.js
* npm

---

## Learning Outcomes

After completing Part 1, I can:

* Create React applications using Vite
* Build and use React components
* Pass data with props
* Work with JavaScript objects and arrays
* Use arrow functions and array methods
* Structure simple React applications

---

## Project Structure

```text
part1/
│
├── src/
│   ├── App.jsx
│   ├── main.jsx
│   └── components/
│
├── public/
├── package.json
└── README.md
```

---

## Conclusion

Part 1 provided a strong foundation in React and modern JavaScript. The exercises helped me understand component-based development, props, and data handling, which are essential concepts for building larger React applications in the upcoming parts of the Full Stack Open course.
