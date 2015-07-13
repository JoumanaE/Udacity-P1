# Udacity-P1
<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<link rel="stylesheet" src="normalize-css.googlecode.com/svn/trunk/normalize.css">
<link rel="stylesheet" href="1.css">
<link href='http://fonts.googleapis.com/css?family=League+Script' rel='stylesheet' type='text/css'/>
<body background="http://www.brightonunitedmethodistchurch.com/wp-content/uploads/2013/08/chalkboard-background.jpg"> 
  <div class="grid">
    <div class="row">
      <div class="col-11"> <img src="https://s3.amazonaws.com/f.cl.ly/items/060C1H3n0j451a0L2E0X/UdacityIdentity.png"width="75" height="45"> <header> Tileli Rococo   </header> </div>
    </div>
    <div class="row">
      <div class="col-3"></div>
      <div class="col-9"><img src="https://s3.amazonaws.com/f.cl.ly/items/2T1E3I110L3X1B3r3A0l/IMG_1585.JPG"width="950" height="500"></div>
    </div>
     <div class="col-3"></div>
      <div class="col-6"></div>
      <div class="col-3"></div>
    <div class="row">
      <div class="col-4"> <h1> Burgh Stories</h1> <img src="https://s3.amazonaws.com/f.cl.ly/items/001l123z0G0v1T1m1V3r/Burgh.jpg"width="350" height="250"> <p1> A story telling poadcast in Pittsburgh. </p1> </div>
      <div class="col-4"> <h2> Blogging at Warscapes</h2> <img src="https://s3.amazonaws.com/f.cl.ly/items/1A2u312w3r0V263S0o3x/Screen%20Shot%202015-02-17%20at%2011.46.45%20AM.png"width="350" height="250"> <p2> Mainly book reviews </p2> </div>
      <div class="col-4"><h3> Science </h3> <p3> Learning more about science, catching up. Writting about my learning adventures.</p3></div>
    </div
</body>
</html>
* {
    border: 1px transparent !important;
}

* {
    -webkit-box-sizing: border-box;
    -moz-box-sizing: border-box;
    -ms-box-sizing: border-box;
    box-sizing: border-box;
}

@media only screen (max-width: 500px) {
col{display:none ;}
}

.reading-area {width:100%;height: 100%;overflow: auto;
}

.grid {
    margin: 0 auto;
    max-width: 1200px;
    width: 100%;
}

.row {
    width: 100%;
    margin-bottom: 20px;
    display: flex; 
}

.col-1 {
    width: 8.33%;
}

.col-2 {
    width: 16.66%;
}

.col-3 {
    width: 25%;
}

.col-4 {
    width: 33.33%;
}

.col-5 {
    width: 41.66%;
}

.col-6 {
    width: 50%;
}

.col-7 {
    width: 58.33%;
}

.col-8 {
    width: 66.66%;
}

.col-9 {
    width: 75%;
}

.col-10 {
    width: 83.33%;
}

.col-11 {
    width: 91.66%;
}

.col-12 {
    width: 100%;
}

*{font-family: 'League Script', cursive; font-size: 45px; 
color:white;}
*body{
  background: url(http://www.brightonunitedmethodistchurch.com/wp-content/uploads/2013/08/chalkboard-background.jpg);
 }
 
header{float: right; font-size: 45px; display:flex;}
}

.row {
    width: 100%;
    margin-bottom: 20px;
    display: flex;}

h1{background:transparent; float: left; padding: 30px;
padding-bottom: 95px;}

p1{background:transparent; font-size: 35px; color:#C14E4E;
float:left; padding:30px;}

h2{ background:transparent; float: right; padding: 30px;
}

p2{background:transparent; font-size: 35px; float: right;padding:30px;}  

h3{background: transparent;float: center;
color:white; padding: 30px; padding-bottom: 50px;} 

p3{font-size: 35px; color:#A9E9A9;float: center;padding:30px;}

