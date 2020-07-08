<html>
 <head> 
  <meta name="viewport" content="width=device-width,initial-scale=1.0"> 
<style>
 body{
  animation:myanimation 20s infinite;
}
@keyframes myanimation {
     0%{background-color:blue;}
     25%{background-color:yellow;}
     50% {background-color:grey;}
     75% {background-color:orange;}
     50%{background-color:pink;}
}
h1{
  border:3px solid black;
  border-radius:3px;
  text-align:center;
  padding:8px;
  width:100%;
}
img{
  width:320px;
  height:400px;
  display:flex;
  flex-wrap:wrap;
  justify-content:space-around;
  margin-left:auto;
  margin-right:auto;
  padding:20px;
  border:3px solid black;
}
audio{
  border:3px solid black;
  border-radius:10px;
  display:flex;
  flex-wrap:wrap;
  margin:20px;
  margin-left:auto;
  margin-right:auto;
  flex-direction:column;
}
</style>
</head> 
 <body> 
  <h1>Happy Birthday Ram Prakash</h1> 
  <div> 
   <img src="ram.jpg">
   <img src="cake.gif"> 
  </div> 
  <div id="audio"> 
   <audio controls autoplay loop> 
    <source src="Ram.mp3"> 
   </audio> 
  </div> 
 </body>
</html>
