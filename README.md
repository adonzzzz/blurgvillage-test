# blurgvillage-test
blurgvillage website for free.
[blurgvillage.html](https://github.com/user-attachments/files/33084198/blurgvillage.html)

<html>
<head>
     <title>blurgvillage.com</title>
     <link rel="stylesheet" href="style.css">
</head>
<body style="background-color:white">
<nav class="navbar">
<div class="navdiv">
<div class="logo">
<img src="/home/sths/Desktop/blurgvillage/blurg.jpg" alt="BLURGVILLAGE"> 
</div>
<ul>
   <li><a href="blurgvillage.html">Home</a></li>
   <li><a href="#about">About</a></li>
   <li><a href="#products">Trending</a></li>
   <li><a href="#contact">Contact</a></li>
</ul>
</div>
</nav> 

<section class="main">
<div class="main-box">
<div class="main-text">
<h1>Blurgvillage</h1>
<h2>Fashion Statement</h2>
<p>BLURG ORIGINALS IS WHERE THE<br>
BLURGVILLAGE VISION BECOMES CLOTHING.
EACH PIECE IS DESIGNED AND DEVELOPED
BY OUR TEAM, INSPIRED BY MODERN STREETWEAR
AND MADE TO BE WORN YOUR OWN WAY.</p>
<button class="shop"><a href="#">Shop Now</a></button>
</div>
<div class="main-img">
<img src="bg.jpg">
</div>
</div> 
</section>

<section id="about">
 <h1>ABOUT US</h1>
 <div class="about-box">
 <div class="about-boxes">
     <h2>Perfect Fashion</h2>
     <p>Statement pieces from our shop with discounts</p>
     </div>
 <div class="about-boxes">
     <h2>Explore Fashion</h2>
     <p>Explore the fashion of the west through us.</p>
     </div>
 <div class="about-boxes">
     <h2>Affordable Price</h2>
     <p>Lower price does "NOT" mean low quality in our shop</p>
     </div>
 </div>
</section>             

<section id="products">
<center><div class="header"><h1>TRENDING PIECES</h1></div></center>
<div class="box">
    <div class="product-box">
    <img src="black-bootcut.jpg">
    <h1>Black Bootcut</h1>
    <h2>1000 rs.</h2>
    <button class="cart"><a href="#">Add To Cart</a></button>
    </div>
    <div class="product-box">
    <img src="blue-bootcut.jpg">
    <h1>Blue Bootcut</h1>
    <h2>1000 rs.</h2>
    <button class="cart"><a href="#">Add To Cart</a></button>
    </div>        
    <div class="product-box">
    <img src="smoke-pants.jpg">
    <h1>Smoke Pants</h1>
    <h2>1000 rs.</h2>
    <button class="cart"><a href="#">Add To Cart</a></button>
    </div>
 </div>
 </section>
 
 <section id="contact">
<center><h1>CONTACT US</h1></center>
<div class="cont">
<center><p>Name:
    <input type="text"></p>

    <br><br>

    <p>Email:
    <input type="email"></p>

    <br><br>

    <p>Message:
    <textarea></textarea></p>

    <br><br>

    <button>Submit</button>

    <br><br>

    <p>
        Email: <b>blurgoriginals@gmail.com</b><br>
        Phone: <b>+91 1234567890</b>
    </p></center>
</div>
html{
  scroll-behaviour: smooth;
  }
*{
  margin:0;
  padding:0;
  text-decoration: none;
  }
body{
  height: 100vh;
  }
.navbar{
  background-color: black;
  font-family: sans-serif;
  }
.navdiv{
  display: flex;
  align-items: center;
  justify-content: space-between;
  box-shadow: 0px 2px 10px rgba(0,0,0,0.8);
  position: sticky;
  top: 0;
  z-index: 100;
  height: 60px;
  }
.logo img{
  width: 100px;
  height:50px;
  margin-left: 20px;
  
  }
.navdiv ul{
  list-style: none;
  display: flex;
  align-items: center;
  margin-right: 25px;
  gap: 40px;  
  }
.navdiv ul li a{
  color: grey;
  font-size: 20px;
  font-weight: bold;
  padding: px;
  }
.navdiv ul li a:hover{
  color: white;
  }
.main-box{
  display: flex; 
  }
.main-text{
  margin-left: 100px;
  margin-top: 100px;
  text-align: left;
  line-height: 1.6;
  }
.main-text h1{
  font-size: 45px;
  font-weight: 600;
  }
.main-text h2{
  font-size: 40px;
  font-weight: 500;
  color: #122126;
  }
.main-text p{
  font-size: 20px;
  font-weight: 500;
  margin-left: 3px;
  color: grey;
  } 
.main-img img{
  height: 90%
  }       
.shop{
  margin-top: 15px;
  cursor: pointer; 
  border: 2px solid black;
  border-radius: 20px;
  padding: 6px;
  background-color: white;  
  box-shadow: 0px 2px 10px rgba(0,0,0,0.08); 
  transition: 0.3s ease transform 0.3s ease;  
  }
.shop a{
  font-size: 22px;
  color: black;
  font-weight: 500;
  }
.shop:hover{
  box-shadow: 0px 2px 10px rgba(0,0,0,0.6);
  background-color: grey;
  transform: 0.3s ease;
  }
#products{
  align-items: center;
  }
