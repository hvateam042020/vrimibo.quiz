# Vrimibo Quiz
​
This project is in collaboration with Yeagger B.V. 
Yeagger is a startup company that wants to help other startups grow into the companies they want to be. They do this by providing an app for their customers where they will be able to sell their services.
​
Yeagger would like to have a quiz app for internal use. This quiz app will be used to hold quizzes during customer feedback but also just for fun on a friday evening.
​
Pointers Yeagger wants to achieve:
* The quiz app should have customisable content
* The quiz app should have a dashboard to create/delete this customisable content
* The quiz app should be somewhat real time
* The quiz app should give the users a competitive feel when answering questions
* The app must work on Android (iOS is optional)
​
​
# Deliverables
* [Project Plan](https://docs.google.com/document/d/1CNFJJaoMn59lAaUDVl_USS3kQyKytjmTjy953f0jS9Q/edit?usp=sharing) 
​
# Project Management
* [Trello](https://trello.com/b/bCI44nDN/team-4)
* [Github](#)

# Documentation
## Programming Language
JavaScript (JS) is a lightweight, interpreted, or just-in-time compiled programming language with first-class functions. While it is most well-known as the scripting language for Web pages, many non-browser environments also use it, such as Node.js, Apache CouchDB and Adobe Acrobat. JavaScript is a prototype-based, multi-paradigm, single-threaded, dynamic language, supporting object-oriented, imperative, and declarative (e.g. functional programming) styles.

TypeScript (TS) is an open-source language which builds on JavaScript, one of the world’s most used tools, by adding static type definitions. Types provide a way to describe the shape of an object, providing better documentation, and allowing TypeScript to validate that your code is working correctly. Writing types can be optional in TypeScript, because type inference allows you to get a lot of power without writing additional code.

All valid JavaScript code is also TypeScript code. You might get type-checking errors, but that won't stop you from running the resulting JavaScript. While you can go for stricter behavior, that means you're still in control.

TypeScript code is transformed into JavaScript code via the TypeScript compiler or Babel. This JavaScript is clean, simple code which runs anywhere JavaScript runs: In a browser, on Node.JS or in your apps.

## Backend NodeJS Express.js
Node allows developers to write JavaScript code that runs directly in a computer process itself instead of in a browser. Node can, therefore, be used to write server-side applications with access to the operating system, file system, and everything else required to build fully-functional applications.

Node.js is written in C, C++, and JavaScript, and it is built on the open-source JavaScript engine which also powers JS in browsers such as Google Chrome. As V8 supports new features in JavaScript, they are incorporated into Node.

Express is a minimal and flexible Node.js web application framework that provides a robust set of features for web and mobile applications. With a myriad of HTTP utility methods and middleware at your disposal, creating a robust API is quick and easy. Express provides a thin layer of fundamental web application features, without obscuring Node.js features that you know and love.

## Frontend NativeScript-Vue
NativeScript is an open source framework for building truly native mobile applications using JavaScript.

Vue is a progressive framework for building user interfaces. The core library is focused on the view layer only, and is very easy to pick up and integrate with other libraries or existing projects.

NativeScript-Vue is a NativeScript plugin which allows you to use Vue.js to craft your mobile application.

Why would you use this?
There are many options to build mobile apps. Here are some situations where we think NativeScript-Vue is a great fit.

You need a truly native iOS and Android app: NativeScript builds your apps using native user interface components on iOS and Android. The apps you build are not web-based, and therefore are not subject to the limitations inherent in WebView-based application frameworks. NativeScript also provides an extensive collection of plugins to tie into native device features. So if you need to tie into an iOS or Android API or feature as part of your app, you can do that with NativeScript.

With NativeScript you write your mobile applications in JavaScript — not Objective-C, not Swift, and not Java. If you like JavaScript, you’ll love writing native iOS and Android apps with the same language you use in your Web and/or Node apps.

Vue is known for its simple approach to the view layer. If you like building web apps with Vue, you’ll be right at home with NativeScript-Vue, as you’ll be using the same syntax for handling common tasks like data binding and event handling.

## Code conventions
Variable Names
we use camelCase for identifier names (variables and functions). All names start with a letter.

Spaces Around Operators
Always put spaces around operators ( = + - * / ), and after commas.

Code Indentation
Always use 2 spaces for indentation of code blocks.

Statement Rules
Always end a simple statement with a semicolon.

Object Rules
- Place the opening bracket on the same line as the object name.
- Use colon plus one space between each property and its value.
- Use quotes around string values, not around numeric values.
- Do not add a comma after the last property-value pair.
- Place the closing bracket on a new line, without leading spaces.
- Always end an object definition with a semicolon.

Naming Conventions
- Variable and function names written as camelCase
- Global variables written in UPPERCASE (We don't, but it's quite common)
- Constants (like PI) written in UPPERCASE
- Should you use hyp-hens, camelCase, or under_scores in variable names?

Hyphens in HTML and CSS:
- HTML5 attributes can start with data- (data-quantity, data-price).
- CSS uses hyphens in property-names (font-size).
