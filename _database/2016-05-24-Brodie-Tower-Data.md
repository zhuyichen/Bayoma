---
layout: post-database
title: 160524 Brodie Tower
date: 2016-05-24 16:05:00
author: Yichen Zhu
setupno: 7
locationno: 29
datadl: Not Available
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
    <td rowspan="9">
    <center>
    <p style="font-size: 16px; padding: 12px">University of Liverpool, Brownlow Street, Liverpool, L69 3GQ</p>
    <iframe src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d1189.2414356949819!2d-2.967125279272631!3d53.4061899038967!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0x142bb768f021cfd9!2sBrodie+Tower!5e0!3m2!1sen!2suk!4v1477754248132" width="500" height="400" frameborder="0" style="border:0" allowfullscreen>
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
    <td>5 triaxial servo-accelerometers with 24 bit digitizer and individual high precision clock</td>
  </tr>
  <tr>
    <td class="header"><b>No. of Participants</b></td>
    <td>2</td>
  </tr>
  <tr>
    <td class="header"><b>No. of Setups</b></td>
    <td>7 setups, each 20 min at 50 Hz</td>
  </tr>
  <tr>
    <td class="header"><b>ID Method</b></td>
    <td>Single setup BAYOMA, mode shape assembled by global least square</td>
  </tr>
  <tr>
    <td class="header"><b>Contributer</b></td>
    <td>Yi-Chen Zhu, Yan-Long Xie, Siu-Kui Au (University of Liverpool)</td>
  </tr>
  <tr>
  <td class="header"><b>Data</b></td>
  <td>
    <!-- <a href="http://gofile.me/3sin6/YJvW4c0o4"><b>Download</b></a> (24.7Mb) -->
    N/A
  </td>
  </tr>
</table>

## Setup and Gallery
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
      <script src="{{ site.baseurl }}/js/slideshow.js"></script>
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
    <p>Root Power Spectrum of Setup 2</p>
    </center>
  </td>
  <td>
   <center>
    <img src="{{ site.baseurl }}/img/database/16-10-28-brodie/svd.png" style="width: 500px;" >
    <p>Root Singular Value Spectrum of Setup 2</p>
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
    <th style="width:10%;" colspan="2"><center>Modal s/n Ratio</center></th>
    <th style="width:20%;" colspan="2"><center>Natural Frequency (Hz)</center></th>
    <th style="width:20%;" colspan="2"><center>Damping Ratio (%)</center></th>
    <th style="width:20%;" colspan="2"><center>Modal Force PSD (ug/sqrt(Hz))</center></th>
    <th style="width:10%;" rowspan="2"><center>Track</center></th>
    <th style="width:10%;" rowspan="2"><center>Mode Shape</center></th>
  </tr>
  <tr class="header">
    <th style="width:10%;" ><center>Min</center></th>
    <th style="width:10%;" ><center>Max</center></th>
    <th style="width:10%;" ><center>MPV</center></th>
    <th style="width:10%;" ><center>c.o.v.(%)</center></th>
    <th style="width:10%;" ><center>MPV</center></th>
    <th style="width:10%;" ><center>c.o.v.(%)</center></th>
    <th style="width:10%;" ><center>MPV</center></th>
    <th style="width:10%;" ><center>c.o.v.(%)</center></th>
  </tr>

  <tr>
   <td><center> 1 </center></td>
   <td><center> 1189 </center></td>
   <td><center> 1761 </center></td>
   <td><center> 2.42 </center></td>
   <td><center> 0.21 </center></td>
   <td><center> 0.99 </center></td>
   <td><center> 19 </center></td>
   <td><center> 1.07 </center></td>
   <td><center> 45 </center></td>
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
   <td><center> 970 </center></td>
   <td><center> 2411 </center></td>
   <td><center> 2.71 </center></td>
   <td><center> 0.26 </center></td>
   <td><center> 0.96 </center></td>
   <td><center> 22 </center></td>
   <td><center> 1.09 </center></td>
   <td><center> 35 </center></td>
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
   <td><center> 1413 </center></td>
   <td><center> 6365 </center></td>
   <td><center> 3.75 </center></td>
   <td><center> 0.25 </center></td>
   <td><center> 0.82 </center></td>
   <td><center> 11 </center></td>
   <td><center> 1.00 </center></td>
   <td><center> 56 </center></td>
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
   <td><center> 26 </center></td>
   <td><center> 40 </center></td>
   <td><center> 7.41 </center></td>
   <td><center> 0.28 </center></td>
   <td><center> 2.69 </center></td>
   <td><center> 18 </center></td>
   <td><center> 0.58 </center></td>
   <td><center> 18 </center></td>
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
   <td><center> 19 </center></td>
   <td><center> 92 </center></td>
   <td><center> 8.00 </center></td>
   <td><center> 0.33 </center></td>
   <td><center> 2.58 </center></td>
   <td><center> 12 </center></td>
   <td><center> 0.89 </center></td>
   <td><center> 28 </center></td>
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

