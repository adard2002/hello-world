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
            <th align="left">Is equal to</th>
            <th align="left">Is not equal to</th>
            <th align="left">Strict Equal to</th>
            <th align="left">Strict not equal to</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td align="left">==</td>
            <td align="left">!=</td>
            <td align="left">===</td>
            <td align="left">!==</td>
        </tr>
        <tr>
            <td align="left">This operator compares two values such as numbers, strings or booleans to see if they are the same.</td>
            <td align="left">This operator compares two values such as numbers, strings, or booleans to see if they are not the same.</td>
            <td align="left">This is the prefered operator to use which compares two values to check if both the data type and the value are the same.</td>
            <td align="left">This is the prefered operator to use which compares two values to check if both the data type and the value are not the same.</td>
        </tr>
        <tr>
            <td align="left">'<span class="pinkText">Hello</span>' == '<span class="pinkText">Goodbye</span>' returns <span class="deepPink">false</span> because they are not the same string.<br>'<span class="pinkText">Hello</span>' === '<span class="pinkText">Hello</span>' returns <span class="greenText">true</span> because they are the same string</td>
            <td align="left">'<span class="pinkText">Hello</span>' != '<span class="pinkText">Goodbye</span>' returns <span class="greenText">true</span> because they are not the same string.<br>'<span class="pinkText">Hello</span>' === '<span class="pinkText">Hello</span>' returns <span class="deepPink">false</span> because they are the same string</td>
            <td align="left">'<span class="pinkText">3</span>' === <span class="pinkText">3</span> returns <span class="deepPink">false</span> because they are not the same data type or value.<br> '<span class="pinkText">3</span>' === '<span class="pinkText">3</span>' returns <span class="greenText">true</span> because they are the same data type and value.</td>
            <td align="left">'<span class="pinkText">3</span>' === <span class="pinkText">3</span> returns <span class="greenText">true</span> because they are not the same data type or value.<br> '<span class="pinkText">3</span>' === '<span class="pinkText">3</span>' returns <span class="deepPink">false</span> because they are the same data type and value.</td>
        </tr>
    </tbody>
</table>

























</body>
</html>