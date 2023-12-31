# Node.js Interview Questions

## Beginner Level

### 1. Benefits of using Node.js
   - Node.js provides several advantages, including:
     - Asynchronous APIs, making it event-driven and non-blocking.
     - Fast code execution powered by the Google Chrome V8 JavaScript Engine.
     - Single-threaded model with event looping for high scalability.
     - No buffering due to the event mechanism.

### 2. Global Installation of Dependencies
   - Dependencies installed globally in Node.js are stored in the `/npm` directory. These globally installed dependencies, marked with the `-g` flag, are accessible in the CLI but not directly importable in Node applications using `require()`.

### 3. REPL in Node.js
   - REPL stands for Read Eval Print Loop. It enables executing ad-hoc JavaScript statements directly in the shell. It's beneficial for debugging, testing, and experimenting.

### 4. Define Node.js
   - Node.js is a JavaScript Runtime Environment used for developing server-side applications.

### 5. Node.js Cross-Platform Compatibility
   - Yes, Node.js is cross-platform and can run on Windows, Linux, Unix, and macOS.

### 6. What Makes Node.js Different?
   - Node.js is asynchronous and event-driven, setting it apart from other JavaScript environments.

### 7. Is Node.js Open-Source?
   - Yes, Node.js is open-source and cross-platform.

### 8. Applications Built with Node.js
   - Node.js is versatile, allowing developers to build web applications, chat applications, real-time applications, streaming applications, APIs, and desktop applications, etc.

### 9. Does Node.js Use JavaScript?
   - Node.js is based on JavaScript and uses the V8 engine developed by Google. It is used for building server-side applications.

### 10. Can We Run Node.js on Windows?
   - Yes, it is possible to run Node.js on Windows.

### 11. What Do You Mean by I/O?
   - I/O stands for input/output, which helps write and read files and network operations.

### 12. What Are the Two Data Types Categories in Node.js?
   - Node.js supports two categories of data types - primitive and non-primitive.

### 13. Name Types of API Functions Supported by Node.js?
   - Asynchronous non-blocking and synchronous blocking are the two different types of API functions that Node.js supports.

### 14. Why Does Google Use V8 for Node.js?
   - Google uses V8 for Node.js because it is faster and more efficient. It compiles the JavaScript code directly into machine code.

### 15. Which Extension Is Used to Save Node.js Files?
   - .js extension is used to save Node.js files.

### 16. What Is the Full Form of npm?
   - Npm stands for the Node package manager. It is used for installing, updating, and uninstalling packages in your application. It helps to manage dependencies in Node.js applications.

### 17. For What Type of Applications Is Node.js Not Compatible?
   - Node.js is not compatible with CPU-intensive applications.

### 18. What Is Node Red?
   - Node red is a visual programming tool for Node.js that is used to wire hardware devices and online services as part of IoT applications.

### 19. How Is Operational Error Different from Programming Error?
   - An operational error occurs naturally and is part of the application flow, while programming errors are referred to as bugs that are caused by developers.

### 20. What Is Unit Testing?
   - Unit testing in Node.js is a process of testing individual units of code.

### 21. What Is Blocking Code?
   - Blocking code is code that cannot be executed until the current code is completely executed.

### 22. Are There Any Disadvantages of Node.js?
   - No technology comes without a few disadvantages. Node.js also has a few drawbacks. The main drawback is that Node.js responses can be greatly blocked if an intensive CPU computation is used.

### 23. Give Some Examples of Async Functions.
   - Some examples of async functions are setTimeout(), setInterval(), and process.nextTick()

### 24. Which Library Provides Node.js with a JavaScript Engine?
   - The V8 library provides Node.js with the JavaScript engine.

### 25. How Is JavaScript Different from Node.js?
   - JavaScript is a programming language, whereas Node.js is an interpretation and environment for JavaScript. Node.js is used for performing non-blocking operations of any operating system. On the other hand, JavaScript is used for comprehensive application development.

### 26. What Are Some Features of Node.js?
   - It is fast, scalable, open-source, and asynchronous.

### 27. Can You Develop Network Applications with Node.js?
   - Yes, Node.js developers can develop a variety of applications, including network applications.

### 28. What Tasks Can Be Done Asynchronously with the Help of an Event Loop?
   - The tasks include - intensive CPU computation, I/O operations, GUI programming, and database operations can be done asynchronously with the help of an event loop.

### 29. What Are Security Implementations within Node.js?
   - The different types of security implementations within Node.js include error handling, authentications and authorization, data sanitization, encryption, and logging and monitoring.

### 30. What Is Package.json?
   - Present in the root directory of a Node application/module, package.json defines the properties of a package including dependencies, metadata, and configuration options.

### 31. Is Node.js Single or Multi-Threaded?
   - Node.js is single-threaded.

