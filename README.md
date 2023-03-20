
<html>
<head>
    <title></title>
    <meta http-equiv="refresh" content="10">
</head>
<body>
<div id="work">
  <div id="wire"></div>
  <div id="fanos">
    <div id="small-dark_circle">

    </div>
    <div id="half-circle"></div>
    <div id="circle_light">
  
      <div id="top-triangle"></div>
      <div id="box_body">
        <div id="black_col"></div>
       <div id="candel"></div>
      </div>

<div id="final">
        <div id="line"></div>
        <div id="last-triangle"></div>
      </div>
    </div>
  </div>
  <div class="light" id="light_c">
    
    <div class="light">
      <div class="light">
        <div class="light">
        </div>
        </div>
      </div>
    </div>
  </div>
<!--         <h1 style="color:aliceblue; margin-left: 44%; font-size: xxx-large;"  >رمضان كريم</h1> -->

  <div>
  
  </div>


<style>
  * {
padding: 0;
margin: 0;
outline: none;
-webkit-box-sizing: border-box;
-moz-box-sizing: border-box;
box-sizing: border-box;
}

body {

 background-image: url(bg.png);

 
}



#work {
width: 300px;
margin: 0 auto;
position: relative;
top: -20px;
-webkit-animation-name: routate;
-webkit-animation-duration: 4s;
-webkit-animation-iteration-count: infinite;
animation-name: routate;
animation-duration: 5s;
animation-iteration-count: infinite;
}

@-webkit-keyframes routate {
0% {
  -webkit-transform: rotate(7deg);
  -ms-transform: rotate(7deg);
  transform: rotate(7deg);
}
50% {
  -webkit-transform: rotate(-7deg);
  -ms-transform: rotate(-7deg);
  transform: rotate(-7deg);
}
100% {
  -webkit-transform: rotate(7deg);
  -ms-transform: rotate(7deg);
  transform: rotate(7deg);
}
}

@keyframes routate {
0% {
  -webkit-transform: rotate(7deg);
  -ms-transform: rotate(7deg);
  transform: rotate(7deg);
}
50% {
  -webkit-transform: rotate(-7deg);
  -ms-transform: rotate(-7deg);
  transform: rotate(-7deg);
}
100% {
  -webkit-transform: rotate(7deg);
  -ms-transform: rotate(7deg);
  transform: rotate(7deg);
}
}

#work #wire {
margin: 0 auto;
height: 130px;
width: 10px;
background: #7b3bfb;
border: 5px #0c032e solid;
}

#work #light_c {
position: absolute;
z-index: 5;
bottom: 0;
height: 300px;
}

#work .light {
width: 100%;
height: 100%;
padding: 30px;
margin: 0 auto;
background: rgba(255, 155, 0, 0.08);
-webkit-border-radius: 100%;
-moz-border-radius: 100%;
border-radius: 100%;
-webkit-animation-name: flash;
-webkit-animation-duration: 4s;
-webkit-animation-iteration-count: infinite;
animation-name: flash;
animation-duration: 1s;
animation-iteration-count: infinite;
}

@-webkit-keyframes flash {
0% {
  background: rgba(255, 155, 0, 0.08);
}
50% {
  background: rgba(255, 155, 0, 0.04);
}
100% {
  background: rgba(255, 155, 0, 0.08);
}
}

@keyframes flash {
0% {
  background: rgba(255, 155, 0, 0.08);
}
50% {
  background: rgba(255, 155, 0, 0.04);
}
100% {
  background: rgba(255, 155, 0, 0.08);
}
}

#fanos {
height: 380px;
padding: 10px;
margin: 0 auto;
position: relative;
top: -20px;
}

#small-dark_circle {
margin: 0 auto;
width: 30px;
height: 30px;
-webkit-border-radius: 100%;
-moz-border-radius: 100%;
border-radius: 100%;
background: #d9d60c;
border: 5px #0c032e solid;
position: relative;
z-index: 5;
}

#half-circle {
width: 120px;
height: 120px;
position: absolute;
top: 25px;
left: 50%;
-webkit-transform: translateX(-50%);
-ms-transform: translateX(-50%);
transform: translateX(-50%);
z-index: 1;
-webkit-border-radius: 100%;
-moz-border-radius: 100%;
border-radius: 100%;
background: #5b3281;
border: 5px #0c032e solid;
}

#circle_light {
margin: 0 auto;
position: relative;
top: 50px;
z-index: 3;
}

#line {
margin: 0 auto;
width: 200px;
height: 30px;
padding-top: 3px;
background: #261647;
border: 5px #0c032e solid;
overflow: hidden;
text-align: center;
}

#line .ball {
width: 15px;
height: 15px;
margin: auto 5px;
display: inline-block;
-webkit-border-radius: 100%;
-moz-border-radius: 100%;
border-radius: 100%;
background: #40315a;
border: 5px #0c032e solid;
}

#top-triangle {
margin: 0 auto;
width: 210px;
height: 0;
border-left: 25px transparent solid;
border-right: 25px transparent solid;
border-bottom: 30px #0c032e solid;
position: relative;
top: -5px;
}

#top-triangle:after {
content: '';
display: block;
position: absolute;
z-index: 3;
left: 50%;
-webkit-transform: translateX(-50%);
-ms-transform: translateX(-50%);
transform: translateX(-50%);
top: 5px;
width: 155px;
height: 0;
border-left: 15px transparent solid;
border-right: 15px transparent solid;
border-bottom: 20px #40315a solid;
}

#box_body {
width: 170px;
margin: 0 auto;
height: 180px;
background: rgba(255, 255, 255, 0.1);
position: relative;
top: -10px;
z-index: 1;
border: 5px #0c032e solid;
}

#box_body #candel {
height: 60px;
width: 30px;
background: #ffffff;
border: 5px #0c032e solid;
border-bottom: 0;
position: absolute;
z-index: 1;
left: 65px;
bottom: 0;
}

#box_body #candel:after {
content: '';
display: block;
margin: 0 auto;
position: relative;
top: -20px;
width: 10px;
height: 15px;
-webkit-border-radius: 100%;
-moz-border-radius: 100%;
border-radius: 100%;
background: #ff9b00;
border: 5px #0c032e solid;
}

#box_body #black_col {
margin: 0 auto;
width: 90px;
height: 170px;
border-left: 5px #0c032e solid;
border-right: 5px #0c032e solid;
position: relative;
z-index: 2;
background: rgba(255, 255, 255, 0.1);
}

#final {
position: relative;
z-index: 4;
top: -15px;
}

#last-triangle {
margin: 0 auto;
width: 245px;
height: 0;
border-left: 25px transparent solid;
border-right: 25px transparent solid;
border-bottom: 25px #0c032e solid;
position: relative;
top: -5px;
}

#last-triangle:after {
content: '';
display: block;
position: absolute;
z-index: 3;
left: 50%;
-webkit-transform: translateX(-50%);
-ms-transform: translateX(-50%);
transform: translateX(-50%);
top: 5px;
width: 190px;
height: 0;
border-left: 15px transparent solid;
border-right: 15px transparent solid;
border-bottom: 15px #40315a solid;
}
