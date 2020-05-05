# hotel-website
//overview
<!doctype html>
<html>
<head>
<title>LOGIN PAGE</title>
<link href="overview.css" rel="stylesheet" type="text/css"/>

</head>
<body>

<div id="logo" style="height:150px;width:180px;float:left;"><a href="main.html">
<p id="styl">HOTEL HARIKA</p>
</div>

<div id="header">
<ul>
<li> <a href="main.html">HOME</a> </li>
<li> <a href="booking.html">BOOKING </a></li>
<li style="width:130px;"><a href="restaurant.html">RESTURANT</a> </li>
<li style="width:175px;"><a href="call_accounting.html"> CALL ACOUNTING </a></li>
<li style="width:170px;"><a href="health.html"> HEALTH/SPA </a></li>
<li style="width:130px;"><a href="overview.html">OVERVIEW </a></li>
</ul>
</div>

<div id= BACKGROUND>
 <h1 id="borderimg">| ****HAPPY TO SERVE YOU**** |</h1>

 <div id="contact">
    <div id="contact_box">
     <h1><u>| *CONTACT US*|</h1>

    <table id="number" border="3" cellspacing="5" cellpadding="5" >
     <tr></tr><br>
      <tr>
      <td>HARIKA M.D</td>
      <td>M.No: 9875462100</td>
      </tr>
      <tr>
      <td>MANAGER</td>
      <td>M.No: 9990462122</td>
      </tr>
      <tr>
      <td>BOOKING</td>
      <td>M.No: 8702569874</td>
      </tr>
      <tr>
      <td>QUERIES</td>
      <td>M.No: 9865748123</td>
      </tr>
       
    </table>
    </div>

   <div class="content">
   
  <img class="mySlides " src="over1.jpg" >
  <img class="mySlides " src="over2.jpg" >
  <img class="mySlides " src="over3.jpg" >
  <img class="mySlides " src="over4.jpg"  >
  <img class="mySlides " src="over5.jpg" >
  <img class="mySlides " src="pic17.jpg"  >
  <img class="mySlides " src="AC2.jpg"  >

   </div>
 <div id="bottom">
   <h4>Follow Us On :: <h4>
    <a href="#"><img src="fb.jpg" height="5%" width="5%"></a>
    <a href="#"><img src="google.jpg" height="5%" width="5%"></a>
    <a href="#"><img src="tw.jpg" height="5%" width="5%"></a>
   <a href="#"><img src="yoo.png" height="5%" width="5%"></a>
 </div>  

</div>

</div>
<script>

var myIndex = 0;
carousel();
   
function carousel()
 {
    var i;
    var x = document.getElementsByClassName("mySlides");
    for (i = 0; i < x.length; i++) {
       x[i].style.display = "none";  
    }
    myIndex++;
    if (myIndex > x.length) {myIndex = 1}    
    x[myIndex-1].style.display = "block";  
    setTimeout(carousel, 1000);    
  }

</script>


</body>
</html>


//overview.css
#header
{
   background-image:url("BG12.JPG"); background-repeat:no-repeat;background-size:cover;
  margin-top:-5px; margin-right:0px;  padding:5px;   margin-left:-7px;
  height:100px; width:1332px;
  text-align:center; border-style:none;
  }


#header ul{list-style-type:none;}
#header ul li
{
        border:5px solid; font-size:18px;
        float:left; background-color:pink;
        width:110px;     
        height:50px;   
        text-align:center;
        margin:0px 10px 0px 10px;
        font-weight:bold;
        line-height:50px;
        border-radius:50px;
        transition-property:all;
        transition-duration:0.3s;
        transition-timing-function:linear;
}
#header li{
        text-decoration:none;
        color:gold;
        }

#header li:hover{
                      background-color:#00FF7F;
                        color:gold;
                        }