### 32. What Are the Clauses Used in Promise Object in Node.js?
   - In JavaScript, a Promise object can have three states:
     - Pending: The initial state of the promise before it is resolved or rejected.
     - Fulfilled: The state of a promise representing a successful operation. This is also sometimes called "resolved."
     - Rejected: The state of a promise representing a failed operation. To create a Promise object, you must pass a function (often called an executor function) to the Promise constructor. This function takes two arguments: resolve and reject. These are functions that you call to either fulfill or reject the promise.

### 33. Name Some Important Applications in IT Where Node.js Can Be Used.
   - One of the main applications where Node.js can be used is building real-time web applications. Apart from this, distributed systems for sub-programming collections can also use Node.js. It can be used in general applications as well as complex network applications. One can also use Node.js to create, read, write, or close server files.

### 34. Is AJAX Supported by All Browsers?
   - Yes, all browsers support AJAX.

### 35. How to Obtain the IP Address of the User in Node.js?
   - We use `req.connection.remote address` to get the IP address.

### 36. How to Install the Node Body-Parser Module?
   - To install the body-parser module for Node.js, follow these steps:
     1. Open a command prompt or terminal window.
     2. Navigate to the directory where your Node.js project is located.
     3. Run the command `npm install body-parser` to install the body-parser module and add it to your project's dependencies.

## Intermediate Level

### 1. Explain the Function of Exit Code in Node.js
   - Exit codes are a collection of specific codes whose function is to complete a specific process. Examples of exit codes are fatal error, unused, internal JavaScript evaluation failure, etc.

### 2. What Causes Server Latency and Prevents Scalability in Node.js?
   - Several factors can cause server latency and prevent scalability in Node.js. Some of the most common ones include:
     - Blocking I/O: Blocking I/O operations can cause the server to become unresponsive while waiting for I/O operations to complete. This can be especially problematic in Node.js, which is designed to handle many concurrent connections. To avoid this, Node.js provides non-blocking I/O operations.
     - Inefficient Code: Inefficient code can cause unnecessary processing and slow down the server. This can be caused by poor algorithmic choices, excessive use of synchronous operations, or inefficient data structures.
     - Insufficient Hardware Resources: Insufficient hardware resources, such as CPU, memory, or network bandwidth, can cause the server to become overloaded and unresponsive. This can be especially problematic in high traffic scenarios.
     - Improper Configuration: Improperly configured servers can cause performance issues. This can be caused by incorrect network settings, improper load balancing, or other misconfigurations.

### 3. How Does Node.js Convert JavaScript Code to C++?
   - Node.js uses the Google V8 JavaScript engine to convert JS code to C++.

### 4. Define Event Programming
   - Event programming is a programming paradigm that uses events to trigger actions. An event can be generated by the user, by the system, or by the program itself.

### 5. How Is Ajax Different from Node.js?
   - Ajax is a client-side technology used to make web pages more interactive and dynamic, while Node.js is a server-side technology used to build scalable, high-performance web applications.

### 6. Explain Non-Blocking in Node.js
   - Non-blocking in Node.js means that the program can continue to execute other code even while waiting for I/O operations to complete.

### 7. In Which Packages Are Dependencies Stored in Node.js?
   - Dependencies are present in the package.json file.

### 8. Define Control Function in Node.js
   - A control function manages and manipulates the flow of asynchronous code execution. Node.js is designed to handle asynchronous I/O operations, which means that multiple I/O operations can be executed simultaneously without blocking the execution of other code. However, managing the flow of asynchronous code can be challenging, especially when multiple operations need to be executed in a particular order. Control functions provide a solution to this problem by allowing developers to define the order in which asynchronous operations should be executed. They can be used to perform tasks such as error handling, callback management, and flow control.

### 9. When Do You Use Modularization in Node.js?
   - Modularization in Node.js provides scalability when developing complex applications. The modularization option can be used to execute the import of objects, classes, functions, modules, and external files.

### 10. What Is the Callback Function Used For?
   - The callback function is used to execute a function after a certain event has occurred.

### 11. Explain How Blocking Is Prevented in Node.js
   - Because of the event mechanism in Node.js, a callback function is called every time an event starts. This prevents blocking in Node.js.

### 12. How Many Layers Are There in Node.js Application Architecture?
   - There are three layers in the application architecture - API, service, and integration layers.

### 13. Name Input Arguments for Asynchronous Queue
   - Two input arguments for an asynchronous queue are concurrency value and task function.

### 14. Does Node.js Applications Buffer Data?
   - No, Node.js applications do not buffer data.

### 15. What Is a Boolean Data Type in Node.js?
   - The Boolean data type in Node.js can have one of two values: true or false.

### 16. Is It Possible to Run External Processes with Node.js?
   - It is possible to run external processes with Node.js. This can be done with the help of the child_process module.

