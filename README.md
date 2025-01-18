LEVEL 1

<!DOCTYPE html> /* is a way to tell the browser that the webpage is written in HML5, the latest and most widely used version og the HTML standard*/
<html lang="en">
    <head> /*is a crucial part that contains important metadata and settings for the webpage*/
        <meta charset="UTF-8"> /*meta tags provdide information about the page, such as character coding, viewport setttings and descriptions, here it sets the character coding to UTF-8*/
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>WhatDoesThisDo?</title /*title of the webpage*/
    </head>
    <body> /*in the body section is the code for the webpage ?/
        <h1>What does this do?</h1>/*displays on the webpage, hera is a HEading 1 used*/
    </body>
</html>



LEVEL 2

<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>level 2</title>
        <style>  /*here is a style attribution for CSS code inside HTML, the background color is going to be red*/
            .different {
                background-color: red;
            }
        </style>
    </head>
    <body>
        <h1 class="different">is this different from the h1 in level 1, if so, how is it different?</h1> /*the headline of the page*/
    </body>
</html>


/*do you remember how to do comments in css?*/  ---> yes, you do /*-*/
.different{
    color: #00FF00;
}

LEVEL 3

<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>level 2</title>
       <link rel="stylesheet" href="level3.css">  /* link to connect CSS to HTML document*/
    </head>
    <body>
        <h1 class="different">is this different from the h1 in level 2, if so, how is it different?</h1> /* yes, now you have special CSS document connected to HTML*/
    </body>
</html>


LEVEL 4

<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>level 2</title>
    </head>
    <body>
        <!- -
        Imagine that we have Tailwind installed in our project.
        - ->
        <h1 class="bg-gray-300 text-red-400">is this different from the h1 in level 3, if so, how is it different?</h1> /*example of how we use tailwind in our project. Background grey and red text*/
    </body>
</html>


LEVEL 5

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Hello World</title>
</head>
<body>
    <h1 id="greeting"></h1> /* the 'id' is attribute used to identify an HTML element, in this case greeting
                                the ids are used to target spcific elements on the page, often for styling or JavaScript manipulation. */

    <!- -
    Now comes the first thing we have never seen before, namely TypeScript.
    Try to read it and guess what it does, write in a comment what you think it will do
    Next use Google, ChatGPT and/or Claude to find out what it does.
    write in another comment what it actually does and see if it is far from what you thought it did
    - ->
    <script>  /*This is a JavaScript code block that is executed when the page loads.*/
        document.getElementById("greeting").innerHTML = "Hello, world!"; /*is a JavaScript method that finds the HTML element with the "greeting" ID. .innerHTML is a property that allows you to set the content inside the HTML element.*/
    </script>
</body>
</html>

Level 6

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Greeting</title>
</head>
<body> 
    <h1 id="greeting"></h1>  /*id attribute with the value "greeting this <h1> element is currently empty, as it doenst have eny text inside</h1>"

    <script src="level6.js"></script> /*This is a <script> tag that is used to include an external JavaScript file.
                                      The src attribute specifies the path to the JavaScript file, which in this case is "level6.js".
                                      When the web page loads, the browser will execute the JavaScript code contained in the "level6.js" file.*/

</body>
</html>