#header li:active{background-color:#00FFFF;}
img.round{ border-radius:50px; }
#styl{
      background-color: pink; 
      font-size: 13px; font-weight: bold; 
      height:62px; margin-top: 20px; 
       margin-left: 15px;
       margin-bottom: 20px;
        margin-right: 20px;
         border:6px solid gold; 
        width:160px; text-align: center; 
        border-radius: 50px; 
        padding:18px; box-sizing: border-box;
    }
#BACKGROUND
{
    background-image:url("LOG4.jpg"); background-repeat:no-repeat;
  background-size:cover;
  background-attachment: fixed;
   float:left;
   height:1200px;
   width :1342px;
   margin-top:-40px;
    color: rgb(218, 241, 8);
   text-align:center;
font-size:30px; font-family:algerian;
}

#borderimg
{
    height:70px; width:1000px;
    border: 30px solid transparent;
     padding: 10px;
    -webkit-border-image: url(BG6.jpg) 20% round;
    -o-border-image: url(BG6.jpg) 20% round;
    border-image: url(BG6.jpg) 20% round;
    margin-bottom:200px;  margin-top:200px; 
    margin-left:150px;
}

#contact
{
    height:630px; width:1320px; background-color:white;margin-top:-    700px; margin-left:10px;opacity:0.9;
}
#contact_box
{
  height:400px; width:600px;border-radius:30px; 
   border:10px orange;   margin-top:30px; margin-left:20px;
   border-style:groove;font-size:25px;
}
#number
{   float:left
    height:400px;width:500px; margin-left:50px;margin-top:-20px;
   border:5px silver; font-size:25px;color:black;
}

.content
{
    background-image: url("HS6");
    height:390px;   float:left;
    width:620px;
    border: 15px orange;
    border-style:groove;
    text-align:center;
    float:left;
    margin-left:650px;margin-top:-420px;
    opacity:1.0;
    border-radius:20px;
 }
.mySlides
{
    height:100%;
    width:100%;
}
 
#bottom
{
   height:100px; width:1200px; border_radius:20px; float:left;
}

#number td:hover{background-color:green;}
#bottom a:hover{background-color:yellow;}

//booking

<html>
<head>
<title>BOOKING PAGE</title>
<link href="booking.css" rel="stylesheet" type="text/css"/>


</head>
<body>
  <div id="logo" style="height:150px;width:180px;float:left;"><a href="main.html">
   <p id="styl">HOTEL HARIKA</p>
    </div>
    
    <div id="header">
    <ul>
    <li> <a href="main.html">HOME</a> </li>
    <li> <a href="booking.html"> BOOKING </a></li>
    <li style="width:130px;"><a href="restaurant.html"> RESTAURANT</a> </li>
    <li style="width:175px;"><a href="call_accounting.html"> CALL ACOUNTING </a></li>
    <li style="width:170px;"><a href="health.html"> HEALTH/SPA </a> </li>
    <li style="width:130px;"><a href="overview.html">OVERVIEW </a></li>
    
    
    </ul>
    </div>

<div id= BACKGROUND>
<h1 id="borderimg">WELCOME TO BOOKING PAGE</h1>

  

  <div id="BOOKINGBOX">
 <form>

<table border="0" cellspacing="5" cellpadding="5" >
<tr></tr><br>
 <tr>
 <th >NAME :: </th>
 <td bgcolor="gold"><input type="text"  id="room" name="NAME1" placeholder="Enter Full Name"  required> </td>
 </tr>
<tr></tr>
<tr></tr>
 <tr>
 <th>EMAIL ::</th>
 <td bgcolor="gold"><input type="email" name ="email" id="email" placeholder="Enter Email" required></td>
 </tr>
<tr></tr>
<tr></tr>

<tr>
 <th>Mobile No. ::</th>
 <td bgcolor="gold"><input type="number" name ="text" id="room"  placeholder="98xxxxxxxx" required></td>
 </tr>
<tr></tr>
<tr></tr>

 <tr>
 <th >Check in:: </th>
 <td bgcolor="gold"><input type="date" id="room"  name="in" required> </td>
 </tr>
