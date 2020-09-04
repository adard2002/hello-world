[Home Page](README.md)

<!DOCTYPE html>
<html>
<title>DISCUSSION_05</title>
<body>
        <h1>Design web pages with CSS</h1>
        <li>What is CSS?</li>
        CSS stands for Cascading Style Sheets, since HTML was just the structure of a web page CSS is putting all of the details on the structure.
        <li>How does it work?</li>
        The thing to pay attention too trying to understand how CSS works is there is a box around all of the HTML elements. <br>
        CSS works by cooperating with the rules of HTML elements. These rules control how the content of specified elements will be shown throughout the site.
        The rules of CSS contains two parts. One being a <b>Selector</b> and the other being a <u>declaration</u>. The example below tells you that everything between the &lt;p&gt; element is going to have the Arial font applied to it.<br>
                Example: <b>p</b>{ <br>
                    <u>font-family: Arial;</u>}<br>
        - <b>Selectors:</b> tell which element the rule applies to. In the example above this tells you that everything within the &lt;p&gt; will be changed.<br>
        - <u>Declaration:</u> tells which rule is going to be applied to the element. In the example above this tells you it wants to change everything to the Arial font.<br>
        <p>
        CSS declarations sit inside curly brackets and is made up of two parts: a <b>property</b> and a <u>value</u>, separated by a colon. You can specify several properties within a declaration by separating them by a semi-colon. <br>
                Example: h1, h2, h3 {<br>
                                <b>font-family:</b> <u>Arial;</u><br>
                                <b>color:</b> <u>yellow;</u><br>
                                }
        - <b>property:</b> indicates the aspects you want to change. In this case it's color and the font. But there more aspects such as width, height, and border. <br>
        - <u>value:</u> specifies the settings you want to apply to the aspects you want to change. In this case the font family is going to be Arial and the color is going to be yellow <br>
        </p>
        <p>
        &lt;link&gt; used in an HTML document to tell the browser where the CSS file is that was used to style the page. It lives inside of the &lt;head&gt; element and doesn't need a closing tag. It should use 3 attributes being:<br>
        - href: specifies the path or location of the CSS file. (often placed in a folder called CSS or styles).<br>
        - type: specifies the type of document being linked to. Value should be text/css.<br>
        - rel: specifies the relationship between the HTML page and the file it is being linked too. If it's being linked to a CSS file the value should be stylesheet.<br>
        <b>Example:</b>
                &lt;head&gt;<br>
                        &lt;title&gt;Using External CSS&lt;/title&gt;
                        
        
        </p>









</body>
</html>