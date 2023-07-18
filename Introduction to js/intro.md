## JAVASCRIPT??

`JavaScript` is a high-level, interpreted programming language used for creating interactive and dynamic web applications. It allows developers to add interactivity to websites by manipulating web page content, handling user interactions, and communicating with servers. JavaScript is a `weakly typed language` (dynamically typed).JavaScript can be used for `Client-side developments` as well as `Server-side developments`.

- `JavaScript is a synchronus single-threaded language.`

- `synchronus single-threaded` means JavaScript can execute one command at a time in a specific order.

- JavaScript, created by `Brendan Eich` in `1995`, is one of the most widely used web development languages.

## JavaScript is Used for

### 1. Enhancing User Interfaces:

- Creating interactive elements like dropdown menus and sliders.
- Validating and processing user input in real-time.

### 2. Manipulating HTML and CSS:

- Modifying web page content dynamically.
- Updating styles and layout on the fly.

### 3. Handling User Events:

- Responding to user actions like clicks and keystrokes.
- Creating interactive and responsive web experiences.

### 4. Asynchronous Data Retrieval:

- Making requests to servers without page reload (AJAX).
- Updating content dynamically with retrieved data.

### 5. Client-Side Storage:

- Storing and retrieving data on the client's browser.
- Using cookies, local storage, or IndexedDB.

### 6. Web Browser APIs:

- Accessing browser features like geolocation and multimedia.
- Leveraging APIs for graphics, audio, video, and more.

### 7. Third-Party Libraries and Frameworks:

- Utilizing pre-built tools for efficient development.
- Examples include React, Angular, and Vue.js.

### 8. Server-Side Development:

- Building web servers and APIs using JavaScript (Node.js).
- Handling server-side tasks and processing data.

### 9. Mobile App Development:

- Creating mobile apps with frameworks like React Native.
- Sharing code across iOS and Android platforms.

## Advantages of JavaScript

- `Less server interaction` − You can validate user input before sending the page off to the server. This saves server traffic, which means less load on your server.
- `Immediate feedback to the visitors` − They don't have to wait for a page reload to see if they have forgotten to enter something.
- `Increased interactivity` − You can create interfaces that react when the user hovers over them with a mouse or activates them via the keyboard.
- `Richer interfaces` − You can use JavaScript to include such items as drag-and-drop components and sliders to give a Rich Interface to your site visitors.

## Limitations of JavaScript

- `Security risks`: JavaScript can be used to fetch data using AJAX or by manipulating tags that load data such as `<img>, <object>, <script>`.
- These attacks are called cross-site script attacks. They inject JS that is not part of the site into the visitor’s browser thus fetching the details.
- `Performance` : JavaScript does not provide the same level of performance as offered by many traditional languages as a complex program written in JavaScript would be comparatively slow. But as JavaScript is used to perform simple tasks in a browser, so performance is not considered a big restriction in its use.
- `Complexity` : To master a scripting language, programmers must have a thorough knowledge of all the programming concepts, core language objects, and client and server-side objects otherwise it would be difficult for them to write advanced scripts using JavaScript.
- `Weak error handling and type checking facilities` : It is a weakly typed language as there is no need to specify the data type of the variable. So wrong type checking is not performed by compile.
- `Richer interfaces` : You can use JavaScript to include such items as drag-and-drop components and sliders to give a Rich Interface to your site visitors.

## JavaScript: Client side Vs Server side

## 1. Client-side development:

Client-side development refers to using JavaScript to write code that runs directly in the user's web browser. It focuses on enhancing the user interface and providing interactive functionality on the client side.

### Example:

Imagine a website that displays a slideshow of images. Using JavaScript on the client side, you can create a script that automatically transitions between the images, providing a visually engaging and dynamic experience for the user. The JavaScript code runs in the user's browser and controls the behavior of the slideshow, such as changing the images and applying transitions.

## 2. Server-side development:

Server-side development involves using JavaScript to write code that runs on the server, handling requests from clients and performing tasks like processing data and generating dynamic web pages.

### Example:

Consider an online shopping website where users can add products to their shopping cart. When a user clicks the "Add to Cart" button, the JavaScript code on the client side sends a request to the server. On the server side, JavaScript code can handle this request, update the user's shopping cart in the server's database, and send a response back to the client indicating a successful addition to the cart. The server-side JavaScript code takes care of processing the data and performing the necessary actions on the server.

## JavaScript can be added to your HTML file in three ways

- Inline JavaScript
- Internal JavaScript
- External JavaScript

1. Inline JavaScript:
   Inline JavaScript involves embedding JavaScript code directly within the HTML markup of a web page. It is placed within the `<script>` tags in the HTML document.

Example:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Inline JavaScript Example</title>
  </head>
  <body>
    <h1>Hello, world!</h1>
    <script>
      alert("This is an inline JavaScript example.");
    </script>
  </body>
</html>
```

2. Internal JavaScript:
   Internal JavaScript refers to including JavaScript code within the `<script>` tags in the `<head>` or `<body>` section of an HTML document. The code is written directly within the HTML file.

Example:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Internal JavaScript Example</title>
    <script>
      function sayHello() {
        alert("Hello, Jayanth!");
      }
    </script>
  </head>
  <body>
    <h1>Internal JavaScript Example</h1>
    <button onclick="sayHello()">Click me!</button>
  </body>
</html>
```

3. External JavaScript:
   External JavaScript involves placing the JavaScript code in a separate external file with a `.js` extension and then including that file in the HTML document using the `<script>` tag's `src` attribute.

Example:

index.html:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>External JavaScript Example</title>
    <script src="script.js"></script>
  </head>
  <body>
    <h1>External JavaScript Example</h1>
    <button onclick="sayHello()">Click me!</button>
  </body>
</html>
```

script.js:

```javascript
function sayHello() {
  alert("Hello, Jayanth!");
}
```

In the external JavaScript example, the JavaScript code is placed in a separate file called "script.js" and linked to the HTML file using the `src` attribute in the `<script>` tag.
