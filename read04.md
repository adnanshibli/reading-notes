in this text I will talk a little about **html**

### first of all 
**prosses and design**
you must kbow why you are building the site. 
and what the site used for.
the reason of build you own site is so important because it will effect about the shape of your site
then you must know **the reason why the people will visit your site**
after that you must know **what visitors want to achive from visit your site**
what information your visitors need about your site.
and **how often people will visit your site**

## this is the second thing I will talk about.
**the structure**
**html** **html/** all the code written here inside this two tags.
**head** **/head** this tag will be for all links 
**body** **/body** this tag will be for the body of the site
and those are the most important tags in **HTML**
# HTML 5 and css layout
there is many layout like :
* header
* footer
the element of html 5 improved and devloped than html 4 and the verions before
and the tag  
![code tag](https://miro.medium.com/max/2632/0*0G00RG5epDOfvg8m)
HTML5 LAYOUT
<!DOCTYPE html>
<html>
<head>
 <title>HTML5 Layout</title>
 <style type="text/css">
 header, section, footer, aside, nav, article, figure, figcaption {
 display: block;}
 body {
 color: #666666;
 background-color: #f9f8f6;
 background-image: url("images/dark-wood.jpg");
 background-position: center;
 font-family: Georgia, times, serif;
 line-height: 1.4em;
 margin: 0px;}
 .wrapper {
 width: 940px;
 margin: 20px auto 20px auto;
 border: 2px solid #000000;
 background-color: #ffffff;}
 header {
 height: 160px;
 background-image: url(images/header.jpg);}
 h1 {
 text-indent: -9999px;
 width: 940px;
 height: 130px;
 margin: 0px;}
 nav, footer {
 clear: both;
 color: #ffffff;
 background-color: #aeaca8;
 height: 30px;}
 nav ul {
 margin: 0px;
 padding: 5px 0px 5px 30px;}
 nav li {
 display: inline;
 margin-right: 40px;}
 nav li a { 
 color: #ffffff;}
 nav li a:hover, nav li a.current {
 color: #000000;}
 section.courses {
 float: left;
 width: 659px;
 border-right: 1px solid #eeeeee;}
 article {
 clear: both;
 overflow: auto;
 width: 100%;}
 hgroup {
 margin-top:40px;}
 figure {
 float: left;
 width: 290px;
 height: 220px;
 padding: 5px;
 margin: 20px;
 border: 1px solid #eeeeee;}
 figcaption {
 font-size: 90%;
 text-align: left;}
 aside {
 width: 230px;
 float: left;
 padding: 0px 0px 0px 20px;}
 aside section a {
 display: block;
 padding: 10px;
 border-bottom: 1px solid #eeeeee;}
 aside section a:hover {
 color: #985d6a;
 background-color: #efefef;}
 a {
 color: #de6581;
 text-decoration: none;}
 h1, h2, h3 {
 font-weight: normal;}
 h2 { 
447 HTML5 LAYOUT
Example
HTML5 LAYOUT
 margin: 10px 0px 5px 0px;
 padding: 0px;}
 h3 {
 margin: 0px 0px 10px 0px;
 color: #de6581;}
 aside h2 {
 padding: 30px 0px 10px 0px;
 color: #de6581;}
 footer {
 font-size: 80%;
 padding: 7px 0px 0px 20px;}
 </style>
 <!--[if lt IE 9]>
 <script src="http://html5shiv.googlecode.com/svn/trunk/html5.js"></script>
 <![endif]-->
</head>
<body>
 <div class="wrapper">
 <header>
 <h1>Yoko's Kitchen</h1>
 <nav>
 <ul>
 <li><a href="" class="current">home</a></li>
 <li><a href="">classes</a></li>
 <li><a href="">catering</a></li>
 <li><a href="">about</a></li>
 <li><a href="">contact</a></li>
 </ul>
 </nav>
 </header>
 <section class="courses">
 <article>
 <figure>
 <img src="images/bok-choi.jpg" alt="Bok Choi" />
 <figcaption>Bok Choi</figcaption>
 </figure>
 <hgroup>
 <h2>Japanese Vegetarian</h2>
 <h3>Five week course in London</h3>
 </hgroup>
