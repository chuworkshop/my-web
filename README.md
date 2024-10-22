<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Learning Hub</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f4f4f4;
            line-height: 1.6;
        }
        header {
            background: #333;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        header h1 {
            font-size: 2.5em;
            margin-bottom: 10px;
        }
        header p {
            font-size: 1.2em;
        }
        nav {
            background: #444;
            padding: 15px;
            text-align: center;
        }
        nav a {
            color: white;
            padding: 10px 20px;
            margin: 5px;
            text-decoration: none;
            background-color: #4CAF50;
            border-radius: 5px;
        }
        nav a:hover {
            background-color: #45a049;
        }
        section {
            margin: 20px;
            padding: 20px;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0px 0px 10px rgba(0,0,0,0.1);
        }
        section h2 {
            color: #333;
            font-size: 2em;
            margin-bottom: 10px;
        }
        ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
        }
        ul li {
            margin-bottom: 10px;
            font-size: 1.1em;
        }
        ul li a {
            text-decoration: none;
            color: #4CAF50;
        }
        ul li a:hover {
            color: #333;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        footer p {
            margin: 0;
        }
    </style>
</head>
<body>

    <header>
        <h1>Welcome to My Learning Hub</h1>
        <p>Your personal portal to learn web development and programming languages</p>
    </header>

    <nav>
        <a href="#html-section">HTML & CSS</a>
        <a href="#js-section">JavaScript</a>
        <a href="#programming-section">Programming Languages</a>
        <a href="#tools-section">Essential Tools</a>
        <a href="#freelancing-section">Freelancing Tips</a>
    </nav>

    <section id="html-section">
        <h2>Learn HTML & CSS</h2>
        <ul>
            <li><a href="https://www.w3schools.com/html/" target="_blank">W3Schools HTML Tutorial</a></li>
            <li><a href="https://www.freecodecamp.org/learn/responsive-web-design/#basic-html-and-html5" target="_blank">FreeCodeCamp: HTML & CSS Course</a></li>
            <li><a href="https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics" target="_blank">MDN Web Docs: HTML Basics</a></li>
        </ul>
    </section>

    <section id="js-section">
        <h2>Learn JavaScript</h2>
        <ul>
            <li><a href="https://www.w3schools.com/js/" target="_blank">W3Schools JavaScript Tutorial</a></li>
            <li><a href="https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/" target="_blank">FreeCodeCamp: JavaScript Algorithms</a></li>
            <li><a href="https://developer.mozilla.org/en-US/docs/Learn/JavaScript" target="_blank">MDN Web Docs: JavaScript Guide</a></li>
        </ul>
    </section>

    <section id="programming-section">
        <h2>Learn Programming Languages</h2>
        <h3>C++</h3>
        <ul>
            <li><a href="https://www.w3schools.com/cpp/" target="_blank">W3Schools C++ Tutorial</a></li>
            <li><a href="https://www.learncpp.com/" target="_blank">LearnCpp.com: C++ Programming</a></li>
            <li><a href="https://www.codecademy.com/learn/learn-c-plus-plus" target="_blank">Codecademy: Learn C++</a></li>
        </ul>

        <h3>Python</h3>
        <ul>
            <li><a href="https://www.w3schools.com/python/" target="_blank">W3Schools Python Tutorial</a></li>
            <li><a href="https://www.learnpython.org/" target="_blank">LearnPython.org</a></li>
            <li><a href="https://www.codecademy.com/learn/learn-python-3" target="_blank">Codecademy: Learn Python</a></li>
        </ul>

        <h3>Java</h3>
        <ul>
            <li><a href="https://www.w3schools.com/java/" target="_blank">W3Schools Java Tutorial</a></li>
            <li><a href="https://www.codecademy.com/learn/learn-java" target="_blank">Codecademy: Learn Java</a></li>
            <li><a href="https://www.javatpoint.com/java-tutorial" target="_blank">JavaTPoint: Java Tutorial</a></li>
        </ul>

        <h3>SQL</h3>
        <ul>
            <li><a href="https://www.w3schools.com/sql/" target="_blank">W3Schools SQL Tutorial</a></li>
            <li><a href="https://www.codecademy.com/learn/learn-sql" target="_blank">Codecademy: Learn SQL</a></li>
            <li><a href="https://www.mysqltutorial.org/" target="_blank">MySQL Tutorial</a></li>
        </ul>
    </section>

    <section id="tools-section">
        <h2>Essential Tools</h2>
        <ul>
            <li><a href="https://code.visualstudio.com/" target="_blank">Download Visual Studio Code</a></li>
            <li><a href="https://notepad-plus-plus.org/downloads/" target="_blank">Download Notepad++</a></li>
            <li><a href="https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer" target="_blank">Install Live Server for VS Code</a></li>
        </ul>
    </section>

    <section id="freelancing-section">
        <h2>Freelancing Tips & Platforms</h2>
        <ul>
            <li><a href="https://www.upwork.com" target="_blank">Upwork</a></li>
            <li><a href="https://www.fiverr.com" target="_blank">Fiverr</a></li>
            <li><a href="https://www.freelancer.com" target="_blank">Freelancer</a></li>
            <li><a href="https://www.toptal.com" target="_blank">Toptal</a></li>
            <li><a href="https://www.codecademy.com/articles/freelancing-tips-for-developers" target="_blank">Freelancing Tips for Developers</a></li>
        </ul>
    </section>

    <footer>
        <p>Created by You | All Rights Reserved © 2024</p>
    </footer>

</body>
</html>

 
