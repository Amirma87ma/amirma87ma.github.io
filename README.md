<html lang="en"> 
 <head> 
  <meta charset="UTF-8"> 
  <meta name="viewport" content="width=device-width, initial-scale=1"> 
  <style>
        * {
            box-sizing: border-box;
        }
        body {
            font-family: Arial, Helvetica, sans-serif;
            margin: 0;
            background-color: #ddd;
              -webkit-touch-callout: none;
      -webkit-user-select: none;
      user-select: none;
      margin: 0;
      padding: 0;
        max-height: 100%;
      font-family: 'Roboto', Arial, sans-serif;
      -webkit-font-smoothing: antialiased;
      font-size: 16px;
        }
         


        .header {            background: #E7E7E7;           background: -webkit-gradient(linear, left top, left bottom, from(#666), to(#8886));
            padding: 80px;
            
            text-align: center;
            
            color: white;
        }
        .header h1 {
            font-size: 40px;
        }

        .row {
            display: -ms-flexbox;
            /* IE10 */
            display: flex;
            -ms-flex-wrap: wrap;
            /* IE10 */
            flex-wrap: wrap;
        }
        .a {
            overflow: hidden;
            background-color: #333;
            position: sticky;
            position: -webkit-sticky;
            top: 0;
        }

    }

    .main {
        -ms-flex: 70%;
        /* IE10 */
        flex: 70%;
        background-color: white;
        padding: 20px;
    }
    .fakeimg {
        margin-top: 16px;
        text-align: center;
    
        background: #000000;           background: -webkit-gradient(linear, left top, left bottom, from(#666), to(#555));
        border-radius: 14px;
        background-color: #000000;
        width: 100%;
    height: 450px;
webkit-box-shadow:inset 4px 4px 4px rgba(0,0,0,0.28), 10px 0 rgba(255,255,255,0.42);
box-shadow:inset 4px 4px 4px rgba(0,0,0,0.28), 0 1px 0 rgba(255,255,255,0.42);
box-shadow:inset 4px 4px 6px rgba(,0,0,0.28), 0 1px 0 rgba(255,255,255,0.42);
-moz-box-sizing:border-box;
-webkit-box-sizing:border-box;
box-sizing:border-box;
border-right: solid;
border-bottom: solid;
border-color: gray;
border-width: 1px;
        max-width: 800px;
        margin: auto;
    }
        .fakeimg2 {
        background: #000000;           background: -webkit-gradient(linear, left top, left bottom, from(#666), to(#222));
        border-radius: 14px;
        background-color: #000000;
        width: 100%;
    height: 430px;
webkit-box-shadow:inset 10px 20px 10px rgba(0,0,0,0.28), 10px 0 rgba(255,255,255,0.42);
box-shadow:inset 10px 10px 10px rgba(0,0,0,0.28), 0 1px 0 rgba(255,255,255,0.42);
box-shadow:inset 5px 5px 6px rgba(0,0,0,0.28), 0 1px 0 rgba(255,255,255,0.42);
-moz-box-sizing:border-box;
-webkit-box-sizing:border-box;
box-sizing:border-box;
border-right: solid;
border-bottom: solid;
border-color: gray;
border-width: 1px;
        max-width: 800px;
        margin: auto;
    }
    
        

    

    * {
        box-sizing: border-box;
    }
   
 
/* just to remove default margins and paddings, kinda make everything looks better */
*{
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  font-family: 'Roboto', sans-serif;
}
  
/* the container just aligns the card at the center of the body */
.container{
  perspective: 1000px;
  position: absolute;
 
  left: 50%;
  transform: translate(-50%, -50%);
}

.card{
  transform-style: preserve-3d;
  width: 350px;
  background: white;
  box-shadow: 0 0 3px grey;
  border-radius: 5px;
  margin: auto;
  cursor: pointr;
}

.inner-card{
  padding: 15px;
  width: 100%;
  height: 100%;
  border-radius: 5px;
  background: dodgerblue;
  transition: 0.5s;
}
.card:hover > .inner-card{
  animation: clip 1.5s;
}
    

