# Javascript-Basics
A repo created while learning basics of javascript.

Intoduction:
    
JavaScript is a lightweight, cross-platform, single-threaded, and interpreted compiled programming language. It is also known as the scripting language for webpages. It is well-known for the development of web pages, and many non-browser environments also use it.

JavaScript is a weakly typed language (dynamically typed). JavaScript can be used for Client-side developments as well as Server-side developments. JavaScript is both an imperative and declarative type of language. JavaScript contains a standard library of objects, like Array, Date, and Math, and a core set of language elements like operators, control structures, and statements. 

How to Link JavaScript File in HTML ?
JavaScript can be added to HTML file in two ways:

Internal JS: We can add JavaScript directly to our HTML file by writing the code inside the <script> tag. The <script> tag can either be placed inside the <head> or the <body> tag according to the requirement.
External JS: We can write JavaScript code in another files having an extension.js and then link this file inside the <head> tag of the HTML file in which we want to add this code.

History of JavaScript
It was created in 1995 by Brendan Eich while he was an engineer at Netscape. It was originally going to be named LiveScript but was renamed. Unlike most programming languages, JavaScript language has no concept of input or output. It is designed to run as a scripting language in a host environment, and it is up to the host environment to provide mechanisms for communicating with the outside world. The most common host environment is the browser. 

Features of JavaScript
According to a recent survey conducted by Stack Overflow, JavaScript is the most popular language on earth. 
With advances in browser technology and JavaScript having moved into the server with Node.js and other frameworks, JavaScript is capable of so much more. Here are a few things that we can do with JavaScript: 

JavaScript was created in the first place for DOM manipulation. Earlier websites were mostly static, after JS was created dynamic Web sites were made.
Functions in JS are objects. They may have properties and methods just like other objects. They can be passed as arguments in other functions.
Can handle date and time.
Performs Form Validation although the forms are created using HTML.
No compiler is needed.

Applications of JavaScript
Web Development: Adding interactivity and behavior to static sites JavaScript was invented to do this in 1995. By using AngularJS that can be achieved so easily.
Web Applications: With technology, browsers have improved to the extent that a language was required to create robust web applications. When we explore a map in Google Maps then we only need to click and drag the mouse. All detailed view is just a click away, and this is possible only because of JavaScript. It uses Application Programming Interfaces(APIs) that provide extra power to the code. The Electron and React are helpful in this department.
Server Applications: With the help of Node.js, JavaScript made its way from client to server and Node.js is the most powerful on the server side.
Games: Not only in websites, but JavaScript also helps in creating games for leisure. The combination of JavaScript and HTML 5 makes JavaScript popular in game development as well. It provides the EaseJS library which provides solutions for working with rich graphics.
Smartwatches: JavaScript is being used in all possible devices and applications. It provides a library PebbleJS which is used in smartwatch applications. This framework works for applications that require the Internet for their functioning.
Art: Artists and designers can create whatever they want using JavaScript to draw on HTML 5 canvas, and make the sound more effective also can be used p5.js library.
Machine Learning: This JavaScript ml5.js library can be used in web development by using machine learning.
Mobile Applications: JavaScript can also be used to build an application for non-web contexts. The features and uses of JavaScript make it a powerful tool for creating mobile applications. This is a Framework for building web and mobile apps using JavaScript. Using React Native, we can build mobile applications for different operating systems. We do not require to write code for different systems. Write once use it anywhere!

Limitations of JavaScript
 Security risks: JavaScript can be used to fetch data using AJAX or by manipulating tags that load data such as <img>, <object>, <script>. These attacks are called cross-site script attacks. They inject JS that is not part of the site into the visitor’s browser thus fetching the details. 
Performance: JavaScript does not provide the same level of performance as offered by many traditional languages as a complex program written in JavaScript would be comparatively slow. But as JavaScript is used to perform simple tasks in a browser, so performance is not considered a big restriction in its use.
Complexity: To master a scripting language, programmers must have a thorough knowledge of all the programming concepts, core language objects, and client and server-side objects otherwise it would be difficult for them to write advanced scripts using JavaScript.
Weak error handling and type checking facilities: It is a weakly typed language as there is no need to specify the data type of the variable. So wrong type checking is not performed by compile.

JavaScript is considered lightweight due to the fact that it has low CPU usage, is easy to implement, and has a minimalist syntax. Minimalist syntax as in, has no data types. Everything is treated here as an object. It is very easy to learn because of its syntax similar to C++ and Java.

