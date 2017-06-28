# dalonso31.github.io
<!DOCTYPE html>
<HTML>
<HEAD>
<link rel="stylesheet" type="text/css" href="style.css">
</HEAD>
  <h1>Daniela Alonso Sanchez</h1>
  <BODY>
  <h2>About me </h2>
  <p>Hi, I am Daniela. Hover these boxes to learn about me.</p>
<ul>
  <div class="dropdown">
    <button class="dropbtn">Biography</button>
    <div class="dropdown-content">
    <p> I was born in Cuba, in the city Havana. I developed an interest for humanities there. Then, I moved to the US, when I was nine. In the US I discorevered an attraction towards STEM fields.</p>
    </div>
  </div>
   <div class="dropdown">
    <button class="dropbtn">Likes and Dislikes</button>
    <div class="dropdown-content">
    <p>I like JUngkook.</p>
    </div>
  </div>
  <div class="dropdown">
    <button class="dropbtn">Fun facts</button>
    <div class=dropdown-content>
    <p>I crack my back a LOT</p>
    </div>
  </div>
  <div class="dropdown">
    <button class="dropbtn">Fav websites</button>
    <div class=dropdown-content>
    <p>I crack my back a LOT</p>
    </div>
  </div>
  <div class="dropdown">
    <button class="dropbtn">Pride Run</button>
    <div class=dropdown-content>
    <p>I crack my back a LOT</p>
    </div>
  </div>
</ul>
    <p class="thirdp">meh</p>
    <p>I am learning how to code this summer.</p>
    <img src="kermit.jpg">
</BODY>
</html>
.thirdp {
  color:#006600
}

/* Dropdown Button */
.dropbtn {
    background-color: #b30047;
    color: white;
    padding: 16px;
    font-size: 16px;
    border: none;
    cursor: pointer;
    align: left;
    display:block;

}

/* The container <div> - needed to position the dropdown content */
.dropdown {
    position: block;
  display: block;

}


.dropdown-content {
  display: none;
   float: right;
   background-color: #f9f9f9;
   min-width: 160px;
   box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
   padding: 12px 16px;
   z-index: 1;
}

/* Change color of dropdown links on hover */
.dropdown-content a:hover {background-color: #f1f1f1}

/* Show the dropdown menu on hover */
.dropdown:hover .dropdown-content {
    display: block;
}

/* Change the background color of the dropdown button when the dropdown content is shown */
.dropdown:hover .dropbtn {
   left: 0;
    background-color: #3e8e41;
}