<tr></tr>
<tr></tr>
 <tr>
 <th>Check Out::</th>
 <td bgcolor="gold"><input type="date" id="room"  name ="out" required ></td>
 </tr>
<tr></tr>
<tr></tr>

<tr>
  <th>Room Type::</th>
  <td id="roomtype" bgcolor="gold"><select name ="dropdown" required >
  <option></option>
  <option>A/C</option>
  <option> Non A/C</option></select>
  <select name ="drpodown1" required>
  <option></option>
  <option >Single</option>
  <option >Double</option>
  <option >Three</option>
  </td>
  </tr>
 
  <tr><th></th>
<td><a href="payment.html"><input type="submit" id="sub"  value="BOOK" ></a> &nbsp&nbsp&nbsp&nbsp
<input type ="reset" id="sub" value="RESET" onclick="alert('Reset sucessfully enter again!!!')" ></td>
</tr>
<tr> </tr>

 </form>
 </table>
  </div>


<div id="slide_name1">
 <h1 style="margin-top:15px;"> AC ROOMS</h1>
<div>  

<div id="slide_name2">
 <h1 style="margin-top:15px;"> NON-AC ROOMS</h1>
</div>  


</div>
</body>
</html>

//booking.css
#header
{
   background-image:url("NBG1.jpg"); background-repeat:no-repeat;background-size:cover;
  margin-top:-5px; margin-right:0px;  padding:5px;   margin-left:0px;
  height:100px; width:1332px;
  text-align:center; border-style:none;
  }
 
#header ul{list-style-type:none;}
#header ul li
{
        border:5px solid; font-size:18px;
        float:left; background-color:pink;
        width:110px;     
	height:50px;   
	text-align:center;
	margin:0px 10px 0px 10px;
        font-weight:bold;
	line-height:50px;
	border-radius:50px;
	transition-property:all;
	transition-duration:0.3s;
	transition-timing-function:linear;
}
#header li{
	text-decoration:none;
	color:gold;
	}

#header li:hover{
		      background-color:#00FF7F;
			color:gold;
			}

#header li:active{background-color:#00FFFF;}
img.round{ border-radius:50px; }
#BACKGROUND
{
    background-image:url(blur.jpg); background-repeat:no-repeat;
  background-size:cover;
  background-attachment: fixed;
   float:left;
   height:800px;
   width :1340px;
   margin-top:-40px;
    color: rgb(100,10,5);
   text-align:center;
font-size:30px; font-family:algerian;
}
#BOOKINGBOX
{
   height:500px; width:400px;
   background-image: url("NBG1.jpg");
   background-repeat:no-repeat; background-size:cover;
   background-position: center;
   opacity:0.8;
    text-align:center;   
   margin-left:480px;     
   border-radius:30px;
   margin-top:20px;
   color:#00FF7F;
  font-size:28px;
  font-family:impact;
  
}

#borderimg
{
    height:80px; width:1220px;
    border: 30px solid transparent;
     padding: 10px;
    -webkit-border-image: url(MBG1.jpg) 20% round;
    -o-border-image: url(MBG1.jpg) 20% round;
    border-image: url(MBG1.jpg) 20% round;
    margin-bottom:30px;  margin-top:20px; 
    margin-left:20px;
   color:rgb(36, 6, 107);
}
#styl{
  background-color: pink; 
  font-size: 13px; font-weight: bold; 
  height:62px; margin-top: 20px; 
   margin-left: 15px;
   margin-bottom: 20px;
    margin-right: 20px;
     border:6px solid gold; 
    width:160px; text-align: center; 
    border-radius: 50px; 
    padding:18px; box-sizing: border-box;
}




 #slide_name1
 {
     width:390px;  height:60px;
     border:20px solid rgb(139,10,4);
     border-style:groove;
    text-align:center;
    float:left;
    font-size:20px;
   font-family:impact;
   color:rgb(6, 12, 99);
   margin-left:20px; margin-top:-270px;     
 }
 
 #slide_name2
 {
     width:370px;  height:60px;
     border:20px solid rgb(139, 10, 4);
     border-style:ridge;
    text-align:center;
    float:right;
    font-size:20px;
   font-family:impact;
   color:rgb(6, 12, 99);
   margin-right:-895px; margin-top:-300px;     
 }
 
 //restaurent
 <!doctype html>
