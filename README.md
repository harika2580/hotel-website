
<!DOCTYPE html>
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

