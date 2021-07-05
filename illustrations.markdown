---
layout: page
title: illustrations
permalink: /illustrations/
order: 2
---


<style>

/* STYLES FOR SLIDESHOW */
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



/* STYLES FOR IMAGE GRID*/

.row {
  display: flex;
  flex-wrap: wrap;
  padding: 0 4px;
}

/* Create four equal columns that sits next to each other */

.row {
  display: -ms-flexbox; /* IE10 */
  display: flex;
  -ms-flex-wrap: wrap; /* IE10 */
  flex-wrap: wrap;
  padding: 0 4px;
}

/* Create four equal columns that sits next to each other */
.column {
  -ms-flex: 20%; /* IE10 */
  flex: 32%;
  max-width: 32%;
  padding: 0 4px;
}

.column img {
  margin-top: 8px;
  vertical-align: middle;
  width: 100%;
}

/* Responsive layout - makes a two column-layout instead of four columns */
@media screen and (max-width: 800px) {
  .column {
    -ms-flex: 50%;
    flex: 50%;
    max-width: 50%;
  }
}

/* Responsive layout - makes the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 600px) {
  .column {
    -ms-flex: 100%;
    flex: 100%;
    max-width: 100%;
  }
}


</style>



My favourite art media are gauche, watercolour and coloured pencils. I also recently starting creating digital drawings using Procreate.

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






<div class="row">
  <div class="column">
    <img src="/assets/illust/illustrations/illus1.jpg">
    <img src="/assets/illust/illustrations/illus4.jpg">
    <img src="/assets/illust/illustrations/illus7.jpg">
    <img src="/assets/illust/illustrations/illus10.jpg">
  </div>
  <div class="column">
  <img src="/assets/illust/illustrations/illus2.jpg">
  <img src="/assets/illust/illustrations/illus5.jpg">
  <img src="/assets/illust/illustrations/illus8.jpg">
  <img src="/assets/illust/illustrations/illus11.jpg">
  </div>
  <div class="column">
  <img src="/assets/illust/illustrations/illus3.jpg">
  <img src="/assets/illust/illustrations/illus6.jpg">
  <img src="/assets/illust/illustrations/illus9.jpg">
  <img src="/assets/illust/illustrations/illus12.png">

  </div>
</div>