<html>
<head>
<title>RESTAURANT PAGE</title>
<link href="restaurant.css" rel="stylesheet" type="text/css"/>

<script>
   
    function f1( ){ document.getElementById("borderimg").style.color="white";} 
    function f2( ){ document.getElementById("borderimg").style.color="gold"; }
    function f3( ){ document.getElementById("about1").style.color="blue";} 
    function f4( ){ document.getElementById("about1").style.color="orange"; }
    function f5( ){ document.getElementById("hotel").style.color="gold";} 
    function f6( ){ document.getElementById("hotel").style.color="blue"; }
    
	function ff( ){ document.getElementById("note").innerHTML="...";}
	function ff1( ){ document.getElementById("note").innerHTML="BUY 2 FOR Rs.400";} 
	function ff2( ){ document.getElementById("note").innerHTML="| ***BUY COMBO FOR Rs.450" ; }
    function ff3( ){ document.getElementById("note").innerHTML="| *** BUY 2 FOR Rs.550" ;} 
	function ff4( ){ document.getElementById("note").innerHTML="| *** BUY FOR Rs.400" ;}
    function ff5( ){ document.getElementById("note").innerHTML="| *** BUY FOR Rs.600" ;}
	function ff6( ){ document.getElementById("note").innerHTML="| *** BUY FOR Rs.450" ;}
    function ff7( ){ document.getElementById("note").innerHTML="| *** BUY FOR Rs.550";}
	function ff8( ){ document.getElementById("note").innerHTML="| *** BUY FOR Rs.400" ; }
   
  </script>


</head>
<body>

<div id="logo" style="height:150px;width:180px;float:left;"><a href="main.html">
  <p id="styl">HOTEL HARIKA</p>
</div>

<div id="header">
<ul>
<li> <a href="main.html">HOME</a> </li>
<li> <a href="booking.html">BOOKING </a></li>
<li style="width:130px;"><a href="restaurant.html">RESTAURANT</a> </li>
<li style="width:175px;"><a href="call_accounting.html"> CALL ACOUNTING </a></li>
<li style="width:170px;"><a href="health.html"> HEALTH/SPA </a></li>
<li style="width:130px;"><a href="overview.html">OVERVIEW </a></li>
<li><a href="login.html">LOGIN</a></li>

</ul>
</div>

