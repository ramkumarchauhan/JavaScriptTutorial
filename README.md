<h1>Javascript Tutorial</h1>

<h3>Day_01. Basics</h3>
<ul>
    <li>- <code>console.log()</code> --> Output in console</li>
    <li>- Variable declaration - <code>let</code>, <code>var</code>, <code>const</code></li>
    <li>- Data Types - numbers, strings, booleans, null, undefined</li>
    <li>- Conditionals - <code>if</code>, <code>if-else</code>, multi-conditional <code>if-else</code></li>
    <li>- Loops - <code>while</code>, <code>do-while</code>, <code>for</code> loops --> Loops continue executing block of code until a termination condition meets.</li>
    <li>- Iterators - <code>for...of</code>, <code>for...in</code> --> Iterators on each available element of array or object</li>
</ul>

<h3>Day_02. String Methods</h3>
<ul>
    <li>- <code>concat()</code> -> joins two strings.</li>
    <li>- <code>charAt(index)</code> -> returns the index number of mentioned character</li>
    <li>- <code>toUpperCase()</code> -> Change all letters to Capital case.</li>
    <li>- <code>toLowerCase()</code> -> Change all letters to Small case.</li>
    <li>- <code>trim()</code> -> Removes whitespace from both ends of a string.</li>
    <li>- <code>split(",")</code> -> Splits a string into an array of substrings based on the specified separator.</li>
    <li>- <code>replace(oldValue, newValue)</code> & <code>replaceAll(oldValue, newValue)</code> -> Returns a new string replacing old value with new one.</li>
    <li>- <code>includes(searchWord)</code> -> Determines whether one string may be found within another string</li>
    <li>- <code>startsWith(searchWord)</code> -> Checks if a string starts with the specified string.</li>
    <li>- <code>endsWith(searchWord)</code> -> Checks if a string ends with the specified string.</li>
    <li>- <code>slice(startIndex, endIndex)</code> -> Extracts a section of a string and returns it as a new string.</li>
</ul>

<h3>Day_03. Array & Array Methods</h3>
<ul>
    <li>- <code>push()</code> -> Adds one or more elements to the end of an array and returns the new length of the array.</li>
    <li>- <code>pop()</code> -> Removes the last element from an array and returns that element.</li>
    <li>- <code>unshift()</code> -> Inserts the given values to the beginning of an array-like object.</li>
    <li>- <code>shift()</code> -> Removes the first element from an array.</li>
    <li>- <code>concat()</code> -> Returns a new array that combines the elements of the original array with other arrays or values.</li>
    <li>- <code>reverse()</code> -> Reverses an array in place and returns the reference to the same array.</li>
    <li>- <code>sort()</code> -> Sorts the elements as strings by default and returns the reference to the same array.</li>
    <li>- <code>toString()</code> -> Returns a string representing the object.</li>
    <li>- <code>slice()</code> -> <code>array.splice(start, number of elements in the array to remove from start, elements to add to the array beginning from the start index,item2,...)</code></li>
    <li>- <code>splice()</code> -> Changes the contents of an array by removing or replacing existing elements and/or adding new elements in place.</li>
    <li>- <code>join()</code> -> Joins the array’s items into a string and returns that string.</li>
    <li>- <code>forEach()</code> -> Executes a callback function once for each array element.</li>
    <li>- <code>map()</code> -> Creates a new array with the results of calling a provided function on every element in the calling array.</li>
    <li>- <code>filter()</code> -> Creates a new array with all elements that pass the test implemented by the provided function.</li>
</ul>

<h3>Day_04. Objects-</h3>
<ol>
    <li>Object Declaration using-</li>
    <ul>
        <li>- Object Literal</li>
        <li>- Constructor Function</li>
    </ul>
    <li>Accessing object's properties</li>
    <li>'this' keyword</li>
</ol>

