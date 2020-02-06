<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <title>Advanced CSS - Assignment 1</title>
    <style>
        a:link{
            color: green;
        }
        a[target="_blank"] {
            color:red;
        }
        #first-div p:first-of-type {
            content:"NEW";
        }
        #second-div p:nth-child(even) {
            color: red;
        }
        #second-div p:nth-child(odd) {
            color: blue;
        }
        p:hover:last-child{
            font-family: Georgia, 'Times New Roman', Times, serif;
        }
    </style>
</head>

<body>
    <h1>Main Heading</h1>
    <p>Paragraph 1</p>
    <a href="https://www.google.com/">Google</a>
    <a href="https://www.google.com/doodles">Google Doodles</a>
    <a href="https://www.link-group.eu/" target="_blank">Goto Link Group</a>
    <div id="first-div">
        <h2>Subheading</h2>
        <p>Paragraph 2</p>
        <p>Paragraph 3</p>
        <div id="second-div">
            <h3>Sub subheading</h3>
            <p>Paragraph 4</p>
            <p>Paragraph 5</p>
            <p>Paragraph 6</p>
            <p>Paragraph 7</p>
            <p>Paragraph 8</p>
        </div>
    </div>
    <p>Paragraph 9</p>
    <p>Paragraph 10</p>
</body>

</html>
