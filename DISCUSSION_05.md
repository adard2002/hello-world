[Home Page](README.md)

<!DOCTYPE html>
<html>
<title>DISCUSSION_05</title>
<body>
        <h1>Design web pages with CSS</h1>
        <h2>Evolution of CSS</h2>
        <li><b>CSS1 (Released in 1996)</b></li>
        <li><b>CSS2 (Released in 1998)</b></li>
        <li><b>CSS3 (World in Progress but some browsers have already started to implement it)</b></li>
         - What is CSS?
        CSS stands for Cascading Style Sheets, since HTML was just the structure of a web page CSS is putting all of the details on the structure.
         - How does it work?
        The thing to pay attention too trying to understand how CSS works is there is a box around all of the HTML elements. <br>
        CSS works by cooperating with the rules of HTML elements. These rules control how the content of specified elements will be shown throughout the site.
        The rules of CSS contains two parts. One being a <b>Selector</b> and the other being a <u>declaration</u>. The example below tells you that everything between the &lt;p&gt; element is going to have the Arial font applied to it.<br>
                Example: <b>p</b>{ <br>
                    <u>font-family: Arial;</u>}<br>
        <li><b>Selectors:</b> tell which element the rule applies to. In the example above this tells you that everything within the &lt;p&gt; will be changed.<br></li>
        <li><u>Declaration:</u> tells which rule is going to be applied to the element. In the example above this tells you it wants to change everything to the Arial font.<br></li>
        <p>
        CSS declarations sit inside curly brackets and is made up of two parts: a <b>property</b> and a <u>value</u>, separated by a colon. You can specify several properties within a declaration by separating them by a semi-colon. <br>
                Example: h1, h2, h3 {<br>
                                <b>font-family:</b> <u>Arial;</u><br>
                                <b>color:</b> <u>yellow;</u><br>
                                }<br>
        <li><b>property:</b>indicates the aspects you want to change. In this case it's color and the font. But there more aspects such as width, height, and border. <br></li>
        <li><u>value:</u> specifies the settings you want to apply to the aspects you want to change. In this case the font family is going to be Arial and the color is going to be yellow <br></li>
        </p>
        <p>
        &lt;link&gt; used in an HTML document to tell the browser where the CSS file is that was used to style the page. It lives inside of the &lt;head&gt; element and doesn't need a closing tag. It should use 3 attributes being:<br>
        <li>href: specifies the path or location of the CSS file. (often placed in a folder called CSS or styles).<br></li>
        <li>type: specifies the type of document being linked to. Value should be text/css.<br></li>
        <li>rel: specifies the relationship between the HTML page and the file it is being linked too. If it's being linked to a CSS file the value should be stylesheet.<br></li>
        <b>Example:</b><br>
                &lt;head&gt;<br>
                        &lt;title&gt;Using External CSS&lt;/title&gt;<br>
                        &lt;link href=&ldquo;css/style.css&rdquo; type=&ldquo;text/css&rdquo; rel=&ldquo;stylesheet&rdquo;/&gt;<br>
                &lt;/head&gt;<br>
        </p>
        <p>
        &lt;style&gt;: usually sits inside a &lt;head&gt; element. Should contain the type attribute to indicate the styles are specified in CSS and the value should be text/css.
        </p>
        <h2>CSS Selectors</h2>
        - What do they do?<br>
        Allow you to target specific elements in an HTML document.<br>


<table style="width:100%">
    <thead>
        <tr>
            <th align="left">Selector</th>
            <th align="left">Meaning</th>
            <th align="left">Example</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td align="left">Universal Selector</td>
            <td align="left">Applies to all elements in the document.</td>
            <td align="left">*{} Targets all elements on the page</td>
        </tr>
        <tr>
            <td align="left">Type Selector</td>
            <td align="left">Matches element names</td>
            <td align="left">h1, h2, h3 {} Targets the h1, h2, and h3 elements</td>
        </tr>
        <tr>
            <td align="left">Class Selector</td>
            <td align="left">Matches element whose calss attribute has a value that matches the one specified after the period symbol.</td>
            <td align="left">p.note {} Targets only &lt;p&gt; elements whose class attribute has a value of note.</td>
        </tr>
        <tr>
            <td align="left">ID Selector</td>
            <td align="left">Matches an elements whose id is attribute has the pound or hash symbol.</td>
            <td align="left">#introduction {}</td>
            </tr>
        <tr>
            <td align="left">Child Selector</td>
            <td align="left">Matches element that is a direct child of another</td>
            <td align="left">li&gt;a{} Targets any &lt;a&gt; elements that are children of an &lt;li&gt; element.</td>
        </tr>
        <tr>
            <td align="left">Desendant Selector</td>
            <td align="left">Matches an element that is a specified element</td>
            <td align="left">p a{} this targets any &lt;a&gt; elements that are inside a &lt;p&gt; element. Even if there are other elements nested between them </td>
        </tr>
        <tr>
            <td align="left">Adjacent Sibling Selector</td>
            <td align="left">Matches the next element sibling of another</td>
            <td align="left">h1+p {} Targets the first &lt;p&gt; element after any &lt;h1&gt; element.</td>
        </tr>
        <tr>
            <td align="left">General Sibling Selector</td>
            <td align="left">Matches an element that is a sibling of another. Even when it doesn't need to be the direct next element.</td>
            <td align="left"></td>
        </tr>
    </tbody>
</table>
        <h3>How to add a comment in CSS</h3>
        /* (msg here) */
        <h2>Implementing Colors</h2>
                <h3>How can you specify colors in CSS?</h3>
                <p>There are a total of three ways to do this:<br>
        <b>RGB Values:</b>
        These express colors by telling how much Red, Green and blue are used to make up that specific color.
        <li>Example:</li> p { <br> color: rgb(100,100,90);}
        <b>Hex Codes:</b> 
        6 digit codes that represent how much red, green, and blue are in the color. They have a hash # sign before them.
        <li>Example:</li> h2 { <br> color:#ee3e80;}
        <b>Color Names:</b> 
        There are a total of 147 predefined color names that are recognized by browsers.
        <li>Example:</li> h1 {<br> color:DarkCyan;}
        <h3>CSS3: HSL Colors</h3>
        <b>H: Hue-</b> expressed as an angle. (0 - 360)
        <b>S: Saturation-</b> expressed as a percentage.
        <b>L: Lightness-</b> expressed as a percentage with 0% being white, 50% being normal, and 100% being black.
        <b>a: Alpha-</b> expressed as a number between 0 and 0.1. For example, 0.5 represents 50% transparency and 0.75 represents 75% transparency.
</body>
</html>