A lightweight language does not consume much of your CPU’s resources. It doesn’t put excess strain on your CPU or RAM. JavaScript runs in the browser even though it has complex paradigms and logic which means it uses fewer resources than other languages. For example, NodeJs, a variation of JavaScript not only performs faster computations but also uses fewer resources than its counterparts such as Dart or Java.

Additionally, when compared with other programming languages, it has fewer in-built libraries or frameworks, contributing as another reason for it being lightweight. However, this brings a drawback in that we need to incorporate external libraries and frameworks. 

JavaScript is both compiled and interpreted. In the earlier versions of JavaScript, it used only the interpreter that executed code line by line and shows the result immediately. But with time the performance became an issue as interpretation is quite slow. Therefore, in the newer versions of JS, probably after the V8, the JIT compiler was also incorporated to optimize the execution and display the result more quickly. This JIT compiler generates a bytecode that is relatively easier to code. This bytecode is a set of highly optimized instructions. 
The V8 engine initially uses an interpreter, to interpret the code. On further executions, the V8 engine finds patterns such as frequently executed functions, and frequently used variables, and compiles them to improve performance.

JavaScript is best known for web page development but it is also used in a variety of non-browser environments. 

Introduction to Object Oriented Programming in Javascript :

The concept of Object Oriented Programming in JavaScript was introduced in ES6. Before ES6 JavaScript did not support the OOPs and it was a completely functional-based programming language everything was done with the help of functions. We can implement the OOPs in ES6 by creating classes and their object instances. Now, after the introduction of ES6, JavaScript become an Object Oriented Programming language as it supports all four basic pillars of OOPs which are inheritance, encapsulation, abstraction, and polymorphism.

As JavaScript is widely used in Web Development, in this article we will explore some of the Object Oriented mechanisms supported by JavaScript to get the most out of it. Some of the common interview questions in JavaScript on OOPS include:

How is Object-Oriented Programming implemented in JavaScript? 
How does it differ from other languages? 
Can you implement Inheritance in JavaScript?
and so on…

There are certain features or mechanisms which make a Language Object-Oriented like:

OOPs Concept in JavaScript

Object	Classes	Encapsulation
Abstraction	Inheritance	Polymorphism
Let’s dive into the details of each one of them and see how they are implemented in JavaScript.

Object: An Object is a unique entity that contains properties and methods. For example “a car” is a real-life Object, which has some characteristics like color, type, model, and horsepower and performs certain actions like driving. The characteristics of an Object are called Properties in Object-Oriented Programming and the actions are called methods. An Object is an instance of a class. Objects are everywhere in JavaScript, almost every element is an Object whether it is a function, array, or string. 

Note: A Method in javascript is a property of an object whose value is a function. 

The object can be created in two ways in JavaScript:

Object Literal
Object Constructor

Note: The JavaScript Object.create() Method creates a new object, using an existing object as the prototype of the newly created object.

Classes: Classes are blueprints of an Object. A class can have many Objects because the class is a template while Objects are instances of the class or the concrete implementation. 
Before we move further into implementation, we should know unlike other Object Oriented languages there are no classes in JavaScript we have only Object. To be more precise, JavaScript is a prototype-based Object Oriented Language, which means it doesn’t have classes, rather it defines behaviors using a constructor function and then reuses it using the prototype. 

Abstraction: Abstraction means displaying only essential information and hiding the details. Data abstraction refers to providing only essential information about the data to the outside world, hiding the background details or implementation. 

Encapsulation: The process of wrapping properties and functions within a single unit is known as encapsulation. 

Inheritance: It is a concept in which some properties and methods of an Object are being used by another Object. Unlike most of the OOP languages where classes inherit classes, JavaScript Objects inherit Objects i.e. certain features (property and methods) of one object can be reused by other Objects. 

Note: The Person and Student objects both have the same method (i.e toString()), this is called Method Overriding. Method Overriding allows a method in a child class to have the same name(polymorphism) and method signature as that of a parent class. 

Polymorphism: Polymorphism is one of the core concepts of object-oriented programming languages. Polymorphism means the same function with different signatures is called many times. In real life, for example, a boy at the same time may be a student, a class monitor, etc. So a boy can perform different operations at the same time. Polymorphism can be achieved by method overriding and method overloading

JavaScript is best known for web page development but it is also used in a variety of non-browser environments.