<div id= BACKGROUND>
<h1 id="borderimg" onmouseover="f1()" onmouseout="f2()">WELCOME TO OUR<br>RESTAURANT<br></h1>
       <h3 style="margin-right:10px;margin-top:370px;" id="BEST">" Best In The City " </h3>


   <div id="ABOUT_US">
       <div id="about"><h2 style="font-family:algerian;color:orange;" id="about1" onmouseover="f3()"  onmouseout="f4()">"ABOUT US"</h2>
        <h4> Restaurant is a place for simplicity with Elegance. Good food, good beer, and good service. Simple is the name of the game, and we�re good at finding it in all the right places, even in your dining experience.
		We�re the group from <b id="hotel" onmouseover="f5()"  onmouseout="f6()">'HOTEL HARIKA'</b>... who make simply AWSOME food possible. Come join us and see what simplicity tastes like.</h4>
          <div id="IMG">
              <img src="kabob.jpg" id="img1" height="100%" width="100%">
              <img src="radish.jpg" id="img1" height="100%" width="100%">
              <img src="r9.jpg" id="img1" height="100%" width="100%">
              <img src="limes.jpg" id="img1" height="100%" width="100%">
          </div>
        </div>
    </div>

 <div id="PRICE">
    <div id="price_tag">
  <h1 style="margin-top:140px;font-size:70px;"><u id="p_id" onmouseover="f7()" onmouseout="f8()">"GREAT AFFORDABLE PRICE"</u></h1>
  <h2 style="color:purple;margin-left:500px;margin-top:350px;font-size:50px" onmouseover="f7()" onmouseout="f8()">With Attractive Combo Offers!</h2>
    </div>
 </div>
 
  
  <div id="price_menu">
   
    <div id="menu1">
        <img src="food5.jpg" id="menu_img" height="80%" width="100%" onmouseover="ff1()" onmouseout="ff()" >
        <h5 class="NAME"><u>Burger king:Rs.200/-</h5>
    </div>   
	
    <div id="menu1">
        <img src="f4.jpg" id="menu_img" height="80%" width="100%" onmouseover="ff2()" onmouseout="ff()">
        <h5 class="NAME"><u>Mutton Biryani:Rs.300/-</h5>
    </div>  

   <div id="menu1">
        <img src="food2.jpg" id="menu_img" height="80%" width="100%" onmouseover="ff3()" onmouseout="ff()">
        <h5 class="NAME"><u>Mexican Fries:Rs.380/-</h5>
    </div>  

    <div id="menu1">
        <img src="food3.jpg" id="menu_img" height="80%" width="100%" onmouseover="ff4()" onmouseout="ff()">
        <h5 class="NAME"><u>Delicios Delight:Rs.400/-</h5>
    </div>
 
    <div id="menu2">
        <img src="food4.jpg" id="menu_img" height="80%" width="100%" onmouseover="ff5()" onmouseout="ff()">
        <h5 class="NAME"><u>Non-Veg Combo:Rs.550/-</h5>
    </div>  
    <div id="menu2">
        <img src="food8.jpg" id="menu_img" height="80%" width="100%" onmouseover="ff6()" onmouseout="ff()">
        <h5 class="NAME"><u>Chicken Wings:Rs.450/-</h5>
    </div>  
    <div id="menu2">
        <img src="kabob.jpg" id="menu_img" height="80%" width="100%" onmouseover="ff7()" onmouseout="ff()">
        <h5 class="NAME"><u>Afghani Kabab:Rs.550/-</h5>
    </div>  
    <div id="menu2">
        <img src="s2.jpg" id="menu_img" height="80%" width="100%" onmouseover="ff8()" onmouseout="ff()">
        <h5 class="NAME"><u>Kadhi Pakoda:Rs.250/-</h5>
     </div>  
      
	  <p style="color:blue;font-size:25px bold; margin-top:5px; float:left; margin-left:5px; font-family:calibri;" id="note"> </p>
	  
   </div>

   <div id="DISH">
    <div id="dish_tag">
  <h1 style="margin-top:0px;font-size:80px;">"OUR <u>FEATURED</u> DISHES <u>MENU"</h1>
    </div>
  </div>
  
    <div id="dish1">
      <div id="dish1_det">
      <h2 style="color:purple;font-family:algerian;">*Have A Look<br>On Our Dishes* ::</h2>
      <h4>Each food is handmade at the crack of dawn, using only the simplest of ingredients to bring out
         smells and flavors that beckon the whole block. Stop by anytime and experience simplicity at its finest.</h4>
        </div>
 
        <div class="content">
   
       <img class="mySlides " src="slider1.jpg" >
       <img class="mySlides " src="slider2.jpg" >
       <img class="mySlides " src="slider3.jpg" >
       <img class="mySlides " src="food1.jpg" >
       <img class="mySlides " src="food6.jpg" >

       </div>
      
     </div>

    <div id="SERVICE">
    <div id="service_tag">
   <h1 style="margin-top:0px;font-size:80px;color:gold">"ENJOY OUR    <u>*SERVICE*</u>ANY TIME<h1>           
      <h2 style="color:black;font-size:60px;"><u>With ROOM SERVICE Available also!!!</h2>
    </div>
  </div> 
   

 </div>
</div>  

