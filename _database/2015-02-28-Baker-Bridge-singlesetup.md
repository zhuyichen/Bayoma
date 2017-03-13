---
layout: post-database
title: 150228 Baker Bridge Single Setup
date: 2015-02-28 00:00:00
author: Binbin Li (uol)
setupno: 1
locationno: 16
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
    <td> Baker Bridge </td>
    <td rowspan="9">
    <center>
    <p style="font-size: 16px; padding: 12px"> Exeter, UK </p>
    <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2526.4949591578047!2d-3.4723532980799607!3d50.71075600147584!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0x0!2zNTDCsDQyJzM4LjciTiAzwrAyOCcxMy41Ilc!5e0!3m2!1sen!2suk!4v14894240791410" width="500" height="400" frameborder="0" style="border:0" allowfullscreen>
    </iframe>
    </center>
    </td>
  </tr>
  <tr>
    <td class="header"><b>Type</b></td>
    <td> Cable-stayed footbridge </td>
  </tr>
  <tr>
    <td class="header"><b>Gross Dimensions</b></td>
    <td> 3.3m Wide x 109m Long x 42m High </td>
  </tr>
  <tr>
    <td class="header"><b>Equipment</b></td>
    <td> Honeywell QA-700 </td>
  </tr>
  <tr>
    <td class="header"><b>No. of Participants</b></td>
    <td> N/A </td>
  </tr>
  <tr>
    <td class="header"><b>No. of Setups</b></td>
    <td> 1 setup, 15min at 128Hz </td>
  </tr>
  <tr>
    <td class="header"><b>ID Method</b></td>
    <td> Single Setup BAYOMA </td>
  </tr>
  <tr>
    <td class="header"><b>Contributer</b></td>
    <td> Binbin Li (University of Liverpool) </td>
  </tr>
  <tr>
  <td class="header"><b>Data</b></td>
  <td>
    <a href="  "><b>Download</b></a> (6MB)
  </td>
  </tr>
</table>

## Setup and Gallery
---
<table id="myTable2">
 <tr>
  <td style="width:50%">
    <center>
     <img src="{{ site.baseurl}}/img/database/2015-02-28-Baker-Bridge-singlesetup/setup/setup.gif" style="width:100%;">
    </center>
  </td>
  <td style="width:50%">
    <center>

       <div class="slideshow-container">
        <div class="mySlides">
          <div class="numbertext">1 / 2</div>
          <img src="{{ site.baseurl}}/img/database/2015-02-28-Baker-Bridge-singlesetup/photo/Baker Bridge.png" style="width:80%">
          <div class="text"></div>
        </div>

        <div class="mySlides">
          <div class="numbertext">2 / 2</div>
          <img src="{{ site.baseurl}}/img/database/2015-02-28-Baker-Bridge-singlesetup/photo/Layout.png" style="width:80%">
          <div class="text"></div>
        </div>

        <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
        <a class="next" onclick="plusSlides(1)">&#10095;</a>
       </div>
       <br>

      <div style="text-align:center">
        <span class="dot" onclick="currentSlide(1)"></span>
        <span class="dot" onclick="currentSlide(2)"></span>
      </div>
      <script src="{{ site.baseurl }}/js/slideshow.js"></script>
    </center>
  </td>
 </tr>
</table>

## Data Spectra
---
<table id="myTable2">
 <tr>
  <td>
   <center>
    <img src="{{ site.baseurl}}/img/database/2015-02-28-Baker-Bridge-singlesetup/spectra/psd.png"  >
    <p> Root Power Spectrum </p>
    </center>
  </td>
  </tr>
  <tr>
  <td>
   <center>
    <img src="{{ site.baseurl}}/img/database/2015-02-28-Baker-Bridge-singlesetup/spectra/sv.png"  >
    <p> Root Singular Value Spectrum  </p>
    </center>
  </td>
 </tr>
</table>

#### * The initial guess and selected frequency band for each mode are shown in the root singular value spectrum with circles and the symbol '[-]'.

## Identification Results
---

