# JS-Documents-Technical-Documentation-Page-
(New) Responsive Web Design (freeCodeCamp)
<nav id="navbar">
<header>JS Documentation</header>
<ul>
  <li><a class="nav-link" href="#js_home">JS Home</a></li>
  <li><a class="nav-link" href="#js_overview">JS Overview</a></li>
  <li><a class="nav-link" href="#js_functions">JS Functions</a></li>
  <li><a class="nav-link" href="#js_placement">JS Placement</a></li>
  <li><a class="nav-link" href="#js_variables">JS Variables</a></li>
  <li><a class="nav-link"  href="#declaring_variables">Declaring Variables</a></li>
</ul>
</nav>
<main id="main-doc">
  <section class="main-section" id="js_home">
    <header>JS Home</header>
    <p>JavaScript is a lightweight, interpreted programming language. It is designed for creating network-centric applications. It is complimentary to and integrated with Java. JavaScript is very easy to implement because it is integrated with HTML. It is open and cross-platform.</p>
    <p>Javascript is a MUST for students and working professionals to become a great Software Engineer specially when they are working in Web Development Domain. I will list down some of the key advantages of learning Javascript</p>
    <ul>
      <li>JavaScript usage has now extended to mobile app development, desktop app development, and game development. This opens many opportunities for you as Javascript Programmer.</li>
      <li>Due to high demand, there is tons of job growth and high pay for those who know JavaScript. You can navigate over to different job sites to see what having JavaScript skills looks like in the job market.</li>
    </ul>
      </section>
    <section class="main-section" id="js_overview">
      <header>JS Overview</header>
      <p>Advantages of JavaScript</p>
      <ul>
        <li>Less server interaction − You can validate user input before sending the page off to the server. </li>
        <li>Immediate feedback to the visitors − They don't have to wait for a page reload to see if they have forgotten to enter something.</li>
        <li>Increased interactivity − You can create interfaces that react when the user hovers over them with a mouse or activates them via the keyboard.</li>
      </ul>
    </section>
    <section class="main-section" id="js_functions">
      <header>JS Functions</header>
      <p>A function is a group of reusable code which can be called anywhere in your program. This eliminates the need of writing the same code again and again. It helps programmers in writing modular codes. Functions allow a programmer to divide a big program into a number of small and manageable functions.</p>
      <p>Like any other advanced programming language, JavaScript also supports all the features necessary to write modular code using functions. You must have seen functions like alert() and write() in the earlier chapters. We were using these functions again and again, but they had been written in core JavaScript only once.</p>
      <p>JavaScript allows us to write our own functions as well. This section explains how to write your own functions in JavaScript.</p>
      </section>
    <section class="main-section" id="js_placement">
      <header>JS Placement</header>
      <p>To use JavaScript from an external file source, you need to write all your JavaScript source code in a simple text file with the extension ".js" and then include that file as shown above.</p>
      <code>function sayHello() {
   alert("Hello World")
}
</code>
      <p> you can keep the following content in filename.js file and then you can use sayHello function in your HTML file after including the filename.js file.</p>
    </section>
    <section class="main-section" id="js_variables">
      <header>JS Variables</header>
      <p>One of the most fundamental characteristics of a programming language is the set of data types it supports.</p>
      <p>These are the type of values that can be represented and manipulated in a programming language.</p>
      <p>JavaScript allows you to work with three primitive data types</p>
    </section>
  <section class="main-section" id="declaring_variables">
      <header>Declaring Variables</header>
      <p>Declaring (Creating) Variables</p>
    <p>To create a variable, you must specify the type and assign it a value:</p>
    <code>type variableName = value;</code>
  <p>Declare Many Variables</p>
  <p>To declare more than one variable of the same type, you can use a comma-separated list:</p>
  <code>int x = 5, y = 6, z = 50;
System.out.println(x + y + z);</code>
  <p>One Value to Multiple Variables</p>
  <p>You can also assign the same value to multiple variables in one line:</p>
  <code>int x, y, z;
x = y = z = 50;
System.out.println(x + y + z);</code>
  <code>let y = 13.</code>
  <code>let x = 13.</code>
  <p> This syntax can be used to declare a block scope local variable. See Variable scope below. </p>
  </section>
  <link rel="stylesheet" href="styles.css">
    </main>

#navbar {
  width: 45;
}

@media (max-width: 768px) {
  body{
    background-color:
    violet;
  }
}
