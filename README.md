# Introduction to Web Development

Course Code: HTTP 5110

Academic Year: 2025-2026

This course will introduce students to the roles and responsibilities of a Web Developer.

# links
https://www.w3schools.com/

# Images
![Web Development Overview](Webdev.jpg)

> **Note**: Understanding the various roles within web development is crucial for successful collaboration in web projects. Be proactive in learning about both front-end and back-end processes.

# Code Example:

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jinal VijayKumar Patel - Site</title>
    <!-- <link rel="stylesheet" href="./Styles/Style.css"> -->
    <style>body {
    padding: 0px;
    margin: 0px;
    font-family: Arial, Helvetica, sans-serif;
    background: #fff;
    color: #000;
    }
#logo img{
        position: absolute;
        margin-top: auto;
        margin-left: auto;
        height: 50px;
        width: 50px;
}
    a:link{
        color:black
        }
a:visited{
        color:rgb(112, 46, 46)
        }
a:hover{
        background-color:rgb(194, 139, 139);
        color:black;
        }
a:active{
        color:beige
        }
#navbar li
        {
        display: inline;
        list-style-type:circle;
        border-left: 1px solid #000;
        line-height: 1.1em;
        margin: 6 .5em 0 -.5em;
        padding: 0 14px; 
        line-height: 1.1em; 
        }
.container {
        margin:10px;
        padding:10px;
        background-color:#ca8080;
        border-width:1px;
        border-color:black;
        border-style:solid;
        clear:both;
        }
.nav {
        margin:10px;
        padding:10px;
        background-color:rgb(229 229 180);
        border-width:1px;
        border-color:black;
        border-style:solid;
        }
.left {
        width:20%;
        margin:10px;
        padding:10px;
        background-color:rgb(229 229 180);
        border-width:1px;
        border-color:black;
        border-style:solid;
        float:left;
        }
        .centre {
        width:47%;
        margin:10px;
        padding:10px;
        background-color:rgb(229 229 180);
        border-width:1px;
        border-color:black;
        border-style:solid;
        float:left;
        }
        .right {
        width:20%;
        margin:10px;
        padding:10px;
        background-color:rgb(229 229 180);
        border-width:1px;
        border-color:black;
        border-style:solid;
        float:right;
        }
        .lower-nav {
        margin:10px;
        padding:10px;
        background-color:rgb(229 229 180);
        border-width:1px;
        border-color:black;
        border-style:solid;
        clear:both;
        }
        .copyrights {
        margin:10px;
        padding:10px;
        background-color:rgb(229 229 180);
        border-width:1px;
        border-color:black;
border-style:solid;
float:none;
clear:both;
}
.deadnav{
        color:#FFF;
        background-color: rgb(109, 89, 89)
        } </style>
</head>
<body>
    <div class="container">
    <div class="nav">
        <span id="logo">
            <img src="./Images/logo.png" alt="Error 404">
        <!-- Jinal Patel -->
        </span>
        <ul id="navbar">
            <li><span class="deadnav">Home</span></li>
            <li><a href="portfolio.html">Portfolio</a></li>
            <li><a href="about.html">About Us</a></li>
            <li><a href="contact.html">Contact</a></li>
            <li><a href="services.html">Services</a></li>
        </ul>
    </div>
    <div class="images">
        <div class="left">left</div>
        <div class="centre">centre</div>
        <div class="right">right</div>
    </div>
    <div class="lower-nav">
        <ul id="navbar">
            <li><span class="deadnav">Home</span></li>
            <li><a href="portfolio.html">Portfolio</a></li>
            <li><a href="about.html">About Us</a></li>
            <li><a href="contact.html">Contact</a></li>
            <li><a href="services.html">Services</a></li>
        </ul>
    </div>
    <div class="copyrights">
        <ul id="navbar">
            <li><a href="copyrights.html">&copy; 2024 Jinal Patel all the copyrights reserved</a></li>
            <li><a href="privacy.html">Privacy</a></li>
            <li><a href="terms.html">Terms Of Use</a></li>
        </ul>
    </div>
    </div>
</body>
</html>