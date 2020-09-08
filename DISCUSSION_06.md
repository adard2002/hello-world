[Home Page](README.md)

<!DOCTYPE html>
<html>
<link rel="stylesheet" href="style.css">
<title>DISCUSSION_06</title>
<body>
    <h1>Dynamic web pages with JavaScript</h1>
        <h2>What does JavaScript do?</h2>
            <p>Javascript is where the behavior and interactivity of the page is created. JavaScript <bold>IS</bold> case sensitive.</p>
        <h2>What is a Script?</h2>
            <p>A script is like that of a movie script. It tells the computer what to do step-by-step. Each individual intruction is called a statement, which should always end with a semi colon.</p>
        <h2>What is a Statement?</h2>
            <p>A statement is a line of instruction and should always have it's own line, should always end in a semi colon and can be organized into code blocks.</p>
        <h2>Methods, Objects, Member Operator and Parameters</h2>

<p><span class="pinkText">document</span>.<span class="greenText">write(</span><span class="yellowText">'Good Afternoon!'</span><span class="greenText">);</span><br>
</p>
<p>
- <span class="pinkText">document</span>: Called the "object". This represents the entire page.<br>
- .: The period or dot is the Member Operator. Is placed between the object name and method you want to access.<br>
- <span class="greenText">write()</span>: This is the method of the document, allows new content to written into the page where the &lt;script&gt; element is found.<br>
- <span class="yellowText">'Good Afternoon!'</span>: This is parameters. This is needed if the method requires some more info in order to work and is placed between the parenthesis. In, this case the the write() method needs to know what to write.<br>
</p>
        <h2>Variables and Quantity</h2>
            <h3>What is a Variable?</h3>
                <p>It is used as a storage system for bits of script information it needs to work correctly.</p>
<p><span class="deepPink">var</span> <span class="blueText">quantity</span>;<br>
- <span class="deepPink">var</span>: Variable Keyword; you must give the variable a name, sometimes called an identifier. As you can see in this case the variable is called <span class="blueText">quanity</span>.<br>
- <span class="blueText">quantity</span>: Variable Name; If it is more than one word you will have to use Camel case which means the first word is going to be lowercase and the beginning of every word after the first word will be uppercase. Example: camelCase</p><br>
        <h2>Variable names, values, and Assignment Operator</h2>
<p><span class="deepPink">quantity</span> <span class="greenText">=</span> <span class="blueText">3</span>;<br>
- <span class="deepPink">quantity</span>: Variable Name<br>
- <span class="greenText">=</span>: Assignment Operator; says you are going to assign a value to the variable.<br>
- <span class="blueText">3</span>: Variable Value <br>
The Value in this case is <span class="deepPink">quantity</span>.<br>
</p>
        <h2>What are Statements and Code Blocks?</h2>
<p><span class="greenText">Var today = new Date(); <br>
var hourNow = today.getHours();<br>
var greeting;</span></p><br>
<p>
<span class="dodgerBlue">if (hourNow > 18)</span><span class="pinkText">;</span><br>
<p class="tab"><span class="greenText">greeting = 'Good evening';</span></p><br>
<span class="pinkText">}</span> <span class="dodgerBlue">else if (hourNow > 12)</span><span class="pinkText">{</span><br>
<p class="tab"><span class="greenText">greeting = 'Good afternoon';</span></p><br>
<span class="pinkText">}</span> <span class="dodgerBlue">else if (hourNow > 0)</span> <span class="pinkText">{</span><br>
<p class="tab"><span class="greenText">greeting = 'Good morning';</span></p><br>
<span class="pinkText">}</span> <span class="dodgerBlue">else</span> <span class="pinkText">{</span><br>
<p class="tab"><span class="greenText">greeting = 'Welcome';</span></p><br>
<span class="pinkText">}</span><br>
<span class="greenText">document.write(greeting);</span>
</p>

<span class="greenText">green lines</span> are a statement. <br>
<span class="pinkText">pink curly braces</span> indicate start and end of a code block. <br>
<span class="dodgerBlue">blue code</span> determines which code should run.<br>
        <h2>Data Types</h2>
    - Numeric: Handles numbers. Example: 0.75<br>
    - String: Letters and other characteristics. Example: 'Hi, Ivy!'<br>
    - Boolean: Show one of two values; true or false. Is like a light switch only two outcomes.<br>
Quotes should always be straight. <br>
String should always be writtin in one line. <br>
        <h2>Rules for naming variables</h2>
    1. Name must begin with either a letter, dollar sign, or underscore, can never start with a number. <br>
    2. Cannot use a dash or a period in a variable name.<br>
    3. Cannot use keywords or reserved words such as var.<br>
    4. Case sensitive.<br>
    5. Use a short and simple name that describes the variable info. Like "firstName" or "lastName"<br>
    6. If your variable is made up of multiple words make sure the first letter of the first word is lowercase and after the first word every word must start with a capital.<br>
</body>
</html>