<script>
var myIndex = 0;
carousel();         
function carousel()
 {
    var i;
    var x = document.getElementsByClassName("mySlides");
    for (i = 0; i < x.length; i++) {
       x[i].style.display = "none";  
    }
    myIndex++;
    if (myIndex > x.length) {myIndex = 1}    
    x[myIndex-1].style.display = "block";  
    setTimeout(carousel, 1000);    
  }
</script>

</body>
</html>

//restaurent.css
#header
{
   background-image:url("BG19.jpg"); background-repeat:no-repeat;background-size:cover;
  margin-top:-5px; margin-right:0px;  padding:5px;   margin-left:0px;
  height:100px; width:1332px;
  text-align:center; border-style:none;
  }
 
#header ul{list-style-type:none;}
#header ul li
{
        border:5px solid; font-size:18px;
        float:left; background-color:pink;
        width:110px;     
	height:50px;   
	text-align:center;
	margin:0px 10px 0px 10px;
        font-weight:bold;
	line-height:50px;
	border-radius:50px;
	transition-property:all;
	transition-duration:0.3s;
	transition-timing-function:linear;
}
#header li{
	text-decoration:none;
	color:gold;
	}

#header li:hover{
		      background-color:#00FF7F;
			color:gold;
			}

#header li:active{background-color:#00FFFF;}
img.round{ border-radius:50px; }
#styl{
  background-color: pink; 
  font-size: 13px; font-weight: bold; 
  height:62px; margin-top: 20px; 
   margin-left: 15px;
   margin-bottom: 20px;
    margin-right: 20px;
     border:6px solid gold; 
    width:160px; text-align: center; 
    border-radius: 50px; 
    padding:18px; box-sizing: border-box;
}
#BACKGROUND
{
    background-image:url("RBG1.jpg"); background-repeat:no-repeat;
  background-size:cover;  background-attachment: fixed;
  
   float:left;
   height:1150px;
   width :1342px;
   margin-top:-40px;
    color: yellow;
   text-align:center;
  font-size:30px; font-family:algerian;
}


#borderimg
{
    height:150px; width:600px; float:left;
    border: 30px solid transparent;
     padding: 10px;
    -webkit-border-image: url(BG23.jpg) 20% round;
    -o-border-image: url(BG23.jpg) 20% round;
    border-image: url(BG23.jpg) 20% round;
    margin-bottom:30px;  margin-top:100px; 
    margin-left:300px;    
}
#BEST{
        position:relative;
        animation: mymoves 12s infinite;margin-bottom:100px;
}

 @keyframes mymoves 
  {  
     0%  {left: 0px;}
     25% {left:500px;color:orange;}
     75% {left:-600px;color:white;}
     100%{left: 0px; color:gold;}
   }

#ABOUT_US
{
    height:600px; width:1320px; background-color:white;margin-    top:120px; margin-left:10px;
    
 }

#about
{
  height:550px; width:650px; font-family:calibri;color:black;
  text-align:left; margin-top:30px;margin-bottom:80px;float:left;
   margin-left:30px;
}
#IMG{
       height:500px; width:500px;float:right;margin-right:-650px;
        margin-top:-430px;
}
#img1{height:200px; width:200px; border:3px; border-color:blue; margin:5px 5px 5px 5px;}

#PRICE
 {
    height:1350px; width:1342px;margin-top:-40px;
   background-image:url("RBG2.jpg"); background-repeat:no-repeat;
  background-size:cover;  background-attachment: fixed;
 }

#price_tag
{
   height:500px; width:1200px; float:left;margin-left:80px;
   color:white; margin-top:-80px;
}

#price_menu
{
    height:700px; width:1320px; background-color:white;margin-top:-700px; margin-left:10px;
  
}

#menu1
{
   float:left; 
   height:250px; width:280px; margin:20px 20px 25px 10px;
    font-family:algeriun; color:orange;
     border:10px grey;
     border-style:inset;
}
#menu2
{
   float:left; 
   height:250px; width:280px; margin:20px 20px 25px 10px;
    font-family:algeriun; color:orange;
     border:10px grey;
     border-style:inset;
}