## Uncertainty Laws
----

<table id="myTable2">
 <tr>
  <td style="width:50%">
    <center>
    <div class="slideshow-container">
     <div class="mySlides2" >
       <div class="numbertext">1 / 7</div>
       <img src="{{ site.baseurl }}/img/database/16-10-28-brodie/setup1.png" style="width:80%">
       <div class="text"></div>
     </div>

     <div class="mySlides2">
       <div class="numbertext">2 / 7</div>
       <img src="{{ site.baseurl }}/img/database/16-10-28-brodie/setup2.png" style="width:80%">
     </div>

     <div class="mySlides2">
       <div class="numbertext">3 / 7</div>
       <img src="{{ site.baseurl }}/img/database/16-10-28-brodie/setup3.png" style="width:80%">
     </div>

     <div class="mySlides2">
       <div class="numbertext">4 / 7</div>
       <img src="{{ site.baseurl }}/img/database/16-10-28-brodie/setup4.png" style="width:80%">
     </div>

     <div class="mySlides2">
       <div class="numbertext">5 / 7</div>
       <img src="{{ site.baseurl }}/img/database/16-10-28-brodie/setup5.png" style="width:80%">
     </div>

     <div class="mySlides2">
       <div class="numbertext">6 / 7</div>
       <img src="{{ site.baseurl }}/img/database/16-10-28-brodie/setup6.png" style="width:80%">
     </div>

     <div class="mySlides2">
       <div class="numbertext">7 / 7</div>
       <img src="{{ site.baseurl }}/img/database/16-10-28-brodie/setup7.png" style="width:80%">
     </div>
     <a class="prev" onclick="plusSlides2(-1)">&#10094;</a>
     <a class="next" onclick="plusSlides2(1)">&#10095;</a>
    </div>
    <br>

   <div style="text-align:center">
   <span class="dot2" onclick="currentSlide2(1)"></span>
   <span class="dot2" onclick="currentSlide2(2)"></span>
   <span class="dot2" onclick="currentSlide2(3)"></span>
   <span class="dot2" onclick="currentSlide2(4)"></span>
   <span class="dot2" onclick="currentSlide2(5)"></span>
   <span class="dot2" onclick="currentSlide2(6)"></span>
   <span class="dot2" onclick="currentSlide2(7)"></span>
   </div>
   </center>
   <script src="{{ site.baseurl }}/js/slideshow2.js"></script>
  </td>

  <td style="width:50%">
    <center>
    <div class="slideshow-container">
     <div class="mySlides3" >
       <div class="numbertext">1 / 5</div>
       <img src="{{ site.baseurl }}/img/database/16-10-28-brodie/mode1.png" style="width:80%">
       <div class="text"></div>
     </div>

     <div class="mySlides3">
       <div class="numbertext">2 / 5</div>
       <img src="{{ site.baseurl }}/img/database/16-10-28-brodie/mode2.png" style="width:80%">
     </div>

     <div class="mySlides3">
       <div class="numbertext">3 / 5</div>
       <img src="{{ site.baseurl }}/img/database/16-10-28-brodie/mode3.png" style="width:80%">
     </div>

     <div class="mySlides3">
       <div class="numbertext">4 / 5</div>
       <img src="{{ site.baseurl }}/img/database/16-10-28-brodie/mode4.png" style="width:80%">
     </div>

     <div class="mySlides3">
       <div class="numbertext">5 / 5</div>
       <img src="{{ site.baseurl }}/img/database/16-10-28-brodie/mode5.png" style="width:80%">
     </div>


     <a class="prev" onclick="plusSlides3(-1)">&#10094;</a>
     <a class="next" onclick="plusSlides3(1)">&#10095;</a>
    </div>
    <br>

   <div style="text-align:center">
   <span class="dot3" onclick="currentSlide3(1)"></span>
   <span class="dot3" onclick="currentSlide3(2)"></span>
   <span class="dot3" onclick="currentSlide3(3)"></span>
   <span class="dot3" onclick="currentSlide3(4)"></span>
   <span class="dot3" onclick="currentSlide3(5)"></span>
   </div>
   </center>
   <script src="{{ site.baseurl }}/js/slideshow3.js"></script>
  </td>
 </tr>
</table>
