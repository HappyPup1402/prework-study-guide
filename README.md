<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
    body {
    font-family: Arial, sans-serif;
    
    margin: 0;
    padding: 20px;
}
.container {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
}
.box {
    background-color: #fff;
    border: 1px solid #ddd;
    border-radius: 5px;

    padding: 20px;
    width: calc(35% - 20px);
}
.box h2 {
    margin-top: 0;
}

h1{
    color: rgb(36, 34, 34);
}
footer{
    margin-top: 70px;
}
    </style>
</head>
<body>
    <h1>Pre-work Study Guide</h1>
    <div class="container">
        <div class="box">
            <h2>HTML</h2>
            <ul>
                <li>Introduction to HTML</li>
                <li>Basic Tags</li>
                <li>HTML Structure</li>
                <li>Forms and Inputs</li>
            </ul>
        </div>
        <div class="box">
            <h2>CSS</h2>
            <ul>
                <li>Introduction to CSS</li>
                <li>Selectors and Properties</li>
                <li>Box Model</li>
                <li>Flexbox and Grid</li>
            </ul>
        </div>
        <div class="box">
            <h2>Git</h2>
            <ul>
                <li>Introduction to Git</li>
                <li>Basic Commands</li>
                <li>Branching and Merging</li>
                <li>GitHub Workflow</li>
            </ul>
        </div>
        <div class="box">
            <h2>JavaScript</h2>
            <ul>
                <li>Introduction to JavaScript</li>
                <li>Variables and Data Types</li>
                <li>Functions</li>
                <li>DOM Manipulation</li>
            </ul>
        </div>
    </div>
    
</body>
</html>