@keyframes clip{
  0%{
    clip-path: circle(10% at 0px 0px);
  }
  100%{
    clip-path: circle(100%);
  }
}


    .mybutton {
          
        background-color: #2196F3;
         
      border-radius: 10px;
      box-shadow: 0 2px 5px 0 rgba(0, 0, 0, 0.16), 0 2px 5px 0 rgba(0, 0, 0, 0.23);
      box-sizing: border-box;
      -webkit-flex-basis: 100%;
      -ms-flex-preferred-size: 100%;
      flex-basis: 100%;
      max-width: 600px;
      max-height: 4px;
      margin: 0 auto;
      overflow: hidden;
      padding: 20px;
      position: relative;
        font-size: 16px;
        border-radius: 15px;
      font-weight: 500;
      line-height: 19px;
      width: 80%;
      height: 4%;
    
     
     
    }
    

    .mybutton:hover {
        background-color: #033A17;
        border-radius: 15px;
        border-top-style: solid;
        border-top-color: #033A17;
        border-bottom-style: solid;
        border-bottom-color: #033A17;
        animation-name: e;
        animation-duration: 4s;
        
    }
@keyframes e {
  from {background-color: red;}
  to {background-color: #033A17 ;}
  from {border-top-color: #F55050;}
  to {border-top-color: #033A17;}
  from {border-bottom-color: red;}
  to {border-bottom-color: #033A17;}
}


    .green {
        background-color: #4CAF50;
    border-top-style: solid;
        border-top-color: #4CAF50;
        border-bottom-style: solid;
        border-bottom-color: green;

    }
    .gray {
        background-color: #e09604;
        border-top-style: solid;
        border-top-color: #e09604;
        border-bottom-style: solid;
        border-bottom-color: #CC6600;
        
    }
    .footer {
    
height: 100%;
  box-shadow: 0px -2px -2px #000;
        padding: 20px;
        padding-bottom: 1000px;
        text-align: center;
        background: #8886;
    }
@media screen and (max-width: 500px) {
        .row {
            flex-direction: column;
        }
    }
@media screen and (max-width: 400px) {
        .navbar a {
            float: none;
            width: 100%;
        }
    }


    body {
        color: white;
    }
</style> 
 </head> 
 <body> 
  <div class="navbr"> 
   <p style="text-align:right"></p> 
  </div> 
  <div class="header"> 
   <div class="container"> 
    <div class="card" id="card" onmouseover="moving(event)" onmouseout="stopmoving()"> 
     <div class="inner-card"> 
      <h3>amir_ma</h3> 
     </div> 
    </div> 
   </div> 
   <script>
var card = document.getElementById('card');
  
function moving(event){
    let xaxis = (window.innerWidth / 2 - event.pageX) / 10;
    let yaxis = (window.innerHeight / 2 - event.pageY) / 10;
    card.style.transform = 'rotateY('+xaxis+'deg) rotateX('+yaxis+'deg)';
}

function stopmoving(){
    card.style.transform = "rotateY(0deg) rotateX(0deg)";
    card.style.transition = "0.5s";
}
</script> 
   <p style="font-family:arial; color:#FF0000;">welcome</p> 
  </div> 
  <div class="footer" style="font-size:20px"> 
   <br> 
   <div class="fakeimg"> 
    <br> 
    <br> 
    <p> hello,....</p> 
    <br> 
    <h3>servers</h3>
    <div class="mybutton green"> <a herf="https://discord.gg/TcvA7tU8ue">-</a> 
    </div> 
    <br> 
    <br> 
    <div class="mybutton gray"> <a herf="https://discord.gg/vxVWBxZ3Rz">-</a> 
    </div> 
    <br> 
    <br> 
    <br> 
    <br> 
    <br> 
    <br> 
    <p>‌</p> 
    <br> 
    <br> 
    <br> 
    <p>‌</p> 
    <br> 
    <br> 
    <br> 
    <br> 
   </div> 
   <div class="fakeimg2" style="margin-top:28px"> 
    <br> 
    <h3>customize</h3> 
    <wbr> 
    <h4>background Color</h4> 
    <input id="color" type="color" value="fff"> 
    <br> 
    <script>
setInterval(() => {
let color = document.getElementById('color');
let colorValue = color.value;
document.body.style.backgroundColor = colorValue;
}, 100);
</script> 
    <br> 
    <br> 
    <br> 
    <p>‌</p> 
    <br> 
    <br> 
    <br> 
    <p>‌</p> 
   </div> 
  </div> 
 </body>
</html>
