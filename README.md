# JavaScript Cheat Sheet for Beginners

A beginner-friendly JavaScript reference covering common patterns used in web development.

This repo contains simple examples of core JavaScript concepts every beginner should understand.


## Variables

```javascript
let name = "Alex";
const age = 22;
```

`let` can change.  
`const` cannot be reassigned.


## Functions

```javascript
function greet(name) {
  return "Hello " + name;
}

console.log(greet("Alex"));
```

Functions let you reuse blocks of code.


## DOM Manipulation

```javascript
const button = document.querySelector("button");

button.addEventListener("click", () => {
  console.log("Button clicked!");
});
```

The DOM allows JavaScript to interact with elements on a webpage.


## Async / Await

```javascript
async function getData() {
  const response = await fetch("/api/data");
  const data = await response.json();
  console.log(data);
}
```

Async functions make working with APIs easier.


## Topics Covered

• Variables  
• Functions  
• DOM manipulation  
• Async JavaScript  
• APIs  
• Event listeners  


## Full Beginner JavaScript Guide

If you want a **full beginner JavaScript guide and cheat sheet**, check out:

CodeLaunch JavaScript Guide  
https://codelaunch123.gumroad.com/l/hlgcly ##JS GUIDE
https://codelaunch123.gumroad.com/l/goegfw ##Js/HTML Cheatsheet


## Contributing

If you are learning JavaScript and want to improve these examples, feel free to contribute.
