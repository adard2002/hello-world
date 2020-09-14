[Home Page](README.md)

<DOCTYPE html>
<html>
<link rel="stylesheet" href="style.css">
<title>DISCUSSION.08.md</title>
<body>
    <h1>Operators and Loops</h1>
        <h2>Comparison Operators: Evaluating Conditions</h2>
                You can assess a situation by comparing one value in the script to what you think it might be. The result will be a boolean (true or false).
<table style="width:100%">
    <thead>
        <tr>
            <th align="center">Is equal to</th>
            <th align="center">Is not equal to</th>
            <th align="center">Strict equal to</th>
            <th align="center">Strict not equal to</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td align="center">==</td>
            <td align="center">!=</td>
            <td align="center">===</td>
            <td align="center">!==</td>
        </tr>
        <tr>
            <td align="center">This operator compares two values such as numbers, strings or booleans to see if they are the same.</td>
            <td align="center">This operator compares two values such as numbers, strings, or booleans to see if they are not the same.</td>
            <td align="center">This is the prefered operator to use which compares two values to check if both the data type and the value are the same.</td>
            <td align="center">This is the prefered operator to use which compares two values to check if both the data type and the value are not the same.</td>
        </tr>
        <tr>
            <td align="center">'<span class="pinkText">Hello</span>' == '<span class="pinkText">Goodbye</span>'<br> returns <span class="deepPink">false</span> because they are not the same string.<br>'<span class="pinkText">Hello</span>' === '<span class="pinkText">Hello</span>'<br> returns <span class="greenText">true</span> because they are the same string</td>
            <td align="center">'<span class="pinkText">Hello</span>' != '<span class="pinkText">Goodbye</span>'<br> returns <span class="greenText">true</span> because they are not the same string.<br>'<span class="pinkText">Hello</span>' === '<span class="pinkText">Hello</span>'<br> returns <span class="deepPink">false</span> because they are the same string</td>
            <td align="center">'<span class="pinkText">3</span>' === <span class="pinkText">3</span><br> returns <span class="deepPink">false</span> because they are not the same data type or value.<br> '<span class="pinkText">3</span>' === '<span class="pinkText">3</span>'<br> returns <span class="greenText">true</span> because they are the same data type and value.</td>
            <td align="center">'<span class="pinkText">3</span>' === <span class="pinkText">3</span><br> returns <span class="greenText">true</span> because they are not the same data type or value.<br> '<span class="pinkText">3</span>' === '<span class="pinkText">3</span>'<Br> returns <span class="deepPink">false</span> because they are the same data type and value.</td>
        </tr>
    </tbody>
</table>
<table style="width:100%">
    <thead>
        <tr>
            <th align="center">Greater Than</th>
            <th align="center">Less Than</th>
            <th align="center">Greater Than or Equal To</th>
            <th align="center">Less Than or Equal to</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td align="center">></td>
            <td align="center"><</td>
            <td align="center">>=</td>
            <td align="center"><=</td>
        </tr>
        <tr>
            <td align="center">This operator makes sure the number on the left is greater than the number on the right.</td>
            <td align="center">This operator makes sure the number on the right is greater than the number on the left.</td>
            <td align="center">This operator makes sure the number on the left is greater than or equal to the number on the right.</td>
            <td align="center">This operator makes sure the number on the right is greater than or equal to the number on the left.</td>
        </tr>
        <tr>
            <td align="center">
                <span class="pinkText">4</span> > <span class="pinkText">3</span> returns <span class="greenText">true</span><br>
                <span class="pinkText">3</span> > <span class="pinkText">4</span> returns <span class="deepPink">false</span><br>
            </td>
            <td align="center">
                <span class="pinkText">4</span> < <span class="pinkText">3</span> returns <span class="deepPink">false</span><br>
                <span class="pinkText">3</span> < <span class="pinkText">4</span> returns <span class="greenText">true</span><br>
            </td>
            <td align="center">
                <span class="pinkText">4</span> >= <span class="pinkText">3</span> returns <span class="greenText">true</span><br>
                <span class="pinkText">3</span> >= <span class="pinkText">4</span> returns <span class="deepPink">false</span><br>
                <span class="pinkText">3</span> >= <span class="pinkText">3</span> returns <span class="greenText">true</span><br>
            </td>
            <td align="center">
                <span class="pinkText">4</span> <= <span class="pinkText">3</span> returns <span class="deepPink">false</span><br>
                <span class="pinkText">3</span> <= <span class="pinkText">4</span> returns <span class="greenText">true</span><br>
                <span class="pinkText">3</span> <= <span class="pinkText">3</span> returns <span class="greenText">true</span>
            </td>
        </tr>
    </tbody>
