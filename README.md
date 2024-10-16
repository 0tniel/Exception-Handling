# Exception-Handling
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exception Handling in C++</title>
</head>
<body>
    <h1>Exception Handling in C++</h1>

 <h2>Aim</h2>
    <p>To study Exception Handling in C++.</p>

<h2>Theory</h2>
    <h3>Definition</h3>
    <p>Exception handling in C++ is a mechanism to manage runtime errors, allowing a program to catch and respond to errors gracefully.</p>
    <h3>Components</h3>
    <ul>
        <li><strong>try block:</strong> Encloses code that may throw an exception.</li>
        <li><strong>throw statement:</strong> Signals the occurrence of an exception.</li>
        <li><strong>catch block:</strong> Handles exceptions thrown by the try block.</li>
    </ul>

  <h3>Advantages</h3>
    <ul>
        <li>Separation of Error Handling</li>
        <li>Program Continuity</li>
        <li>Improved Debugging</li>
    </ul>

  <h3>Disadvantages</h3>
    <ul>
        <li>Performance Overhead</li>
        <li>Overuse can clutter code</li>
        <li>Increased Complexity</li>
    </ul>

 <h2>Output</h2>
    <p>Error: Division by zero error</p>

 <h2>Algorithms</h2>
    <ol>
        <li>Identify critical code where exceptions may occur.</li>
        <li>Enclose the code inside a try block.</li>
        <li>Use throw to signal an exception.</li>
        <li>Catch the exception with a matching catch block.</li>
        <li>Handle exceptions gracefully.</li>
    </ol>

 <h2>Code to Handle Division by Zero</h2>

 <h2>Output</h2>
    <p>
        Enter the values of 1 & 2: <br>
        8 0 <br>
        ERROR: Division by 0 <br>
        Enter the values of 1 & 2: <br>
        8 4 <br>
        Answer = 2
    </p>
</body>
</html>