<table id="myTable">
  <tr class="header">
    <th style="width:10%;" rowspan="2"><center>Mode</center></th>
    <th style="width:10%;" rowspan="2"><center>Modal s/n Ratio</center></th>
    <th style="width:20%;" colspan="2"><center>Natural Frequency (Hz)</center></th>
    <th style="width:20%;" colspan="2"><center>Damping Ratio (%)</center></th>
    <th style="width:20%;" colspan="2"><center>Modal Force PSD (ug/sqrt(Hz))</center></th>
    <th style="width:20%;" rowspan="2"><center>Mode Shape</center></th>
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
   <td><center> 83027 </center></td>
   <td><center> 0.94 </center></td>
   <td><center> 0.067 </center></td>
   <td><center> 0.23 </center></td>
   <td><center> 29 </center></td>
   <td><center> 70.81 </center></td>
   <td><center> 3.1 </center></td>
   <td><center><a href="#openModal1-2">View</a></center>
     <div id="openModal1-2" class="modalDialog">
	   <div>
		<a href="#close" title="Close" class="close">X</a>
      <center>
       <img src="{{ site.baseurl}}/img/database/2015-02-28-Baker-Bridge-singlesetup/modeshape/mode1.gif" style="width: 800px;" >
       <p><i>Identification Results Mode 1</i></p>
      </center>
	   </div>
     </div>
    </td>
  </tr>
  <tr>
   <td><center> 2 </center></td>
   <td><center> 8399 </center></td>
   <td><center> 1.63 </center></td>
   <td><center> 0.089 </center></td>
   <td><center> 0.65 </center></td>
   <td><center> 15 </center></td>
   <td><center> 259.60 </center></td>
   <td><center> 4.1 </center></td>
   <td><center><a href="#openModal2-2">View</a></center>
     <div id="openModal2-2" class="modalDialog">
	   <div>
		<a href="#close" title="Close" class="close">X</a>
      <center>
       <img src="{{ site.baseurl}}/img/database/2015-02-28-Baker-Bridge-singlesetup/modeshape/mode2.gif" style="width: 800px;" >
       <p><i>Identification Results Mode 2</i></p>
      </center>
	   </div>
     </div>
    </td>
  </tr>
  <tr>
   <td><center> 3 </center></td>
   <td><center> 24891 </center></td>
   <td><center> 2.01 </center></td>
   <td><center> 0.041 </center></td>
   <td><center> 0.19 </center></td>
   <td><center> 23 </center></td>
   <td><center> 479.80 </center></td>
   <td><center> 3.7 </center></td>
   <td><center><a href="#openModal3-2">View</a></center>
     <div id="openModal3-2" class="modalDialog">
	   <div>
		<a href="#close" title="Close" class="close">X</a>
      <center>
       <img src="{{ site.baseurl}}/img/database/2015-02-28-Baker-Bridge-singlesetup/modeshape/mode3.gif" style="width: 800px;" >
       <p><i>Identification Results Mode 3</i></p>
      </center>
	   </div>
     </div>
    </td>
  </tr>
  <tr>
   <td><center> 4 </center></td>
   <td><center> 6398 </center></td>
   <td><center> 2.24 </center></td>
   <td><center> 0.051 </center></td>
   <td><center> 0.31 </center></td>
   <td><center> 18 </center></td>
   <td><center> 308.37 </center></td>
   <td><center> 3.8 </center></td>
   <td><center><a href="#openModal4-2">View</a></center>
     <div id="openModal4-2" class="modalDialog">
	   <div>
		<a href="#close" title="Close" class="close">X</a>
      <center>
       <img src="{{ site.baseurl}}/img/database/2015-02-28-Baker-Bridge-singlesetup/modeshape/mode4.gif" style="width: 800px;" >
       <p><i>Identification Results Mode 4</i></p>
      </center>
	   </div>
     </div>
    </td>
  </tr>
  <tr>
   <td><center> 5 </center></td>
   <td><center> 510 </center></td>
   <td><center> 2.81 </center></td>
   <td><center> 0.071 </center></td>
   <td><center> 0.66 </center></td>
   <td><center> 12 </center></td>
   <td><center> 289.22 </center></td>
   <td><center> 3.9 </center></td>
   <td><center><a href="#openModal5-2">View</a></center>
     <div id="openModal5-2" class="modalDialog">
	   <div>
		<a href="#close" title="Close" class="close">X</a>
      <center>
       <img src="{{ site.baseurl}}/img/database/2015-02-28-Baker-Bridge-singlesetup/modeshape/mode5.gif" style="width: 800px;" >
       <p><i>Identification Results Mode 5</i></p>
      </center>
	   </div>
     </div>
    </td>
  </tr>
  <tr>
   <td><center> 6 </center></td>
   <td><center> 1827 </center></td>
   <td><center> 3.09 </center></td>
   <td><center> 0.083 </center></td>
   <td><center> 0.88 </center></td>
   <td><center> 12 </center></td>
   <td><center> 138.84 </center></td>
   <td><center> 4.8 </center></td>
   <td><center><a href="#openModal6-2">View</a></center>
     <div id="openModal6-2" class="modalDialog">
	   <div>
		<a href="#close" title="Close" class="close">X</a>
      <center>
       <img src="{{ site.baseurl}}/img/database/2015-02-28-Baker-Bridge-singlesetup/modeshape/mode6.gif" style="width: 800px;" >
       <p><i>Identification Results Mode 6</i></p>
      </center>
	   </div>
     </div>
    </td>
  </tr>
  <tr>
   <td><center> 7 </center></td>
   <td><center> 5105 </center></td>
   <td><center> 3.69 </center></td>
   <td><center> 0.04 </center></td>
   <td><center> 0.30 </center></td>
   <td><center> 14 </center></td>
   <td><center> 84.10 </center></td>
   <td><center> 3.2 </center></td>
   <td><center><a href="#openModal7-2">View</a></center>
     <div id="openModal7-2" class="modalDialog">
	   <div>
		<a href="#close" title="Close" class="close">X</a>
      <center>
       <img src="{{ site.baseurl}}/img/database/2015-02-28-Baker-Bridge-singlesetup/modeshape/mode7.gif" style="width: 800px;" >
       <p><i>Identification Results Mode 7</i></p>
      </center>
	   </div>
     </div>
    </td>
  </tr>
  <tr>
   <td><center> 8 </center></td>
   <td><center> 244 </center></td>
   <td><center> 4.42 </center></td>
   <td><center> 0.044 </center></td>
   <td><center> 0.29 </center></td>
   <td><center> 19 </center></td>
   <td><center> 31.36 </center></td>
   <td><center> 9.1 </center></td>
   <td><center><a href="#openModal8-2">View</a></center>
     <div id="openModal8-2" class="modalDialog">
	   <div>
		<a href="#close" title="Close" class="close">X</a>
      <center>
       <img src="{{ site.baseurl}}/img/database/2015-02-28-Baker-Bridge-singlesetup/modeshape/mode8.gif" style="width: 800px;" >
       <p><i>Identification Results Mode 8</i></p>
      </center>
	   </div>
     </div>
    </td>
  </tr>
  <tr>
   <td><center> 9 </center></td>
   <td><center> 4168 </center></td>
   <td><center> 4.55 </center></td>
   <td><center> 0.033 </center></td>
   <td><center> 0.23 </center></td>
   <td><center> 16 </center></td>
   <td><center> 55.42 </center></td>
   <td><center> 5.4 </center></td>
   <td><center><a href="#openModal9-2">View</a></center>
     <div id="openModal9-2" class="modalDialog">
	   <div>
		<a href="#close" title="Close" class="close">X</a>
      <center>
       <img src="{{ site.baseurl}}/img/database/2015-02-28-Baker-Bridge-singlesetup/modeshape/mode9.gif" style="width: 800px;" >
       <p><i>Identification Results Mode 9</i></p>
      </center>
	   </div>
     </div>
    </td>
  </tr>
  <tr>
   <td><center> 10 </center></td>
   <td><center> 300 </center></td>
   <td><center> 5.05 </center></td>
   <td><center> 0.049 </center></td>
   <td><center> 0.53 </center></td>
   <td><center> 11 </center></td>
   <td><center> 44.10 </center></td>
   <td><center> 4.1 </center></td>
   <td><center><a href="#openModal10-2">View</a></center>
     <div id="openModal10-2" class="modalDialog">
	   <div>
		<a href="#close" title="Close" class="close">X</a>
      <center>
       <img src="{{ site.baseurl}}/img/database/2015-02-28-Baker-Bridge-singlesetup/modeshape/mode10.gif" style="width: 800px;" >
       <p><i>Identification Results Mode 10</i></p>
      </center>
	   </div>
     </div>
    </td>
  </tr>
  <tr>
   <td><center> 11 </center></td>
   <td><center> 1590 </center></td>
   <td><center> 5.95 </center></td>
   <td><center> 0.027 </center></td>
   <td><center> 0.22 </center></td>
   <td><center> 13 </center></td>
   <td><center> 57.53 </center></td>
   <td><center> 3 </center></td>
   <td><center><a href="#openModal11-2">View</a></center>
     <div id="openModal11-2" class="modalDialog">
	   <div>
		<a href="#close" title="Close" class="close">X</a>
      <center>
       <img src="{{ site.baseurl}}/img/database/2015-02-28-Baker-Bridge-singlesetup/modeshape/mode11.gif" style="width: 800px;" >
       <p><i>Identification Results Mode 11</i></p>
      </center>
	   </div>
     </div>
    </td>
  </tr>
  <tr>
   <td><center> 12 </center></td>
   <td><center> 1135 </center></td>
   <td><center> 6.36 </center></td>
   <td><center> 0.036 </center></td>
   <td><center> 0.38 </center></td>
   <td><center> 11 </center></td>
   <td><center> 45.72 </center></td>
   <td><center> 3.7 </center></td>
   <td><center><a href="#openModal12-2">View</a></center>
     <div id="openModal12-2" class="modalDialog">
	   <div>
		<a href="#close" title="Close" class="close">X</a>
      <center>
       <img src="{{ site.baseurl}}/img/database/2015-02-28-Baker-Bridge-singlesetup/modeshape/mode12.gif" style="width: 800px;" >
       <p><i>Identification Results Mode 12</i></p>
      </center>
	   </div>
     </div>
    </td>
  </tr>
  <tr>
   <td><center> 13 </center></td>
   <td><center> 1407 </center></td>
   <td><center> 8.09 </center></td>
   <td><center> 0.026 </center></td>
   <td><center> 0.24 </center></td>
   <td><center> 13 </center></td>
   <td><center> 49.75 </center></td>
   <td><center> 4.6 </center></td>
   <td><center><a href="#openModal13-2">View</a></center>
     <div id="openModal13-2" class="modalDialog">
	   <div>
		<a href="#close" title="Close" class="close">X</a>
      <center>
       <img src="{{ site.baseurl}}/img/database/2015-02-28-Baker-Bridge-singlesetup/modeshape/mode13.gif" style="width: 800px;" >
       <p><i>Identification Results Mode 13</i></p>
      </center>
	   </div>
     </div>
    </td>
  </tr>
  <tr>
   <td><center> 14 </center></td>
   <td><center> 59 </center></td>
   <td><center> 8.31 </center></td>
   <td><center> 0.032 </center></td>
   <td><center> 0.28 </center></td>
   <td><center> 13 </center></td>
   <td><center> 24.26 </center></td>
   <td><center> 5.3 </center></td>
   <td><center><a href="#openModal14-2">View</a></center>
     <div id="openModal14-2" class="modalDialog">
	   <div>
		<a href="#close" title="Close" class="close">X</a>
      <center>
       <img src="{{ site.baseurl}}/img/database/2015-02-28-Baker-Bridge-singlesetup/modeshape/mode14.gif" style="width: 800px;" >
       <p><i>Identification Results Mode 14</i></p>
      </center>
	   </div>
     </div>
    </td>
  </tr>
  <tr>
   <td><center> 15 </center></td>
   <td><center> 136 </center></td>
   <td><center> 9.22 </center></td>
   <td><center> 0.045 </center></td>
   <td><center> 0.56 </center></td>
   <td><center> 11 </center></td>
   <td><center> 18.93 </center></td>
   <td><center> 6.3 </center></td>
   <td><center><a href="#openModal15-2">View</a></center>
     <div id="openModal15-2" class="modalDialog">
	   <div>
		<a href="#close" title="Close" class="close">X</a>
      <center>
       <img src="{{ site.baseurl}}/img/database/2015-02-28-Baker-Bridge-singlesetup/modeshape/mode15.gif" style="width: 800px;" >
       <p><i>Identification Results Mode 15</i></p>
      </center>
	   </div>
     </div>
    </td>
  </tr>
  <tr>
   <td><center> 16 </center></td>
   <td><center> 441 </center></td>
   <td><center> 9.56 </center></td>
   <td><center> 0.025 </center></td>
   <td><center> 0.26 </center></td>
   <td><center> 11 </center></td>
   <td><center> 21.53 </center></td>
   <td><center> 4 </center></td>
   <td><center><a href="#openModal16-2">View</a></center>
     <div id="openModal16-2" class="modalDialog">
	   <div>
		<a href="#close" title="Close" class="close">X</a>
      <center>
       <img src="{{ site.baseurl}}/img/database/2015-02-28-Baker-Bridge-singlesetup/modeshape/mode16.gif" style="width: 800px;" >
       <p><i>Identification Results Mode 16</i></p>
      </center>
	   </div>
     </div>
    </td>
  </tr>
  <tr>
   <td><center> 17 </center></td>
   <td><center> 820 </center></td>
   <td><center> 10.42 </center></td>
   <td><center> 0.026 </center></td>
   <td><center> 0.29 </center></td>
   <td><center> 11 </center></td>
   <td><center> 27.29 </center></td>
   <td><center> 4.3 </center></td>
   <td><center><a href="#openModal17-2">View</a></center>
     <div id="openModal17-2" class="modalDialog">
	   <div>
		<a href="#close" title="Close" class="close">X</a>
      <center>
       <img src="{{ site.baseurl}}/img/database/2015-02-28-Baker-Bridge-singlesetup/modeshape/mode17.gif" style="width: 800px;" >
       <p><i>Identification Results Mode 17</i></p>
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
    <img src="{{ site.baseurl}}/img/database/2015-02-28-Baker-Bridge-singlesetup/idresults/mode1_6.gif" style="width: 80%" >
    <p> Mode 1 - 6 </p>
   </center>
  </td>
 </tr>
 <tr>
  <td>
   <center>
    <img src="{{ site.baseurl}}/img/database/2015-02-28-Baker-Bridge-singlesetup/idresults/mode7_12.gif" style="width: 80%" >
      <p> Mode 7 - 12 </p>
   </center>
  </td>
 </tr>
 <tr>
  <td>
   <center>
    <img src="{{ site.baseurl}}/img/database/2015-02-28-Baker-Bridge-singlesetup/idresults/mode13_17.gif" style="width: 80%" >
      <p> Mode 13 - 17 </p>
   </center>
  </td>
 </tr>
