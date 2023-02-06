<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <nav>
        <div class="logo">
        </div>
    </nav>
    <div>
        <div class="container">
            <div class="article1">
                <article></article>
                <article></article>
            <div class="article2">
                <article></article>
                <article></article>
            </div>
            </div>
        </div>
    </div>
    <footer>
        <h1>Copyright 2023</h1>
    </footer>
    <style>
        nav {
            width: 100%;
            height: 80px;
            background-color: white;
            position: fixed;
            border-bottom: 2px solid black;
            box-shadow: 0px 0px 8px black;
        }
        article {
            width: 200px;
            height: 200px;
            background-color: white;
            position: relative;
            margin: 20px;
        }
        footer {
            width: 100%;
            height: 80px;
            background-color: white;
            position: fixed;
            border-top: 2px solid black;
            border-color: black;
            text-align: center;
        }
        .container {
            height: 800px;
            background-color: grey;
        }
        .article1 {
            position: relative;
            top: 225px;
            left: 100px;
        }
        .article2 {
            position: relative;
            left: 800px;
            bottom: 440px;
        }
        .logo {
            width: 80px;
            height: 80px;
            background-color: black;
            position: absolute;
            right: 0px;
        }
    </style>
</body>
</html>