.NAME
{
     margin-top:-0px;
 }


#DISH
 {
    height:1350px; width:1342px;margin-top:0px;
   background-image:url("r9.jpg"); background-repeat:no-repeat;
  background-size:cover;  background-attachment: fixed;
 }

#dish_tag
{
   height:500px; width:1200px; float:left;margin-left:80px;
   color:white; margin-top:400px;
}

#dish1
{
    height:500px; width:1320px; background-color:white;margin-top:-700px; margin-left:10px;  
}

#dish1_det
{
   height:400px;   float:left; font-family:calibri;
    width:600px;    color: black; margin-left:0px;margin-top:-200px;
}
.content
{
    height:350px;   float:left;
    width:550px;       margin-top:-200px;
    border: 20px orange;
    border-style:groove;
    text-align:center;
    float:left;
    margin-left:90px;
    opacity:1.0;
    border-radius:20px;
 }
.mySlides
{
    height:100%;
    width:100%;
}


#SERVICE
 {
    height:680px; width:1342px;margin-top:0px;
   background-image:url("pic16.jpg"); background-repeat:no-repeat;
  background-size:cover;  background-attachment: fixed;
 }

#service_tag
{
   height:500px; width:1200px; float:left;margin-left:80px;
   color:white; margin-top:200px;
}

#menu:hover{background-color:none;opacity:0.9;
              border-radius:30px; }
#menu_img:hover{height:100%;}

#img1:hover{background-color:none;opacity:0.9;
             border-radius:40px; }
#borderimg:active{background-color:hotpink;}

.content:hover{height:380px; width:550px; border-radius:60px}


//health
<!doctype html>
<html>
<head>
<title>HEALTH AND SPA</title>
<link href="health.css" rel="stylesheet" type="text/css"/>

 <script>
   
    function f1( ){ document.getElementById("borderimg").style.color="gold"; }
    function f2( ){ document.getElementById("borderimg").style.color="orange"; }
   
  </script>

</head>
<body>

<div id="logo" style="height:150px;width:180px;float:left;"><a href="main.html">
   <p id="styl">HOTEL HARIKA</p>
</div>

<div id="header">
<ul>
<li> <a href="main.html">HOME</a> </li>
<li> <a href="booking.html"> BOOKING </a></li>
<li style="width:130px;"><a href="restaurant.html"> RESTAURANT</a> </li>
<li style="width:175px;"><a href="call_accounting.html"> CALL ACOUNTING </a><</li>
<li style="width:170px;"><a href="health.html"> HEALTH/SPA </a></li>
<li style="width:130px;"><a href="overview.html">OVERVIEW </a></li>
<li><a href="login.html">LOGIN</a></li>

</ul>
</div>


<div id="START">
 <h1 id="borderimg" onmouseover="f1()" onmouseout="f2()" >HOTEL HARIKA'S<br> SPA <br> & <br>GYMNASIUM</h1> 
</div>

<div id="GYM">
   
   <div id="GYMPARA1">
       <h1 style="color:gold;font-family:algerian;margin-top:300px;"><u>"HOTEL HARIKA'S GYMNASIUM</u></h1>
       <h3 style="color:gold;font-family:algerian;margin-top:90px;margin-left:100px;">"YOUR FITNESS IS OUR AIM!!"</h3>
    
   </div>
</div>


<div id="SPA">
   
   <div ID="SPA1">
       <h1 style="color:gold;font-family:algerian;margin-top:300px;margin-left:-100px;"><u>|SPA SERVICES|</u></h1>
       <h3 style="color:gold;font-family:algerian;margin-top:10px;margin-left:300px;">"YOUR HEALTH & BEAUTY IS OUR CONCERN"</h3>
    
   </div>
   <br><br>
   <br><br>
     
   <div id="SPABOX1">
  
      <div id="SPABOXIMG1">
             <img src="SPA10.jpg" height="100%" width="100%";>
	  </div>
  
      

</body>
</html>

