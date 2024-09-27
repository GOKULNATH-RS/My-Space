---
title: 'Introduction to TypeScript'
tags: ['TypeScript', 'JavaScript', 'Typed Language']
date: '29 Sept, 2024'
href: '/blog/typescript-intro'
---

TypeScript is a superset of JavaScript that adds static typing to the language. It helps catch errors early in the development process, making your code more robust and maintainable. This blog post will walk you through the basics of TypeScript, explaining its key features and how to get started.

## What is TypeScript?  
TypeScript extends JavaScript by adding types. This means you can catch type-related errors during development instead of at runtime, leading to fewer bugs and easier-to-maintain code. TypeScript code is transpiled into JavaScript, making it compatible with any environment where JavaScript runs.

## Installing TypeScript  
You can install TypeScript using npm (Node Package Manager). If you haven't already, install Node.js first, then run the following command:

```bash
npm install -g typescript
```

Basic TypeScript Example
Here’s a simple TypeScript example demonstrating how to use types:

```typescript
function greet(name: string): string {
  return `Hello, ${name}!`;
}

const userName: string = "John";
console.log(greet(userName)); // Output: Hello, John!
```
## How to Compile TypeScript?
To compile your TypeScript code into JavaScript, run the following command:

```bash
tsc yourFileName.ts
```
This will generate a yourFileName.js file that you can execute using Node.js or include in your HTML files.

By integrating TypeScript into your projects, you'll enjoy a smoother development experience with improved code quality and fewer runtime errors.