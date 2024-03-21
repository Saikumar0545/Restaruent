<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css" integrity="sha512-DTOQO9RWCH3ppGqcWaEA1BIZOC6xxalwEsw9c2QQeAIftl+Vegovlnee1c9QX4TctnWMn13TZye+giMm8e2LwA==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <style>
        *{
            padding: 0;
            margin: 0;
            font-family:'Times New Roman', Times, serif;
        }
        body{
            background-color: rgb(0, 0, 0);
        }
        nav{
            display: flex;
            justify-content: space-around;
            align-items: center;
            background-color:rgb(244, 57, 88);
            color: black;
        }
        ul{
            display: flex;
        }
        nav ul li{
            list-style-type: none;
            padding: 20px 60px;
        }
        a{
            text-decoration: none;
            color:black;
            
        }
        /* body part  starts */
        .container1{
            display: flex;
        }
        .card1{
            width: 50%;
        }
        .row1{
            padding: 30px;
        }
        .row1 h1,.row1 p{
            margin:40px 20px;
        }
        button{
            padding:5px 15px;
            background-color: rgba(249, 71, 128, 0.685);
            color: #f3efef;
            border: none;
            margin: 20px;
        }
        /* body parts end */
        .container2{
            display: flex;
            background-color: rgb(212, 22, 171);
            padding: 40px;
        }
        .card2{
            width: 50%;
        }
        .imgs{
            display: flex;
        }
        .first{
            width: 50%;
            padding: 10px;
        }
        .card2 .box{
            margin: 130px 0;
            background-color: rgb(242, 62, 62);
            color: black;
            display: inline-block;
            width: 50%;
        }
        .box h1, .box p{
            margin: 10px;
        }
        #grid {
            background-color: rgb(205, 43, 156); /* For browsers that do not support gradients */
            background-image: linear-gradient(rgb(248, 248, 187), rgb(253, 205, 213));
            }
    </style>
</head>
<body>
    <!-- nav bar starts -->
    <nav>
        <ul>
            <li><b><a href="">Home</a></b></li>
            <li><b><a href="">Order</a></b></li>
            <li><b><a href="">Food</a></b></li>
            <li><b><a href="">Restaurant</a></b></li>
            <li><b><a href="">Testimonials</a></b></li>
            <li><b><a href="">Contact Us</a></b></li>
            <li><!-- Hamburger menu icon -->
             <b> <a href="#menu">☰</a></b></li>
        </ul>
    </nav>
    <!-- nav bar ends -->
    <!-- body starts -->
    <div class="container1">
        <div class="card1">
            <div class="row1" id="grid">
                <h1>LOREM IPSUM</h1>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Amet quibusdam doloremque, rerum sequi quis ex voluptates temporibus at atque delectus necessitatibus eos? Adipisci ut eum harum! Iusto molestias consequuntur obcaecati. lor Lorem ipsum dolor sit amet consectetur adipisicing elit. Sapiente corporis natus provident laborum, enim beatae temporibus praesentium non impedit suscipit illum quo culpa necessitatibus! Esse, officia.ng elit. Cumque accusamus, dolores </p>
                <button type="button"><a href="">click me</a></button>
            </div>
        </div>
        <div class="card1">
            <img src="C:\Users\banga\OneDrive\Pictures\BURGER.jpg" width="100%" height="408px"  alt="">

        </div>
    </div>
    <!-- body ends -->
    <!-- footer starts -->
    <div class="container2" id="grid">
        <div class="card2">
            <div class="imgs">
                <div class="first">
                    <img src="c:\Users\banga\OneDrive\Pictures\stag.jpg" height="200px" width="100%" alt="">
                    <img src="c:\Users\banga\OneDrive\Pictures\city.jpg" height="200px" width="100%" alt="">
                </div>
                <div class="first">
                    <img src="C:\Users\banga\OneDrive\Pictures\food.jpg" height="404px" width="100%" alt="">
                </div>
            </div>
        </div>
        <div class="card2">
            <div class="box">
                <p>LOREM IPSUM</p>
                <h1>LOREM IPSUM <br> SET ADEMIR</h1>
                <p>Click<i class="fa-solid fa-right-long " style="margin: 10px; padding: 3px;"></i></p>
            </div>
        </div>
    </div>
    <!-- footer ends -->
</body>
</html>
