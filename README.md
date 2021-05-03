# Gym-Registration-Form
<!--This is a front end code of an gym registration form by using HTML5 and CSS.-->


<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gym Website</title>
    <style>
        body {
            color: white;
            margin: 0px;
            padding: 0px;
            background: url('background2.jpg');
            font-family: cursive;
        }

        .navbar {
            display: inline-block;
        }

        .left {
            display: inline-block;
            /*border: 2px solid red;*/
            position: absolute;
            left: 60px;
            top: 20px;
        }

        .left img {
            width: 125px;
            filter: invert(100%);

        }

        .left div {
            text-align: center;
            line-height: 0px;
        }

        .mid {
            display: block;
            width: 40%;
            margin: 29px auto;
            /*border: 2px solid green;*/
        }


        .navbar li {
            display: inline-block;
            font-size: 20px;
        }

        .navbar li a {
            text-decoration: none;
            color: white;
            padding: 20px 30px;
        }

        .navbar li a:hover {
            color: silver;
        }

        .right {
            position: absolute;
            right: 34px;
            top: 43px;
            display: inline-block;
            /*border: 2px solid yellow;*/
        }

        .btn {
            font-family: 'Baloo Bhai', cursive;
            margin: 0px 9px;
            background-color: black;
            color: white;
            padding: 4px 14px;
            border: 2px solid grey;
            border-radius: 10px;
            font-size: 20px;
            cursor: pointer;
        }

        .btn:hover {
            color: white;
            background-color: gray;

        }

        .container {
            /*border: 2px solid white;*/
            margin: 30px 30px;
            padding: 75px;
            width: 33%;
            border-radius: 28px;
        }

        .form-group input {
            text-align: center;
            display: block;
            margin: 7px auto;
            padding: 7px;
            border: 2px solid black;
            width: 250px;
            font-size: 20px;
        }

        .container h1 {
            text-align: center;
            color: rgb(255, 255, 255);
        }

        .form-group button {
            display: block;
            width: 50%;
            margin: 20px auto;
        }
    </style>
</head>

<body>
    <header>
        <div class="left">
            <img src="logo.png" alt="">
            <div>Fardeen Fitness</div>
        </div>
        <div class="mid">
            <ul class="navbar">
                <li><a href="#" class="active">Home</a></li>
                <li><a href="#" class="active">Fitness</a></li>
                <li><a href="#" class="active">About</a></li>
                <li><a href="#" class="active">Contact Us</a></li>
            </ul>
        </div>
        <div class="right">
            <button class="btn">E-Mail</button><button class="btn">Contact Info</button>
        </div>
    </header>
    <div class="container">
        <h1>Registration Form</h1>
        <form action="">
            <div class="form-group">
                <input type="text" name="" placeholder="Enter your Name">
            </div>
            <div class="form-group">
                <input type="text" name="" placeholder="Enter your Age">
            </div>
            <div class="form-group">
                <input type="text" name="" placeholder="Enter your Gender">
            </div>
            <div class="form-group">
                <input type="text" name="" placeholder="Enter your Locality">
            </div>
            <div class="form-group">
                <input type="text" name="" placeholder="Enter your Email Id">
            </div>
            <div class="form-group">
                <input type="text" name="" placeholder="Enter your Phone Number">
            </div>
            <div class="form-group">
                <button class="btn">Submit</button>
            </div>
        </form>
    </div>
</body>

</html>
