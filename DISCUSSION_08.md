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








</body>
</html>