</table>

## Uncertainty Laws
----

<table id="myTable2">
 <tr>
  <td style="width:100%">
    <center>

      <div class="slideshow-container">
        <div class="mySlides2">
          <div class="numbertext">1 / 3</div>
          <img src="{{ site.baseurl}}/img/database/2015-02-28-Baker-Bridge-singlesetup/unlaw-setup/mode1_6.png" style="width:600px">
          <div class="text"></div>
        </div>

        <div class="mySlides2">
          <div class="numbertext">2 / 3</div>
          <img src="{{ site.baseurl}}/img/database/2015-02-28-Baker-Bridge-singlesetup/unlaw-setup/mode7_12.png" style="width:600px">
          <div class="text"></div>
        </div>


         <div class="mySlides2">
           <div class="numbertext">3 / 3</div>
           <img src="{{ site.baseurl}}/img/database/2015-02-28-Baker-Bridge-singlesetup/unlaw-setup/mode13_17.png" style="width:600px">
           <div class="text"></div>
         </div>

     <a class="prev" onclick="plusSlides2(-1)">&#10094;</a>
     <a class="next" onclick="plusSlides2(1)">&#10095;</a>
    </div>
    <br>

    <div style="text-align:center">
       <span class="dot" onclick="currentSlide2(1)"></span>
       <span class="dot" onclick="currentSlide2(2)"></span>
       <span class="dot" onclick="currentSlide2(3)"></span>
    </div>
   </center>
   <script src="{{ site.baseurl }}/js/slideshow2.js"></script>
  </td>

 </tr>
</table>
