<!DOCTYPE html>
<html>
<head>
<title>AnaeleHomePage</title>
</head> <link href="https://fonts.googleapis.com/css?family=Roboto:300,400,500,700" rel="stylesheet">
<body>
    <nav id="headnav">
      <ul>
      <li>  <a href="homepage.html" target="_blank">HOME</a> </li>
      <li> <a href="cv.html" target="_blank">CV</a> </li>
     <li> <a href="projects.html" target="_blank">PROJECTS</a> </li>
     <li> <a href="aboutme.html" target="_blank">CONTACT</a> </li>
      </ul>
        </nav>
    <div class="container">
      <img src="https://www.mockupblast.com/wp-content/uploads/2017/04/Workspace-Computer-Desktop-Mockup.jpg" alt="My background image - desk" width="100%" height="400px">  
</div>
 <h2> ABOUT ME </h2> 
   <p3 id="myblurb"> My name is Daniel Anaele and I'm an enthusiastic first year student at the University of Dundee studying Computer Science.
     I'm currently taking modules in web authouring - HTML 5 and CSS, and Software Development in Java.<br>
      I look forward to working to you!</p3>
     
      <footer> <nav id="footernav"> 
        <ul>
        <li>  <a href="https://www.worldwildlife.org/">DONATIONS</a> </li>
        <!-- Social media icons from W3 Schools for my footer-->
        <link rel="stylesheet"href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
          <li> <a href="#" class="fa fa-facebook"></a> </li>
          <li> <a href="#" class="fa fa-twitter"></a> </li>
          <li> <a href="#" class="fa fa-instagram"></a> </li>
        <img src="https://scontent-lhr3-1.xx.fbcdn.net/v/t1.0-9/14691119_1144765765600280_2056984393371504478_n.jpg?_nc_cat=110&_nc_ht=scontent-lhr3-1.xx&oh=eb1f11cb6865e2f79cab11bff65bdce5&oe=5C76B3D7" alt="Daniel Anaele" style  width="60" height="45">
        </nav></footer>
   </body>
</html> 

#headnav {
  font-family:"roboto", serif;
  background-color: lightgrey;
  
}
ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    overflow: hidden;
    background-color: #333;
}

li {
    float: left;
}

li a {
    display: block;
    color: #e3e3e3;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
}

/* Change the link color to #111 (black) on hover */
li a:hover {
    background-color: black; 
}
li a:active{
    background-color:#4B3F72;
}

#bbox {
    color:#333;
}
h2{
    font-family: "roboto", serif;
    color:#333;
    background-color:#FBFAF9;
   
}
p3{
    color: #332;
      background-color:#FBFAF9
}
#footernav{
    display: block;
    color: navy;
    text-align: center;
    padding: 0px 0px;
    text-decoration: none;
}

    
}



