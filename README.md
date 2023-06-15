# task1
<!DOCTYPE html>
<html>
<head>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
  <title>Stock Market Landing Page</title>
  <style type="text/css">
   *{padding: 0; margin:0; box-sizing: border-box;}
    header {
      width: 100%;
      height: 100vh;
      background:linear-gradient(rgba(0,0,0,0.8),rgba(0,0,0,0.2)), url('img3.webp');
      backgrround-size: cover;
      font-family:sans-serif;
    }
nav{
width: 100%;
height: 100px;
color: black;
display:flex;
justify-content: space-around;
align-items: center;
}
.logo{
font-size:1.7em;
 letter-spacing: 1px;
color: gold;
   }
.menu a{
text-decoration:none;
color:white;
padding: 10px 20px;
font-size: 20px;
position: relative;
}
.menu a:before{
content: ' ';
position: absolute;
top: 0;
left: 0;
width:0%;
height: 100%;
border-bottom: 2px solid indianred;
transition: 0.4s linear;
}
.menu a:hover:before{
width: 90%;
}
.register a{
text-decoration:none;
color:white;
padding 10px 20px;
font-size:20px;
background: indianred;
border-radius: 8px;
transition; 0.4s;
}
.register a:hover{
background: transparent;
border: 1px solid indianred;
}
.h-txt{
 max-width: 650px;
position: absolute;
top: 50%;
left: 50%;
transform: translate(-50%,-50%);
text-align: center;
color: white;
}
.h-txt span{
letter-spacing: 5px;
}
.h-txt h1{
font-size: 3.5em;
}
.h-txt a{
text-decoration:none
color:white;
padding 10px 20px;
font-size:20px;
background: indianred;
border-radius: 8px;
transtion: 0.4s;
}
.h-txt a:hover{
background: transparent;
border: 1px solid indianred;
}
.ed{
padding:400px 30px;
color: indianred;
}


</style>
</head>
<body>
<header>
<nav>
<div class="logo">
Prime Trading
</div>
<div class="menu">
<a href="#">Home</a>
<a href="#">services</a>
<a href="#">Achievements</a>
<a href="#">contact us</a>
</div>
<div class="register">
<a href="#">Register</a>
</div>
<div>
<i class="fa fa-facebook" style="font-size:40px;color:indianred;"></i>
<i class="fa fa-instagram" style="font-size:40px;color:indianred;"></i>
<i class="fa fa-twitter" style="font-size:40px;color:indianred;"></i>
</div>
</nav>
<section class="h-txt">
<span>Enjoy</span>
<h1>Banknifty Option Trading</h1>
<br>
<a href"#">Apply</a>
</section>
<div class="ed"> 
<marquee direction="left">
Disclaimer: we are not SEBI registered and we deal only in Banknfity and nifty. Invest in your own Risk.</marquee>
</div>
</header>

</body>
</html>
