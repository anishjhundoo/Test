<!DOCTYPE html>
<html>
<head>
    <title>Contact Us</title>
    <style>
        @import url('https://fonts.googleapis.com/css?family=Rozha+One');
        @import url('https://fonts.googleapis.com/css?family=Indie+Flower|Rozha+One');
        @import url('https://fonts.googleapis.com/css?family=Dancing+Script');
        /*HEADER*/
        .header{
            width: 100%;
            height: 65px;
            background-color: rgba(0,0,0,0.7);
            color: white;
        }
        .header h1{
            background-color: red;
            padding: 18px 20px;
            float: left;
            font-family: 'Dancing Script', cursive;
            color: white;
        }
        .header nav ul li{
            float: left;
            display: inline;
            font-family: verdana;
            color: white;
        }
        .bar {
            background-color: red;
            width: 100%;
            height: 6px;
        }
        .select{
            padding: 23px 20px;
        }
        .select:hover{
            padding: 23px 20px;
            background-color: purple;
            transition-duration: 0.5s;
        }
        /*BACKGROUND*/
        *{
            margin: 0;
            padding: 0;
        }
        .nav{
            width: 350px;
            height: 350px;
            border-radius: 50%;
            position: absolute;
            z-index: 1;
            top: 200px;
            left: 510px;
        }

        .nav:hover{
            background-color: black;
            color: red;
            transition-duration: 0.7s;
        }
        .buttonCon{
            width: 100%;
            padding: 10px;
            color: #fff;
            font-size: 16px;
            font-weight: bold;
            background: red;
            border: none;
        }
        .buttonCon:hover{
            background: purple;
            transition-duration: 0.5s;
        }
        #swatches{
            float: right;
            font-size: 35px;
        }
        .contac{
            background-repeat: no-repeat;
            background-attachment: fixed;
            background-size: cover;
            width: 100%;
            height: 500px;
        }

        @-webkit-keyframes typing { from { width: 0; } }
        @-webkit-keyframes blink-caret { 50% { border-color: transparent; } }

        .heading2{
            position: absolute;
            top: 410px;
            left: 50px;
            font: bold 300% Consolas, Monaco, monospace;
            border-right: .1em solid black;
            color: red;
            text-shadow: 4px 4px #000;
            width: 16.5em;
            width: 29ch;
            white-space: nowrap;
            overflow: hidden;
            -webkit-animation: typing 2s steps(21, end),
            blink-caret .5s step-end infinite alternate;
        }
        /*contact-form*/
        .mailUs{
            width: 500px;
            height: 700px;
            margin: 50px 0 0 150px;
        }
        .mailUs input{
            margin-bottom: 20px;
        }
        .mailUs input[type="text"],
        .mailUs input[type="email"]
        {
            border: none;
            border-bottom: 2px solid red;
            background: transparent;
            outline: none;
            height: 40px;
            width: 300px;
            font-size: 16px;
        }
        .mailUs p{
            font-family: trebuchet ms;
            font-size: 15px;
            color: red;
        }
        fieldset{
            padding: 10px;
        }
        legend {
            font-family: trebuchet ms;
            color: purple;
            font-size: 30px;
        }
        textarea{
            width: 470px;
            height: 150px;
            border-width: 2px;
            border-color: red;
            font-family: trebuchet ms;
            padding: 5px;
        }
        placeholder{
            color: rgba(255,255,255,.3);
            font-family: trebuchet ms;
        }
        /*ticking img*/
        .cir-img{
            border-radius: 50%;
            position: absolute;
            top: 739px;
            left: 813px;
            width: 270px;
            height: 270px;
            z-index: 2;
        }
    </style>
    <link href="http://maxcdn.bootstrapcdn.com/font-awesome/4.1.0/css/font-awesome.min.css" rel="stylesheet">
</head>
<body>
    <div class="header">
        <nav>
          <a href="home.html"><h1>SWATCH</h1></a>
          <ul>
            <a href="#"><li class="select">Home</li></a>
            <a href="#"><li class="select">Shop</li></a>
            <a href="#"><li class="select">Contact Us</li></a>
            <a href="#"><li class="select">About Us</li></a>
            <a href="#"><li class="select">Login | Register</li></a>
          </ul>
          <ul id="swatches">
            <li><i class="fa fa-shopping-cart" style="padding: 15px 15px;background-color: red;"></i></li>
          </ul>
        </nav>
  </div>
  <div class="bar"></div>
    <div class="contac" style="background-image: url('contact.jpg');">
        <h2 class="heading2">Contact us on: +230-5828-1552</h2>
    </div>
    <div class="bar"></div>
    <div class="mailUs">
        <form>
            <fieldset>
                <legend>Contact Form</legend>
                <br><br>
                <p>Name*</p>
                <input type="text" placeholder="John Smith" required="">
                <p>E-mail*</p>
                <input type="email" placeholder="mail@example.com" required="">
                <p>Subject</p>
                <input type="text" placeholder="Subject" required="">
                <p>Comment</p><br>
                <textarea required="" placeholder="Write your comment here..."></textarea><br><br>
                <button class="buttonCon">Send</button>
            </fieldset>
        </form>
    </div>
    <img src="watch13.png" style="position: absolute;top:700px;left: 770px;">
    <img src="ticking.gif" class="cir-img">
</body>
</html>