<h3>Day_05. ES6 features-</h3>
<ul>
    <li>- Arrow function</li>
    <li>- Rest Parameter ->Used to collect multiple arguments into a single array parameter. It allows functions to accept an indefinite number of arguments, primarily used in function declarations.</li>
    <li>- Spread Syntax -> Used for Destructuring. It can expand iterable objects into multiple elements.</li>
    <li>- Template literals or String interpolation -> Allows for easier string interpolation and multiline strings using backticks (`) and ${}.</li>
    <li>- Destructuring Assignment -> Destructuring allows for extracting values from arrays or properties from objects into distinct variables.</li>
</ul>

<h3>Day_06. Asynchronous JavaScript</h3>
<ol>
    <li><code>setTimeout() & setInterval()</code> - These are built-in functions for scheduling asynchronous execution of code after a specified delay or at regular intervals.</li>
    <li><code>fetch()</code> - A modern interface (alternative to XMLHttpRequest) for fetching resources (such as JSON, HTML, or images) across the network.</li>
    <li><code>XMLHttpRequest()</code> - XMLHttpRequest is an older API used for making HTTP requests from the browser.</li>
    <li><strong>async/await</strong> - It provides syntactic sugar over Promises, making asynchronous code look and behave more like synchronous code.</li>
    <li><code>Promise()</code> - Promises provide a way to handle asynchronous operations more cleanly and avoid callback hell. Promises represent a value that may be available now, in the future, or never.</li>
</ol>

<h3>Day_07. DOM Manipulation - Part - 1</h3>

### 1. Accessing DOM Elements:
<ul>
  <li><code>getElementById():</code> Retrieves an element by its ID attribute.</li>
  <li><code>getElementsByClassName():</code> Retrieves elements by their class name, returns a collection, not a single element.</li>
  <li><code>getElementsByTagName():</code> Retrieves elements by their tag name, returns a collection, not a single element.</li>
</ul>

### 2. Creating and Modifying Elements:
<ul>
  <li><code>createElement():</code> Creates a new element node.</li>
  <li><code>createTextNode():</code> Creates a new text node.</li>
  <li><code>appendChild():</code> Appends a child node to an element.</li>
  <li><code>removeChild():</code> Removes a child node from an element.</li>
</ul>

### 3. Document Structure Manipulation:
<ul>
  <li><code>document.createElement():</code> Creates a new element.</li>
  <li><code>element.appendChild():</code> Adds a new child node to an element.</li>
  <li><code>element.removeChild():</code> Removes a child node from an element.</li>
  <li><code>element.insertBefore():</code> Inserts a new node before an existing node.</li>
</ul>

<h3>Day_08. DOM Manipulation - Part - 2</h3>

### 1. Modifying Element Content:
<ul>
  <li><code>innerHTML</code>-> Sets or gets the HTML content of an element.</li>
  <li><code>textContent</code>-> Sets or gets the text content of an element.</li>
  <li><code>innerText</code>-> Similar to textContent, but it does not return the text content of hidden elements.</li>
</ul>

### 2. Styling Elements:
<ul>
  <li><code>style.property</code>-> Allows direct manipulation of CSS styles.</li>
  <li><code>classList</code>-> Allows adding, removing, toggling, and checking classes on an element.</li>
</ul>

<h3>Day_09. DOM Manipulation - Part - 3</h3>

<strong>Event Handling:</strong>
<ul>
    <li><strong>Mouse Events:</strong>
    <ul>
        <li><code>onclick</code>-> Fired when a pointing device button (such as a mouse's primary button) is pressed and released on an element.</li>
        <li><code>ondblclick</code>-> Fired when a pointing device button (such as a mouse's primary button) is clicked twice on an element.</li>
        <li><code>onmouseenter</code>-> Fired when the pointer enters the boundaries of an element.</li>
        <li><code>onmouseleave</code>-> Fired when the pointer leaves the boundaries of an element.</li>
        <li><code>onmouseover</code>-> Fired when the pointer enters the boundaries of an element or one of its descendants.</li>
        <li><code>onmouseout</code>-> Fired when the pointer leaves the boundaries of an element or one of its descendants.</li>
        <li><code>onmousedown</code>-> Fired when a pointing device button is pressed down on an element.</li>
        <li><code>onmouseup</code>-> Fired when a pointing device button is released over an element.</li>
        <li><code>onmousemove</code>-> Fired when the pointer is moved while it is over an element.</li>
        <li><code>oncontextmenu</code>-> Fired when the right mouse button is clicked on an element, triggering the browser's context menu.</li>
    </ul>
    </li>
    <li><strong>Keyboard Events:</strong>
    <ul>
        <li><code>oninput</code>-> Fired when the value of an &lt;input&gt;, &lt;select&gt;, or &lt;textarea&gt; element is changed by the user.</li>
        <li><code>onchange</code>-> Fired when the value of an &lt;input&gt;, &lt;select&gt;, or &lt;textarea&gt; element is changed and then loses focus.</li>
        <li><code>onfocus</code>-> Fired when an element gains focus.</li>
        <li><code>onblur</code>-> Fired when an element loses focus.</li>
        <li><code>onkeydown</code>-> Fired when a key is pressed down.</li>
        <li><code>onkeyup</code>-> Fired when a key is released.</li>
        <li><code>onkeypress</code>-> Fired when a key that produces a character value is pressed down. (Note: Deprecated in favor of <code>keydown</code> and <code>keyup</code> for most use cases.)</li>
    </ul>
    </li>
</ul>

<h3>Day_10. DOM Manipulation - Part - 4 </h3>

<strong>Event Handlers:</strong>
<ul>
    <li><code>addEventListener(event, function)</code>-> Attaches an event handler to an element. 'on' is not included when events are attached by using <code>addEventListener()</code>.</li>
    <li><code>removeEventListener(event, function)</code>-> Removes an event handler from an element.</li>
</ul>

<h3>Day_11. Navigator Object </h3>
<p>The "navigator" object in JavaScript represents the "browser environment" and provides information about the browser.</p>
<ul>
    <li><code>navigator.userAgent</code>: Returns the user-agent string for the current browser.</li>
    <li><code>navigator.language</code>: Returns the preferred language of the user's browser.</li>
    <li><code>navigator.cookieEnabled</code>: Indicates whether cookies are enabled in the browser.</li>
    <li><code>navigator.onLine</code>: Indicates whether the browser is online or offline.</li>
    <li><code>navigator.platform</code>: Returns the platform on which the browser is running (e.g., "Win32", "MacIntel", "Linux x86_64").</li>
    <li><code>navigator.geolocation</code>: Provides access to the Geolocation API for obtaining the user's geographic location.</li>
</ul>

<h3>Day_12. Project - 1 Weather App </h3>
<p>It fetches data from an api, returns the weather data for the current location and lists following information-</p>
<ul>
    <li>Temperature in celsius</li>
    <li>Humidity in %</li>
    <li>Wind speed in m/s</li>
    <li>Weather Description</li>
</ul>

<h3>Day_13. Project - 2 Calculator App </h3>
<p>It performs calculation and returns result as intended lists following components-</p>
<ul>
    <li>0-9 buttons</li>
    <li>operators -> +, -, * and /</li>
    <li>clear button to clear given expression</li>
    <li>= button to perdorm calculation on expression.</li>
</ul>

<h3>Day_13. Project - 3 TODO App </h3>
<p>It takes tasks from inputbox and adds into the list when clicked on 'ADD' and removes when clicked on 'REMOVE' button, lists following components-</p>
<ul>
    <li>Input Box</li>
    <li>Add and Remove task buttons</li>
    <li>Task list to show added tasks</li>
</ul>