</table>
        <h2>Local Operators</h2>
            <table style="width:100%">
    <thead>
        <tr>
            <th align="center">Logical And</th>
            <th align="center">Logical Or</th>
            <th align="center">Logical Not</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td align="center">This operator tests more than one condition.</td>
            <td align="center">This operator tests at least one condition.</td>
            <td align="center">This operator takes a single boolean value and inverts it.</td>
        </tr>
        <tr>
            <td align="center">((2 < 5) && (3 >= 2))<br> returns <span class="greenText">true</span></td>
            <td align="center">((2 < 5) || (2 < 1))<br> returns <span class="greenText">true</span></td>
            <td align="center">!(2 < 1) returns <span class="greenText">true</span></td>
        </tr>
        <tr>
            <td align="center">
                <span class="greenText">true</span> && <span class="greenText">true</span> returns <span class="greenText">true</span><br>
                <span class="greenText">true</span> && <span class="deepPink">false</span> returns <span class="deepPink">false</span><br>
                <span class="deepPink">false</span> && <span class="greenText">true</span> returns <span class="deepPink">false</span><br>
                <span class="deepPink">false</span> && <span class="deepPink">false</span> returns <span class="deepPink">false</span>
            </td>
            <td align="center">
                <span class="greenText">true</span> || <span class="greenText">true</span> returns <span class="greenText">true</span><br>
                <span class="greenText">true</span> || <span class="deepPink">false</span> returns <span class="greenText">true</span><br>
                <span class="deepPink">false</span> || <span class="greenText">true</span> returns <span class="greenText">true</span><br>
                <span class="deepPink">false</span> || <span class="deepPink">false</span> returns <span class="deepPink">false</span>
                </td>
            <td align="center">
                !<span class="greenText">true</span> returns <span class="deepPink">false</span><br>
                <span class="deepPink">false</span> returns <span class="greenText">true</span>
            </td>
        </tr>
    </tbody>
</table>






            Comparison operators usually give only one of two values which are: <span class="greenText">true</span> or <span class="deepPink">false</span>. Logical operators give you the ability to compare the results of more than one comparison operator.<br>
            <span class="pinkText">(</span><span class="blueText">(5 < 2)</span> <span class="yellowText">&&</span> <span class="lightPurple">(2 >= 3)</span><span class="pinkText">)</span><br>
            There are a total of three expressions which will resolve to either <span class="greenText">true</span> or <span class="deepPink">false</span>. The expressions on the left and the right (expressions 1 and 2) both use comparison operators and both return <span class="deepPink">false</span>. The third expression uses a logical operator. The logical and operator check to see if both expressions on the sides return <span class="greenText">true</span> but in this case they don't so the whole thing evaluates to <span class="deepPink">false</span>.
            <span class="blueText">(5 < 2)</span>: Expression 1: Is five less than two? The result is <span class="deepPink">false</span>.<br>
            <span class="lightPurple">(2 >= 3)</span>: Expression 2: Is two greater than or equal to three? The result is also <span class="deepPink">false</span>.<br>
            <span class="pinkText">()</span>: Everything within these parenthesis are Expression 3<br>
            <span class="yellowText">&&</span>: This is a Logical Operator<br>
            


</body>
</html>