# Runrate
Cricket news and live scores website created using ‘cric’ api, that features cricketing news, articles, live scores, players stats and team rankings.<br>
<center><img alt="Runrate" src="https://user-images.githubusercontent.com/54352598/121645205-8be51380-cab1-11eb-8f59-714f3f0911ad.png" /></center>
<br>
<!DOCTYPE html>
<html>
<head>

<style>
  .Marquee-box {
     position: relative;
     display: inline-block;
     width: 500px;
     height: 80px;
     -webkit-perspective: 500px;
             perspective: 500px;
     top: auto;
     left: auto;
     z-index: 100;
  }
  .MyMarquee {
     text-align: center;
     font-weight: bold;
     width: 100%;
     height: 100%;
     font-size: 25px;
     border-radius: 7px;
     border: 20px solid #8C8C8C;
     color: #000000;
     font-family: Impact, Charcoal, sans-serif;
     vertical-align: middle;
     -webkit-box-sizing: border-box;
        -moz-box-sizing: border-box;
             box-sizing: border-box;
     background-color: #FF0000;

     box-shadow: -6px 4px 19px 0px rgba(163, 163, 163, 0.91);
     transform: rotateX(10deg);
     transform-origin: 50% 50% 0px;
  }
  .MyMarquee div {
     display: inline-block;
     vertical-align: middle;
  }
  .MyMarquee a, .MyMarquee img {
     display: inline-block;
     text-decoration: underline;
     color: #000000;
     vertical-align: middle;
  }
</style>
</head>
<body>
 <div class="Marquee-box">
   <marquee class="MyMarquee" id="my_marquee" direction="left" behavior="1" scrollamount="8" onmouseover="this.stop()" onmouseout="this.start()">
     <div>Development work in progress...!</div>
   </marquee>
 </div>



</body>
</html>



