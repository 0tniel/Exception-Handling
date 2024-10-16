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

 <h2>Algorithms</h2>
    <ol>
        <li>Identify critical code where exceptions may occur.</li>
        <li>Enclose the code inside a try block.</li>
        <li>Use throw to signal an exception.</li>
        <li>Catch the exception with a matching catch block.</li>
        <li>Handle exceptions gracefully.</li>
    </ol>

 <h2>Code to Handle Division by Zero</h2>
<h1>Algorithm for Handling Division by Zero Exception</h1>

<h2>1. Start:</h2>
    <p>Begin the program.</p>

 <h2>2. Input:</h2>
    <p>Prompt the user to enter two float values (<code>n1</code> and <code>n2</code>).</p>

 <h2>3. Try Block:</h2>
 <ol>
        <li>Check if the second value (<code>n2</code>) is equal to zero.
            <ul>
                <li>If <strong>true</strong>:
                    <ol>
                        <li><strong>Throw Exception</strong>: Signal an exception with the value of <code>n2</code>.</li>
                    </ol>
                </li>
                <li>If <strong>false</strong>:
                    <ol>
                        <li>Calculate the division: <code>ans = n1 / n2</code>.</li>
                        <li>Display the result: Print <code>"Answer = "</code> followed by the value of <code>ans</code>.</li>
                    </ol>
                </li>
            </ul>
        </li>
    </ol>

<h2>4. Catch Block:</h2>
    <ol>
        <li>If an exception is thrown:
            <ol>
                <li>Catch the exception and store it in a variable (<code>num</code>).</li>
                <li>Display an error message: Print <code>"ERROR: Division by "</code> followed by the value of <code>num</code>.</li>
            </ol>
        </li>
    </ol>

<h2>5. End:</h2>
</body>
</html>
