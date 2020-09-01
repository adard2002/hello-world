[Home Page](README.md)
<html>
<title>DISCUSSION_04</title>
            <h1>Structure Web Pages with HTML</h1>
    <body>
            <h2>About HTML</h2>
            <li>What is HTML?</li>
    <p>
    HTML is an acronym which stands for "Hypertext Markup Language". Let's break that down shall we?<br>
    - HyperText: means it allows you to make links which lets people who visit the website to switch between tabs quickly.<br>
    - Markup Language: markup is the tags we put at the ends of text we want to display. The markup is not displayed on the site. The only times you can see the actually markup is when escape characters are at play. 
                <li>What exactly is HTML code?</li>
    The HTML code has angled brackets which contain characters which are inside angled brackets. The angled brackets are called elements, and these elements have two parts to them. An opening and a closing, the closing element will have a forward slash. This tells the program that that is where the command ends. There are some open ended elements too, such as the &lt;img src&gt;. There are atributes inside of elements also, atributes tell us more about elements. <br>
    Example: &lt;p&gt; lang=&ldquo;en-us&rdquo;&gt;Paragraph in English&lt;/p&gt;
    - lang is the _attribute_ name and the "en-us" is the _attribute value_
    </p>
            <h2>Evolution of HTML</h2>
    <ul>
    <li><b>HTML 4 (Released in 1997):</b></li>
            Some markup can be done in CSS now; &lt;center&gt;, &lt;font&gt;, and &lt;strike&gt;.
    <li><b>XML (Released in 1998):</b></li>
            Created for writing in a new markup language, this included having people to follow new, more strict rules. <br>
    <li><b>XHTML 1.0 (Released in 2000):</b></li>
            Since people had to follow the new rules of markup it was decided that people could use one of two formats of XHTML. <br>
                Transitional XHTML 1.0: Allowed people to use a less strict syntax which let them use some of the older markup.<br>
                Frameset XHTML 1.0: Allowed people to have several frames open. Each of those frames held some different HTML pages. This is the least used.<br>
    <li><b>HTML 5 (Work in Progress):</b></li> <br>
            Tags don't have to be closed and new elements and attributes will be introduced. 
    </p>
            <h2>Process of designing a web page</h2>
    <p>
        First, you are going to want to set up a Site Map and a wireframe for your web page. You will probably want to use pencil and paper because you will want to show your customer your making the web pages for will be satisfied with your work. There may be some trial and error getting it what your customer's expectations may be. Down below are an example of each. 
    </p>
        <li>What is a Site Map?</li>
     <p>
        It is a layout of what will all be seen in your navigation bar and what will all be inside each and every link that is in your navigation bar. It will help you organize and plan out what will be in those tabs. 
    </p>
        <div style="text-align: center;">
         <img src="https://miro.medium.com/max/490/0*fmTh6pyS31Q3ShmG.jpg" width="490" height="237">
         </div>
                <li> What is a Wireframe?</li>
    <p>
        It is a layout of what your web page will look like. It organizes where your navigation bar will be, your logo, your pictures, etc.
    </p>
        <div style="text-align: center;">
         <img src="https://moqups.com/blog/wp-content/uploads/2020/02/Screen4b.png" width="512" height="512"> 
         </div>
             <h2>What to look for in designing a navigation bar</h2>
    <p>
        - Decide where you want your Nav. Bar located; top, left, right, etc.<br>
        - Make it look nice appealing to the eye, have your main tabs like "Home" and "About Us" and "Contact".<br>
        - Once you have your main tabs you can then add your secondary tabs which will show when the user hovers over it or clicks a dropdown arrow.<br>
        - The users will need some indication as to where they are in your site. Which can be accomplished by several choices; highlighting, arrow, color change, etc.  
    </p>
        <div style="text-align: center;">
    <img src="https://www.jquery-az.com/wp-content/uploads/2015/11/9.3-Bootstrap-navbar-custom.png" width="943" height="210">
         </div>
    <p>
    In this example you can see they are located at the "Home" page and are looking at the "Bootstrap" tab. Which has a few choices of pages to go to. It's not clutered, it's easy to read and simple to follow.</p>
    <h2>Some Elements and Attributes to help you get started with HTML</h2>


    </body>
</html>


Elements     |        What it does       |
:------------------|:------------------:|
&lt;html&gt;&lt;/html&gt;  | Tells everything between the markup that everything is html.  Contains everything within an HTML document.        |
&lt;body&gt;&lt;/body&gt;           | Should be closed only at the end before the html closing  |
<h1></h1>                    | Headers, with 1 through 6 sizes. |
<p></p>                      | Symbolizes paragraph. |
<title></title>              | Title is displayed at the top at the browser's title bar. |
<footer></footer>            | Usually at the bottom and contains information like copyright and author. |
<!-- -->                     | A comment, can't be seen in the actual browser but can be seen only when you open the code	Used to put everything between it in the center. 
<div style="text-align: center;"><div> | Should be used quite often around images to help the words stay together and not break off in the middle by the bottom of the picture. |
<img src="" width="number" height="number">  | Is where you put the link to an image.  width and height are attributes which determine the width and height in pixels.	 |
</br>  |This is used to force a break line in a sentence so it's not all clumped together.    |

<table>
<thead>
<tr>
<th>header 1</th>
<th>header 2</th>
</tr>
</thead>
<tbody>
<tr>
<td>cell 1.1</td>
<td>cell 1.2</td>
</tr>
<tr>
<td>cell 2.1</td>
<td>cell 2.2</td>
</tr>
</tbody>
</table>
