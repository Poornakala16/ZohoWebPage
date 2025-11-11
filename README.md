<!DOCTYPE html>
<html lang="en">
<head>
    <title>Document</title>
    <style>
        body{
            margin: 10;
            background-color: black;
            border-radius: 20px;
        }
        .Main{
            width: 94vw;
            height: 94vh;
            left: 3vw;
            top: 3vh;
            position: relative;
            box-shadow: 10px 10px 10px silver;
            background-color: whitesmoke;
            border-radius: 40px;
        }
        .Box{
            width: 20vw;
            height: 40vh;
            font-size: 100px;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            color: white;
            transition: all 1s ease-in-out;
            border-radius: 50px;
        }
        .Sub1{
            position: absolute;
            left: 3vw;
            top: 27vh;
            background-color: red;
        }
        .Sub2{
            position: absolute;
            background-color: green;
            top: 20vh;
            left: 26vw;
        }
        .Sub3{
            position: absolute;
            right: 3vw;
            top: 20vh;
            background-color: yellow;
        }
        .Sub4{
            position: absolute;
            background-color: blue;
            top: 27vh;
            right: 26vw;
        }
        .Main img{
            width: 94vw;
            height: 94vh;
            border-radius: 50px;
        }
        .Main:hover .Sub1{
            top: 24vh;
            background-color: white;
            color: red;
            border:5px solid red;

        }
        .Main:hover .Sub2{
            top: 27vh;
            background-color: white;
            color: green;
            border: 5px solid green;
        }
        .Main:hover .Sub3{
            top: 27vh;
            background-color: white;
            color: yellow;
            border: 5px solid yellow;
        }
        .Main:hover .Sub4{
            top: 24vh;
             background-color: white;
            color: blue;
            border: 5px solid blue;
        }
    </style>
</head>
<body>
    <div class="Main">
        <div class="Sub1 Box"><h1>Z</h1></div>
        <div class="Sub2 Box"><h1>O</h1></div>
        <div class="Sub3 Box"><h1>O</h1></div>
        <div class="Sub4 Box"><h1>H</h1></div>
    </div>
</body>
</html>
