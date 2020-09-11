[Home Page](README.md)
<!DOCTYPE html>
<html>
<link rel="stylesheet" href="style.css">
<title>DISCUSSION_07</title>
<body>
    <h1>Programming with JavaScript</h1>
        <h2>How to start writing a script?</h2>
        Writing is a script is quite a bit like a recipe, it needs to be in a step-by-step process. Like when you start doing something for the first time like cooking it might seem kinda daunting as first, but when you have the step-by-step process like how a recipe tells you how to do something it should be simple. <br>
        <h3>Here are some steps to help you get started on your script.</h3>
        First, we are going to look at what your goal or what you want to achieve is, then we are going to break that down into smaller steps. Like building a lego set. On the box is a picture of what the outcome of the process will be, and there is a step-by-step booklet inside that tells you how to get to that point.<br>
        1. <b>Define the Goal:</b> What do you want to achieve or want to be the outcome?<br>
        2. <b>Design the Script:</b> Flowcharts are very useful at this part in the process, you are going to want to layout all of the individual steps that the computer needs to execute each individual task. <br>
        3. <b>Code each Step:</b> The computer needs to be able to understand what you want it to do, to do this go through each of your steps and code it step-by-step into your text editor. 
        <h2>Expressions and Operators</h2>
        An expression results in a single value. There are two different types of expressions.<br>
        1. <b>Expressions that assign a value to a variable:</b> for a variable to be useful it must be given a value. In this example you will see that it is done using the assignment operator (the equals sign). And the value of color is now beige.<br>
        - <span class="greenText">var color = 'beige';</span><br>
        2. <b>Expressions that use two or more values to return a single value:</b> You can perform operations on any number of individual values to determine a single value. In this example you will see that the value of area is now 6.<br>
        - <span class="greenText">var area = 3 * 2;</span><br>
        Expressions rely of things call operators. Operators make it able for programmers to create a single value from one or more values. We will be introducing five different types of operators.<br>
        1. <u>Assignment Operators</u><br>
        Give a value to a variable. In this example the value of a color is now beige.<br>
        - <span class="greenText">color = 'beige';</span><br>
        2. <u>Arithmetic Operators</u><br>
        Perform basic math, In this example the value of area is 6.<br>
        - <span class="greenText">area = 3 * 2;</span><br>
        3. <u>String Operators</u><br>
        Combine two strings. This example shows the value of greeting is set to Hi Molly. The characters within the single quotes (' ') are the strings.<br>
        - <span class="greenText">greeting = 'Hi ' + 'Molly';</span><br>
        4. <u>Comparison Operators</u><br>
        Compares two values and tells you it's either true or false. This example shows the value of buy is false.<br>
        - <span class="greenText">buy = 3 > 5;</span><br>
        5. <u>Logical Operators</u><br>
        Combines expressions and tells whether it's true or false. This example shows the value of buy is now true.<br>
        - <span class="greenText">buy = (5 > 3) && (2 < 4);</span><br>
<!--This is a table that goes with the Arithmetic Operators-->
        <h2>More about Arithmetic Operators</h2>
<table style="width:100%">
    <thead>
        <tr>
            <th align="left">Name</th>
            <th align="left">Operator</th>
            <th align="left">Purpose</th>
            <th align="left">Example</th>
            <th align="left">Result</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td align="left">Addition</td>
            <td align="left">+</td>
            <td align="left">Adds one value to another</td>
            <td align="left">10 + 5</td>
            <td align="left">15</td>
        </tr>
        <tr>
            <td align="left">Subtraction</td>
            <td align="left">-</td>
            <td align="left">Subracts one value from another</td>
            <td align="left">10 - 5</td>
            <td align="left">5</td>
        </tr>
        <tr>
            <td align="left">Division</td>
            <td align="left">/</td>
            <td align="left">Divides two values</td>
            <td align="left">10 / 5</td>
            <td align="left">2</td>
        </tr>
        <tr>
            <td align="left">Multiplication</td>
            <td align="left">*</td>
            <td align="left">Multiplies two values</td>
            <td align="left">10 * 5</td>
            <td align="left">50</td>
        </tr>
        <tr>
            <td align="left">Increment</td>
            <td align="left">++</td>
            <td align="left">Adds one to current number</td>
            <td align="left">i = 10; or i++;</td>
            <td align="left">11</td>
        </tr>
        <tr>
            <td align="left">Decrement</td>
            <td align="left">--</td>
            <td align="left">Subtracts one from current number</td>
            <td align="left">i = 10; or i--;</td>
            <td align="left">9</td>
        </tr>
        <tr>
            <td align="left">Modulus</td>
            <td align="left">%</td>
            <td align="left">Divides two values and returns the remainder</td>
            <td align="left">10 % 3</td>
            <td align="left">1</td>
        </tr>
    </tbody>
</table>
        Multiplication and Division are done before addition and subtraction. Let's look over some examples.<br>
        - Example: Calculated from left to right so the total will come out to be 16.<br>
        <span class="greenText">total = 2 + 4 + 10;</span><br>
        - Example: This will come out to be 42, not 60, the reasoning for this is because multiplication and division happen before addition and subtraction.<br>
        <span class="greenText">total = 2 + 4 * 10;</span><br>
        -Example: This will come out to a total of 60 now because the parenthesis indicate that the 2 is adding to the 4 and the outcome of that is multiplied by 10. The parenthesis also indicate which calculation you to be done first.<br>
        <span class="greenText">total = (2 + 4) * 10;</span><br>





</body>
</html>


