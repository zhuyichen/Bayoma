---
layout: post-database
title: 160524-Brodie Tower
date: 2016-05-24 16:05:00
author: Yichen Zhu
setupno: 7
sensorno: 5
datadl: Available
---

## Test Information
---


<table id="myTable2">
  <tr>
    <td class="header" style="width:15%"><b>Date</b></td>
    <td style="width:35%">{{ page.date | date: "%-d %B %Y" }}</td>
    <td class="header" style="width:50%"><b>Address</b></td>    
  </tr>
  <tr>
    <td class="header"><b>Structure</b></td>
    <td>Brodie Tower, University of Liverpool</td>
    <td rowspan="8">
    <center>
    <p style="font-size: 16px; padding: 12px">University of Liverpool, Brownlow Street, Liverpool, L69 3GQ</p>
    <iframe
src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d1189.2414356949819!2d-2.967125279272631!3d53.4061899038967!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0x142bb768f021cfd9!2sBrodie+Tower!5e0!3m2!1sen!2suk!4v1477754248132" width="500" height="400" frameborder="0" style="border:0" allowfullscreen>
    </iframe>
    </center>
    </td>    
  </tr>
  <tr>
    <td class="header"><b>Type</b></td>
    <td>Reinforced concrete building, 7 storeys</td>  
  </tr>
  <tr>
    <td class="header"><b>Gross Dimensions</b></td>
    <td>25m Wide x 28m Long x 25m High</td>
  </tr>
  <tr>
    <td class="header"><b>Equipment</b></td>
    <td>4 triaxial servo-accelerometers with 24 bit digitizer and individual high precision clock</td>
  </tr>
  <tr>
    <td class="header"><b>No. of Participants</b></td>
    <td>2</td>
  </tr>
  <tr>
    <td class="header"><b>No. of Setups</b></td>
    <td>7 setups, each 15 min at 50 Hz</td>
  </tr>
  <tr>
    <td class="header"><b>Contributer</b></td>
    <td>Yi-Chen Zhu, Yan-Long Xie, Siu-Kui Au (University of Liverpool)</td>
  </tr>
  <tr>
  <td class="header"><b>Data</b></td>
  <td>
    <a href="http://gofile.me/3sin6/wqWI4T0cI"><b>Download</b></a>
  </td>  
  </tr>  
</table>

## Setups and Photos
---
<table id="myTable2">
 <tr>
  <td style="width:50%">
    <center>
     <img src="{{ site.baseurl }}/img/database/16-10-28-brodie/synsetup.gif" style="width: 100%;" >
    </center>
  </td>
  <td style="width:50%">
    <center>

<div class="slideshow-container">
  <div class="mySlides">
    <div class="numbertext">1 / 3</div>
    <img src="{{ site.baseurl }}/img/database/16-10-28-brodie/planview.png" style="width:80%">
    <div class="text"></div>
  </div>

  <div class="mySlides">
    <div class="numbertext">2 / 3</div>
    <img src="{{ site.baseurl }}/img/database/16-10-28-brodie/brodie-tower.jpg" style="width:80%">
  </div>

  <div class="mySlides">
    <div class="numbertext">3 / 3</div>
    <img src="{{ site.baseurl }}/img/database/16-10-28-brodie/sensor.jpg" style="width:80%">
  </div>

  <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
  <a class="next" onclick="plusSlides(1)">&#10095;</a>
</div>
<br>

<div style="text-align:center">
  <span class="dot" onclick="currentSlide(1)"></span>
  <span class="dot" onclick="currentSlide(2)"></span>
  <span class="dot" onclick="currentSlide(3)"></span>
</div>

    </center>
  </td>
 </tr>
</table>



## Data Spectra
--------------------
<table id="myTable2">
 <tr>
  <td>
   <center>
    <img src="{{ site.baseurl }}/img/database/16-10-28-brodie/psd.png" style="width: 500px;" >
    <p><i>Root Power Spectrum of Setup 2 </i></p>
    </center>
  </td>
  <td>
   <center>
    <img src="{{ site.baseurl }}/img/database/16-10-28-brodie/svd.png" style="width: 500px;" >
    <p><i>Root Singular Value Spectrum of Setup 2 </i></p>
    </center>
  </td>
 </tr>
</table>

#### * The initial guess and selected frequency band for each mode are shown in the root singular value spectrum with circles and the symbol '[-]'.

## Identification Results
-----------