### 17. Is It Possible to Avoid Callback Hells and How?
   - It is possible to avoid callback hells by using promises; they can help make the code more readable and easier to debug. You can also avoid callback hells using async/wait, libraries, and modularization.

### 18. What Is the Function of the fs Module?
   - The fs module is used to create and manipulate files. It also provides an API for interacting with the file system.

### 19. Define os Module in Node.js?
   - The os module provides a set of tools for interacting with the operating system. It provides an API for getting information about the system, including memory, processor, file system, and network interfaces.

### 20.
**Are duplex streams readable and writable?**
   - Duplex streams are both readable and writable. This means that they can be used to read data from a source and write data to a destination.

### 21.
**What is a transform stream?**
   - A transform stream is a type of stream that can be used to modify or transform the data as it is being read or written.

### 22.
**In Node.js, how many Node object methods are available?**
   - There are a total of 18 Node object methods available. These methods can be used to create, manipulate, and delete objects.

### 23.
**What is the meaning of HTTP status code 504?**
   - HTTP status code 504 indicates that the server is unable to process the request. This can be due to several reasons, such as an overloaded server or a network issue.

### 24.
**Explain routing in the express.**
   - Routing is a process where you associate HTTP request to a URL path or specific routes. When a request matches one of these routes, a corresponding handling function is used. Routing is a robust mechanism that enables you to define how an application handles incoming requests.

### 25.
**How to open a file in Node.js?**
   - A file can be opened in Node.js using the `fs.open()` method. This method takes two arguments, the path of the file and the flags.

### 26.
**What is the difference between Angular and Node.js?**
   - Angular is a front-end web application framework. Node.js is a back-end runtime environment.

### 27.
**How does Node.js handle concurrency if it is single-threaded?**
   - Node.js prevents bottlenecks and aids programmers in easily writing the code because of the single-thread model. Internally, there are several POSIX threads for different I/O operations like File, DNS, etc.

### 28.
**What is the shortcut for killing a process in Node.js?**
   - `Ctrl + C` shortcut is used for terminating processes in Node.js.

### 29.
**What is a Node Inspector?**
   - A Node Inspector is a debugging tool that allows developers to inspect and debug the code of an application through a graphical user interface.

### 30.
**Is dgram an in-built module?**
   - Yes, the Dgram is an in-built module. It is useful in implementing UDP datagram packets.

### 31.
**Can we import a buffer class without buffer modules?**
   - You can import the buffer class without the buffer module.

### 32.
**Which function is used to fire an event?**
   - The `emit()` function is used to fire an event.

### 33.
**Explain callback.**
   - In Node.js, a callback function is a function that is passed as an argument to another function and is called back at a later point in time. The purpose of using a callback function is to handle asynchronous operations.

### 34.
**Can middleware function execute code?**
   - Yes, middleware functions can execute code, and they can modify the request or response objects.

### 35.
**How many types of streams are there in Node.js?**
   - There are four types of streams in Node.js: readable, writable, duplex, and transform.

   - Readable: The readable streams are used to read data from a specific source.
   - Writable: These streams are utilized for writing data to the destination.
   - Duplex: The duplex streams are used for both reading and writing data.
   - Transform: The transform stream enables the data to be transformed while it is being read or written. For example, you can use a transform stream for data compression or data encryption as it is transmitted over the network.

### 36.
**What is the difference between setImmediate() and setTimeout()?**
   - The difference between `setImmediate()` and `setTimeout()` is that `setImmediate()` will execute the callback function immediately, while `setTimeout()` will wait for a specified time before executing the callback function.

### 37.
**What two arguments do async.queue take?**
   - Task function and concurrency value are the two arguments `async.queue` takes.

### 38.
**What is the Null data type in Node.js?**
   - It is a special data type that only takes one value, i.e., `null`.

### 39.
**What is the difference between an event and a callback?**
   - The difference between an event and a callback is that an event is a mechanism that signals a change or action that represents a part of the program's behavior, while a callback is a function that takes data and sends it back to the calling function.

### 40.
**How will you delete a directory?**
   - To delete a directory, we use `fs.rmdir()` method.

### 41.
**Is the value of the symbol data type kept private?**
   - Yes, it is private and used internally.

### 42.
**What is an error-first callback?**
   - Error-first callbacks are used to pass data and identify if an error has occurred.

### 43.
**What are global objects?**
   - Global objects are universal objects that are present in every module or file of the application without requiring explicit import statements.

### 44.
**When does the child process occur?**
   - In Node.js, a child process occurs when a new process is created using the `child_process` module. This module provides functionality to spawn child processes in a similar way to the `fork()` system call in Unix.

### 45.
**Can variables defined with the let keyword be redeclared?**
   - No, the `let` keyword can’t be redeclared and should be declared before use.


