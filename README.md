# Node Js Introduction

<h2>1. What is Node JS</h2>
<p>Node.js is a platform built on Chrome's JavaScript runtime for easily building fast and scalable network applications. Node.js uses an event-driven, non-blocking I/O model that makes it lightweight and efficient, perfect for data-intensive real-time applications that run across distributed devices.</p>

<h2>1. What are features of Node js?</h2>
<ul>
        <li>
            <b>Asynchronous and Event Driven : </b> All APIs of Node.js library are asynchronous, that is, non-blocking. It essentially means a Node.js based server never waits for an API to return data. The server moves to the next API after calling it and a notification mechanism of Events of Node.js helps the server to get a response from the previous API call.
        </li>
        <li>
            <b>Very Fast : </b> Being built on Google Chrome's V8 JavaScript Engine, Node.js library is very fast in code execution.
        </li>
        <li>
            <b>Single Threaded but Highly Scalable : </b> Node.js uses a single threaded model with event looping. Event mechanism helps the server to respond in a non-blocking way and makes the server highly scalable as opposed to traditional servers which create limited threads to handle requests. Node.js uses a single threaded program and the same program can provide service to a much larger number of requests than traditional servers like Apache HTTP Server.
        </li>
        <li>
            <b>No Buffering : </b> Node.js applications never buffer any data. These applications simply output the data in chunks.
        </li>
    </ul>
    <h2>3. What is Routing in nodeJS?</h2>
    <p>Routing refers to how an application's endpoints (URIs) respond to client requests. For an introduction to routing, see Basic routing. We define routing using methods of the Express app object that correspond to HTTP methods; for example, app.get() to handle GET requests and app.post to handle POST requests. there are five different types of middleware: 3rd Party, Router, Application, Error-handling, and Built-in. Scott explains a few of these types and shares a few code examples of their use.</p>
    <h2>4. What is middleware?</h2>
    <p>The middleware in node. js is a function that will have all the access for requesting an object, responding to an object, and moving to the next middleware function in the application request-response cycle. there are five different types of middleware: 3rd Party, Router, Application, Error-handling, and Built-in. Scott explains a few of these types and shares a few code examples of their use.</p>
    <h2>5. What is Express is used for?</h2>
    <p>Express JS is a Node.js framework designed to build API's web applications cross-platform mobile apps quickly and make node js easy. It's a layer built on the top of the Node js that helps manage servers and routes. Express was created to make APIs and web applications with ease, It saves a lot of coding time almost by half and still makes web and mobile applications are efficient. Another reason for using express is that it is written in javascript as javascript is an easy language even if you don't have a previous knowledge of any language. Express lets so many new developers enter the field of web development. Express provides methods to specify what function is called for a particular HTTP verb ( GET , POST , SET , etc.) and URL pattern ("Route"), and methods to specify what template ("view") engine is used, where template files are located, and what template to use to render a response.</p>
    <h2>6. what is module in node js?</h2>
    <p>Module in Node. js is a simple or complex functionality organized in single or multiple JavaScript files which can be reused throughout the Node. js application. Each module in Node. js has its own context, so it cannot interfere with other modules or pollute global scope. The module system is built around the require function. This function is used to load a module and get access to its contents. require is a global variable provided to all your Node. js scripts, so you can use it anywhere you like.</p>