<table id="myTable">
  <tr class="header">
    <th style="width:10%;" rowspan="2"><center>Mode</center></th>
    <th style="width:10%;" rowspan="2"><center>Modal s/n Ratio</center></th>
    <th style="width:20%;" colspan="2"><center>Natural Frequency (Hz)</center></th>
    <th style="width:20%;" colspan="2"><center>Damping Ratio (%)</center></th>
    <th style="width:20%;" colspan="2"><center>Modal Force PSD (ug/sqrt(Hz))</center></th>
    <th style="width:10%;" rowspan="2"><center>Track</center></th>
    <th style="width:10%;" rowspan="2"><center>Mode Shape</center></th>
  </tr>
  <tr class="header">
    <th style="width:10%;" ><center>MPV</center></th>
    <th style="width:10%;" ><center>c.o.v.(%)</center></th>
    <th style="width:10%;" ><center>MPV</center></th>
    <th style="width:10%;" ><center>c.o.v.(%)</center></th>
    <th style="width:10%;" ><center>MPV</center></th>
    <th style="width:10%;" ><center>c.o.v.(%)</center></th>
  </tr>

  <tr>
   <td><center> 1 </center></td>
   <td><center> 938 </center></td>
   <td><center> 2.42 </center></td>
   <td><center> 0.21 </center></td>
   <td><center> 0.99 </center></td>
   <td><center> 19.45 </center></td>
   <td><center> 1.07 </center></td>
   <td><center> 44.61 </center></td>
   <td><center><a href="#openModal1-1">View</a></center>
    <div id="openModal1-1" class="modalDialog">
  	<div>
  		<a href="#close" title="Close" class="close">X</a>
      <center>
      <img src="{{ site.baseurl }}/img/database/16-10-28-brodie/trackmode1.png" style="width: 800px;" >
      <p><i>Track Information Mode 1</i></p>
      </center>
  	</div>
   </div>
   </td>
  <td><center><a href="#openModal1-2">View</a></center>
    <div id="openModal1-2" class="modalDialog">
  	<div>
  		<a href="#close" title="Close" class="close">X</a>
      <center>
      <img src="{{ site.baseurl }}/img/database/16-10-28-brodie/idmode1.avi.gif" style="width: 800px;" >
      <p><i>Identification Results Mode 1</i></p>
      </center>
  	</div>
   </div>
   </td>
  </tr>
  <tr>
   <td><center> 2 </center></td>
   <td><center> 1086 </center></td>
   <td><center> 2.71 </center></td>
   <td><center> 0.26 </center></td>
   <td><center> 0.96 </center></td>
   <td><center> 22.38 </center></td>
   <td><center> 1.09 </center></td>
   <td><center> 34.93 </center></td>
   <td><center><a href="#openModal2-1">View</a></center>
    <div id="openModal2-1" class="modalDialog">
  	<div>
  		<a href="#close" title="Close" class="close">X</a>
      <center>
      <img src="{{ site.baseurl }}/img/database/16-10-28-brodie/trackmode2.png" style="width: 800px;" >
      <p><i>Track Information Mode 2</i></p>
      </center>
  	</div>
   </div>
   </td>
  <td><center><a href="#openModal2-2">View</a></center>
    <div id="openModal2-2" class="modalDialog">
  	<div>
  		<a href="#close" title="Close" class="close">X</a>
      <center>
      <img src="{{ site.baseurl }}/img/database/16-10-28-brodie/idmode2.avi.gif" style="width: 800px;" >
      <p><i>Identification Results Mode 2</i></p>
      </center>
  	</div>
   </div>
   </td>
  </tr>
  <tr>
   <td><center> 3 </center></td>
   <td><center> 3516 </center></td>
   <td><center> 3.75 </center></td>
   <td><center> 0.25 </center></td>
   <td><center> 0.82 </center></td>
   <td><center> 11.05 </center></td>
   <td><center> 0.99 </center></td>
   <td><center> 55.77 </center></td>
   <td><center><a href="#openModal3-1">View</a></center>
    <div id="openModal3-1" class="modalDialog">
  	<div>
  		<a href="#close" title="Close" class="close">X</a>
      <center>
      <img src="{{ site.baseurl }}/img/database/16-10-28-brodie/trackmode3.png" style="width: 800px;" >
      <p><i>Track Information Mode 3</i></p>
      </center>
  	</div>
   </div>
   </td>
  <td><center><a href="#openModal3-2">View</a></center>
    <div id="openModal3-2" class="modalDialog">
  	<div>
  		<a href="#close" title="Close" class="close">X</a>
      <center>
      <img src="{{ site.baseurl }}/img/database/16-10-28-brodie/idmode3.avi.gif" style="width: 800px;" >
      <p><i>Identification Results Mode 3</i></p>
      </center>
  	</div>
   </div>
   </td>
  </tr>
  <tr>
   <td><center> 4 </center></td>
   <td><center> 40 </center></td>
   <td><center> 7.40 </center></td>
   <td><center> 0.28 </center></td>
   <td><center> 2.64 </center></td>
   <td><center> 18.09 </center></td>
   <td><center> 0.56 </center></td>
   <td><center> 17.77 </center></td>
   <td><center><a href="#openModal4-1">View</a></center>
    <div id="openModal4-1" class="modalDialog">
  	<div>
  		<a href="#close" title="Close" class="close">X</a>
      <center>
      <img src="{{ site.baseurl }}/img/database/16-10-28-brodie/trackmode4.png" style="width: 800px;" >
      <p><i>Track Information Mode 4</i></p>
      </center>
  	</div>
   </div>
   </td>
  <td><center><a href="#openModal4-2">View</a></center>
    <div id="openModal4-2" class="modalDialog">
  	<div>
  		<a href="#close" title="Close" class="close">X</a>
      <center>
      <img src="{{ site.baseurl }}/img/database/16-10-28-brodie/idmode4.avi.gif" style="width: 800px;" >
      <p><i>Identification Results Mode 4</i></p>
      </center>
  	</div>
   </div>
   </td>
  </tr>
  <tr>
   <td><center> 5 </center></td>
   <td><center> 94 </center></td>
   <td><center> 8.00 </center></td>
   <td><center> 0.38 </center></td>
   <td><center> 2.55 </center></td>
   <td><center> 12.09 </center></td>
   <td><center> 0.86 </center></td>
   <td><center> 29.72 </center></td>
   <td><center><a href="#openModal5-1">View</a></center>
    <div id="openModal5-1" class="modalDialog">
  	<div>
  		<a href="#close" title="Close" class="close">X</a>
      <center>
      <img src="{{ site.baseurl }}/img/database/16-10-28-brodie/trackmode5.png" style="width: 800px;" >
      <p><i>Track Information Mode 5</i></p>
      </center>
  	</div>
   </div>
   </td>
  <td><center><a href="#openModal5-2">View</a></center>
    <div id="openModal5-2" class="modalDialog">
  	<div>
  		<a href="#close" title="Close" class="close">X</a>
      <center>
      <img src="{{ site.baseurl }}/img/database/16-10-28-brodie/idmode5.avi.gif" style="width: 800px;" >
      <p><i>Identification Results Mode 5</i></p>
      </center>
  	</div>
   </div>
   </td>
  </tr>
  <tr>
   <td><center> 6 </center></td>
   <td><center> 121 </center></td>
   <td><center> 9.46 </center></td>
   <td><center> 0.25 </center></td>
   <td><center> 1.93 </center></td>
   <td><center> 15.97 </center></td>
   <td><center> 0.87 </center></td>
   <td><center> 23.46 </center></td>
   <td><center><a href="#openModal6-1">View</a></center>
    <div id="openModal6-1" class="modalDialog">
  	<div>
  		<a href="#close" title="Close" class="close">X</a>
      <center>
      <img src="{{ site.baseurl }}/img/database/16-10-28-brodie/trackmode6.png" style="width: 800px;" >
      <p><i>Track Information Mode 6</i></p>
      </center>
  	</div>
   </div>
   </td>
  <td><center><a href="#openModal6-2">View</a></center>
    <div id="openModal6-2" class="modalDialog">
  	<div>
  		<a href="#close" title="Close" class="close">X</a>
      <center>
      <img src="{{ site.baseurl }}/img/database/16-10-28-brodie/idmode6.avi.gif" style="width: 800px;" >
      <p><i>Identification Results Mode 6</i></p>
      </center>
  	</div>
   </div>
   </td>
  </tr>

</table>

<table id="myTable2">
<tr>
<td>
<center>
 <img src="{{ site.baseurl }}/img/database/16-10-28-brodie/synidresults.gif" style="width: 800px;" >
</center>
</td>
</tr>
</table>

<script>
var slideIndex = 1;
showSlides(slideIndex);

function plusSlides(n) {
  showSlides(slideIndex += n);
}

function currentSlide(n) {
  showSlides(slideIndex = n);
}

function showSlides(n) {
  var i;
  var slides = document.getElementsByClassName("mySlides");
  var dots = document.getElementsByClassName("dot");
  if (n > slides.length) {slideIndex = 1}
  if (n < 1) {slideIndex = slides.length}
  for (i = 0; i < slides.length; i++) {
      slides[i].style.display = "none";
  }
  for (i = 0; i < dots.length; i++) {
      dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[slideIndex-1].style.display = "block";
  dots[slideIndex-1].className += " active";
}


</script>
