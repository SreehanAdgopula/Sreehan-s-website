<html>           
<head> 
 <style>
img {
  opacity: 0.5;
}

img:hover {
  opacity: 1.0;
}
</style>
 <style>
h2 {
  text-shadow: 2px 2px 5px red;
}
</style>
 <style>
p {outline-color:blue;}

p.dotted {outline-style: dotted;}
p.dashed {outline-style: dashed;}
p.solid {outline-style: solid;}
p.double {outline-style: double;}
p.groove {outline-style: groove;}
 </style>
 <link rel="icon" type="image/x-icon" href="/Sreehan-s-website/Untitled.jpg">
</head>
<body style= "background-repeat: no-repeat;background-size: 100% 100%;background-attachment: fixed;" background="hd.jpg" text="#ffffff">
<title>Page Title</title>
<b> <div style="border: 4px solid purple"> <h1 align="center"> <span style="color:white"> Hi, I'm SREEHAN!! </span> </h1> </div>
       <span style ="color:white"> <h2> <center> Welcome to my website! </center> </h2> </span> 
 <center> <script>
  function myFunction() {
    document.getElementById("demo").innerHTML = "Hello Friend !!";
  }
  </script>
<p id="demo">Click this button so that I can say something!</p>
<button type="button" onclick="myFunction()">Try it</button> </center>
<hr size="10">
<p class="dotted">  <h2 align="center"> <span style="color:white"> I'm a programmer! </span> </h2><center> <font size ="12">  &#128512; </font> </center>
<h2> <center> <span style="color:white"> I do programming like Python, QBASIC, HTML etc. </span> </center> </h2></p>
<p>
<p class="dashed"> <h2> <center> <span style="color:white"> I play modded games like modded minecraft, my favourite game. </span> </center> </h2>
 <h2> <center> <span style="color:white"> In that game, it mostly looks kind of normal, but when you add Nvidia RTX graphics card to it , Minecraft looks very realistic.(looks how everything is in real life)!! Like in the below image. And just ignore the clouds because they only come in mods  </span> </center> </h2></p>
<center> <img src="realminecraft.jpg" width="500" height="333"> </center>
<p class="solid"> <h2> <center> <span style="color:white"> Second favourite game is Blockman go_Bed-Wars, it is very fun to play as it is available in phones </span> </center> </h2>
<p> <h2> <center> <font color ="white"> My favourite thing is Space!!! There are so many thing and so much to discover it. </font> </center> </h2>
<h2> <center> <span style="color:white"> It is my favourite subject! I know billions of thing that are in space like Gamma Rays, Super and Hyper-novas; Oort Cloud, Space wars, etc! </span> </center> </h2> </p>
 <center> <div class="contact-me">                                                                                                                                       
            <h3 class="contact-title">Do you want to chat to me? Okay, fine, here it is!</h3>
       <p class="contact-message">Email here!</p>
       <a class="btn" href="mailto:asreehan@outlook.com">CONTACT ME</a>
          </div> 
          </center> <p>
</p>
<hr align="center" size="6" width="90%" Color="yellow">              
 <span style="color:white"> <h2> <center> A fun fact!=In another billion years, our Milky Way will collide with the Andromeda Galaxy and form (Andro-Way) or (Milkymeda)!?!? </center> </h2> </span> 
<center> <svg height="200" width="500">
  <defs>
    <linearGradient id="grad1" x1="10%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%"
      style="stop-color:rgb(255,255,0);stop-opacity:1" />
      <stop offset="100%"
      style="stop-color:rgb(255,0,0);stop-opacity:1" />
    </linearGradient>
  </defs>
  <ellipse cx="100" cy="70" rx="85" ry="55" fill="url(#grad1)" />
  <text fill="#ffffff" font-size="35" font-family="Verdana"
        x="50" y="80">THANK YOU</text> </b>
 <center> <h3> Want to chat with me directly? ok then, here it is </h3> </center>
 </svg> </center>
 <style>
* {
  box-sizing: border-box;
}

input[type=text], select, textarea {
  width: 100%;
  padding: 12px;
  border: 1px solid #ccc;
  border-radius: 4px;
  resize: vertical;
}

label {
  padding: 12px 12px 12px 0;
  display: inline-block;
}

input[type=submit] {
  background-color: #4CAF50;
  color: white;
  padding: 12px 20px;
  border: none;
  border-radius: 4px;
  cursor: pointer;
  float: right;
}

input[type=submit]:hover {
  background-color: #45a049;
}

.container {
  border-radius: 5px;
  background-color: #f2f2f2;
  padding: 20px;
}

.col-25 {
  float: left;
  width: 25%;
  margin-top: 6px;
}

.col-75 {
  float: left;
  width: 75%;
  margin-top: 6px;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* Responsive layout - when the screen is less than 600px wide, make the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 600px) {
  .col-25, .col-75, input[type=submit] {
    width: 100%;
    margin-top: 0;
  }
}
</style>
<body>


<div class="container">
  <form action="/action_page.php">
  <div class="row">
    <div class="col-25">
      <label for="fname">First Name</label>
    </div>
    <div class="col-75">
      <input type="text" id="fname" name="firstname" placeholder="Your name..">
    </div>
  </div>
  <div class="row">
    <div class="col-25">
      <label for="lname">Last Name</label>
    </div>
    <div class="col-75">
      <input type="text" id="lname" name="lastname" placeholder="Your last name..">
    </div>
  </div>
  <div class="row">
    <div class="col-25">
      <label for="country">Country</label>
    </div>
    <div class="col-75">
      <select id="country" name="country">
        <option value="australia">Australia</option>
        <option value="canada">Canada</option>
        <option value="usa">USA</option>
      </select>
    </div>
  </div>
  <div class="row">
    <div class="col-25">
      <label for="subject">Subject</label>
    </div>
    <div class="col-75">
      <textarea id="subject" name="subject" placeholder="Write something.." style="height:200px"></textarea>
    </div>
  </div>
  <br>
  <div class="row">
    <input type="sumbit" value="Submit">
  </div>
  </form>
</div>
  <center> <div class="bio link">
 <a class="btn" href="https://bio.link/sreehanadigopula">My Bio link! </a>
  </div>
           </center> 
 
                                                                                                                                   
