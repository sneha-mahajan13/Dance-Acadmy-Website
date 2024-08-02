# Dance-Acadmy-Website
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Snisha's Dance academy</title>
</head>
<link rel="stylesheet" href="style.css">
<style>
    /* CSS RESET */
    body {
        color: white;
        margin: 0px;
        padding: 0px;
        background: url('img2.jpg');
        background-size: 3000px 3000px;
        /* background-repeat: repeat-y; */
        /* background-position: right; */
        font-family: cursive;



    }


    .left {
        /* border: 2px solid red; */
        display: inline-block;
        position: absolute;
        left: 35px;
        top: 50px;
    }

    .center {
        /* border: 2px solid green; */
        display: block;
        width: 33%;
        margin: 38px auto;
        font-size: 19px;

    }

    .right {
        /* border: 2px solid yellow; */
        display: inline-block;
        position: absolute;
        top: 50px;
        right: 48px;

    }

    .navbar {
        display: inline-block;
    }

    .navbar li {
        color: white;
        display: inline-block;
        font-size: 25px;

    }

    .navbar li a {
        color: white;
        text-decoration: none;
        padding: 10px 10px;

    }

    .navbar li a:hover,
    .navbar li a:active {

        text-decoration: underline;
        color: bisque;
    }

    .left img {
        width: 33px;

    }

    .left div {
        text-align: center;
        line-height: 20px;
        font-size: 12px;
    }

    .btn {
        margin: 0px 9px;
        color: white;
        padding: 3px 4px;
        background-color: black;
        border: 2px solid grey;
        font-size: 16px;
        cursor: pointer;
        font-family: cursive;

    }

    .btn:hover {
        background-color: darkgrey;
    }

    .continer {
        border: 3px solid white;
        margin: 213px 2500px;
        padding: 150px 24px;
        border-radius: 4px;
    
        width: 30%;
        height: 40%;

    }

    .form-group input {
        font-size: 21px;
        margin: 17px auto;
        padding: 7px;
        text-align: center;
        display: block;
        width: 500px;
        border: 2px solid black;
        border-radius: 12px;
        font-family: cursive;

    }

    .continer h1 {
        text-align: center;
    }

    .continer button {
        display: block;
        width: 175px;
        margin: 41px auto;
        font-size: 25px;
        border-radius: 12px;

    }
</style>

<body>
    <header class="header">
        <!-- left box for logo -->
        <div class="left">
            <img src="img1.jpg" alt="">
            <div>Snisha's Academy</div>

        </div>
        <!-- center box for navigation bar -->
        <div class="center">
            <ul class="navbar">
                <li><a href="#" class="active">Home</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Contact us</a></li>
                <li><a href="#">Email us</a></li>
            </ul>

        </div>
        <!-- right box for button  -->
        <div class="right">
            <button class="btn">Call us</button>
            <button class="btn">Email</button>

        </div>
    </header>
    <div class="continer">
        <h1>Join the best dance academy of Pune</h1>
        <form action="noaction.php">
            <div class="form-group">
                <input type="text" placeholder="Enter your name">
            </div>
            <div class="form-group">
                <input type="text" placeholder="Enter your phone number">
            </div>
            <div class="form-group">
                <input type="text" placeholder="Enter your address">
            </div>
            <div class="form-group">
                <input type="text" placeholder="Enter your age">
            </div>
            <button class="btn">Sumit</button>

        </form>
    </div>

</body>

</html>
