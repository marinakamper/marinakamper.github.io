---
layout: page
title: illustrations
permalink: /illustrations/
order: 2
---


<style>
.button {
  border: none;
  color: white;
  padding: 16px 32px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  margin: 8px 12px;
  transition-duration: 0.4s;
  cursor: pointer;
}

.button2 {
  background-color: white;
  color: black;
  border: 2px solid #555555;
}

.button2:hover {
  background-color: #555555;
  color: white;
}

.container {
  position: relative;
  margin-left: auto;
  margin-right: auto;
  width: 70%;
}


.mySlides{
  height: 400px;
  width:auto;
}

.text-center {
  text-align: center;
}

</style>





My favourite art media are gauche, watercolour and coloured pencils. I also recently starting creating digital drawings using Procreate.

Sketchbook:

<div class = "container">
  <div id="slide-show">
    <img class="mySlides container" src="/assets/illust/sketch01.JPG" />
    <img class="mySlides container" src="/assets/illust/sketch02.JPG" />
    <img class="mySlides container" src="/assets/illust/sketch03.JPG" />
    <img class="mySlides container" src="/assets/illust/sketch04.JPG" />
  <div class = "text-center">  
  <button class="button button2" onclick="plusDivs(-1)">&#10094;</button>
    <button class="button button2" onclick="plusDivs(1)">&#10095;</button>
    </div>
  </div>
  <script>
    var slideIndex = 1;showDivs(slideIndex);
    function plusDivs(n) {showDivs(slideIndex += n);}
    function showDivs(n) {
      var i;
      var x = document.getElementsByClassName("mySlides");
      if (n > x.length) {slideIndex = 1}    
      if (n < 1) {slideIndex = x.length}
      for (i = 0; i < x.length; i++) {x[i].style.display = "none";}
      x[slideIndex-1].style.display = "block";  
    }
  </script>
</div>