.header h1{
  font-size: 35px;
  font-weight: 600;
  text-decoration: underline;
  margin-top: 100px;
  }  
.box{
  align-items: center;
  display: flex;
  gap: 30px;
  border: 1px solid black;
  border-radius: 15px;
  box-shadow: 0px 2px 10px rgba(0,0,0,0.04);
  margin-left: 50px;
  margin-right: 50px;
  margin-top: 40px;
  padding: 30px;
  }
.product-box{
  align-items: center;
  text-align: center;
  padding: 10px;
  line-height: 1.6;
  border-radius: 20px;
  box-shadow: 0px 2px 10px rgba(0,0,0,0.08);
  transition: transform 0.3s ease,
              box-shadow 0.3s ease;
  }
.product-box:hover{
  transform: translatey(-5px);
  box-shadow: 0px 2px 10px rgba(0,0,0,0.2);  
  }
.product-box img{
  width: 96%;
  border-radius: 20px;
  }
.product-box h1{
  font-size: 25px; 
  }
.product-box h2{
  font-size: 20px;    
  color: black;
  margin-bottom: 10px;
  }
.cart{
  background-color: white;
  border: .5px solid black;
  border-radius: 20px;
  padding: 10px 5%;
  box-shadow: 0px 2px 10px rgba(0,0,0,0.2);
  transition: transform 0.3s ease,
              box-shadow 0.3s ease;
  }
.cart a{
  color: black;
  font-size: 20px;
  font-weight: 550;
  }
.cart:hover{
  transform: translatey(-5px);
  box-shadow: 0px 2px 10px rgba(0,0,0,0.2);
  }
#about{
  scroll-margin-top: 80px;
  }
#contact{
  scroll-margin-top: 80px;
  }      
#about h1{
  align-items: center;
  text-align: center;
  font-size: 35px;
  font-weight: 600;
  margin-top: 60px;
  text-decoration: underline;
  }
.about-box{
  display:flex;
  padding: 20px 10%;
  gap: 30px;
  margin-left: 50px;
  margin-right: 50px;
  }
.about-boxes{
  padding: 10px 10%;
  align-items: center;
  text-align: center;
  border: .5px solid gray;
  box-shadow: 0px 2px 10px rgba(0,0,0,0.09);
  border-radius: 20px;
  margin-top: 60px;
  transition: transform 0.4s ease,
              box-shadow 0.4s ease;
  }
.about-boxes p{
  padding-top: 20px;
  }
.about-boxes:hover{
  transform: translatey(-10px);
  box-shadow:0px 2px 10px rgba(0,0,0,0.3);   
  }
.cont{
  border: .5px solid grey;
  padding: 20px;
  margin-top: 30px;
  margin-left: 50px;
  margin-right: 50px;
  border-radius: 20px;
  }
#contact{
  margin-top: 50px;
  }
#contact h1{
  font-size:35px;
  font-weight: 600;
  text-decoration: underline;
  }
footer{
  height: 100px;
  background-color: black;
  display: flex;
  align-items: center;
  text-align: center;
  margin-top: 100px;
  }
footer p{
  color: white;
  text-align: center;
  margin-left : auto;
  margin-right: auto;
  }
                                          

</section>

<footer>
<p>&copy;2026.BLURGVILLAGE</p>
</footer>
</body>
</html>
[style.css](https://github.com/user-attachments/files/33084209/style.css)