//health.css
#header
{
   background-image:url("11.jpg"); background-repeat:no-repeat;background-size:cover;
  margin-top:-5px; margin-right:0px;  padding:5px;   margin-left:0px;
  height:100px; width:1332px;
  text-align:center; border-style:none;
  }
 
#header ul{list-style-type:none;}
#header ul li
{
        border:5px solid; font-size:18px;
        float:left; background-color:pink;
        width:110px;     
	height:50px;   
	text-align:center;
	margin:0px 10px 0px 10px;
        font-weight:bold;
	line-height:50px;
	border-radius:50px;
	transition-property:all;
	transition-duration:0.3s;
	transition-timing-function:linear;
}
#header li{
	text-decoration:none;
	color:gold;
	}

#header li:hover{
		      background-color:#00FF7F;
			color:gold;
			}

#header li:active{background-color:#00FFFF;}
img.round{ border-radius:50px; }
#styl{
  background-color: pink; 
  font-size: 13px; font-weight: bold; 
  height:62px; margin-top: 20px; 
   margin-left: 15px;
   margin-bottom: 20px;
    margin-right: 20px;
     border:6px solid gold; 
    width:160px; text-align: center; 
    border-radius: 50px; 
    padding:18px; box-sizing: border-box;
}
#START
{
    background-image:url(SPAB3.jpg); background-repeat:no-repeat;
   background-size:cover;  background-attachment:fixed; background-position:right; 
   float:left;
   height:1120px;
   width :1342px;
   margin-top:-40px;
    color: rgb(240, 240, 234);
   text-align:center;
  font-size:28px;
}

#borderimg
{
    height:400px; width:400px; float:left;
    border: 30px solid transparent;
     padding: 10px;
    
    border-image: url(BG23.jpg) 50 round;
    margin-bottom:30px;  margin-top:100px; 
    margin-left:800px;    
}

#startBOX
{
    float:left; margin-left:15px;
  height:550px; width:1305px; margin-top:50px;
  background-color:white; color:black;
}
#startBOXIMG
{
    float:right; margin-top:60px;margin-right:10px;
  height:400px; width:500px;border:10px brown;
  border-style:groove;
}
#startBOXPARA
{
    float:left; margin-top:60px; margin-left:10px;
  height:400px; width:730px;border:10px brown;
  border-style:groove;
}
#GYM
{
    background-image:url("HS5.jpg"); background-repeat:no-repeat;
   background-size:cover;  background-attachment: fixed;
  
   float:left;
   height:1500px;
   width :1342px;
   margin-top:-40px;
    color: rgb(66, 3, 3);
   text-align:center;
  font-size:30px;
}

#GYMBOX
{
    float:left; margin-left:15px;
  height:650px; width:1305px; margin-top:300px;
  background-color:white; color:black;
}
#GYMBOXIMG
{
    float:right; margin-top:50px;margin-right:10px;
  height:530px; width:600px;border:10px brown;
  border-style:groove;
}
#GYMBOXPARA
{
    float:left; margin-top:50px; margin-left:10px;
  height:530px; width:600px;border:10px brown;
  border-style:groove; font-size:24px;
}

.content
{
    border: 5px orange;
    border-style:groove;   height:520px; width:590px;
    float:left;
    border-radius:20px;
 }
.mySlides
{
    height:100%;
    width:100%;
}

#SPA
{
    background-image:url("SPA2.jpg"); background-repeat:no-repeat;
   background-size:cover;  background-attachment: fixed;
}
#SPA1{
  float:center;
  height:2300px;
  width :1342px;
  margin-top:0px;
   color: rgb(250, 246, 10);
  text-align:center;
 font-size:40px;
}

#SPABOX1
{
  margin-left:15px;
  height:200px; width:1320px; margin-top:200px;
  background-color:rgb(255, 148, 148); color:black;
  border-radius: 30px;
}
#SPABOXIMG1
{
     margin-top:30px;
  height:475px; width:1300px;border:10px orange;
  border-style:groove;  border-radius:30px;
}
