---
layout: post-database
title: 20171204 Lab model close modes with tmd
date: 2017-12-04 00:00:00
author: Binbin Li (University of Liverpool)
setupno: 1
locationno: 14
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
    <td> Lab model with similary lateral stiffness and tmd </td>
    <td rowspan="9">
    <center>
    <p style="font-size: 16px; padding: 12px"> Liverpool, UK </p>
    <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d1000.0457394835264!2d-2.9674962574742336!3d53.40547184058334!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x487b21179d0d4789%3A0x862920629661e775!2sSchool+of+Engineering!5e0!3m2!1sen!2suk!4v1522182046544 " width="500" height="400" frameborder="0" style="border:0" allowfullscreen>
    </iframe>
    </center>
    </td>
  </tr>
  <tr>
    <td class="header"><b>Type</b></td>
    <td> 3-storied shear-type building with tmd </td>
  </tr>
  <tr>
    <td class="header"><b>Gross Dimensions</b></td>
    <td> 0.25m Wide x 0.3m Long x 0.75m High + 0.2m tmd </td>
  </tr>
  <tr>
    <td class="header"><b>Equipment</b></td>
    <td> 14 PCB accelerometers with 24 bit DAQ </td>
  </tr>
  <tr>
    <td class="header"><b>No. of Participants</b></td>
    <td> 1 </td>
  </tr>
  <tr>
    <td class="header"><b>No. of Setups</b></td>
    <td> 1 setup, 3hr at 256Hz </td>
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
     <img src="{{ site.baseurl}}/img/database/2017-12-04-Lab-model-close-modes-with-tmd/setup/setup01.gif" style="width:100%;">
    </center>
  </td>
  <td style="width:50%">
    <center>

       <div class="slideshow-container">
        <div class="mySlides">
          <div class="numbertext">1 / 5</div>
          <img src="{{ site.baseurl}}/img/database/2017-12-04-Lab-model-close-modes-with-tmd/photo/IMG_2159.JPG" style="width:80%">
          <div class="text"></div>
        </div>

        <div class="mySlides">
          <div class="numbertext">2 / 5</div>
          <img src="{{ site.baseurl}}/img/database/2017-12-04-Lab-model-close-modes-with-tmd/photo/IMG_2160.JPG" style="width:80%">
          <div class="text"></div>
        </div>

        <div class="mySlides">
          <div class="numbertext">3 / 5</div>
          <img src="{{ site.baseurl}}/img/database/2017-12-04-Lab-model-close-modes-with-tmd/photo/IMG_2440.JPG" style="width:80%">
          <div class="text"></div>
        </div>

        <div class="mySlides">
          <div class="numbertext">4 / 5</div>
          <img src="{{ site.baseurl}}/img/database/2017-12-04-Lab-model-close-modes-with-tmd/photo/IMG_2442.JPG" style="width:80%">
          <div class="text"></div>
        </div>

        <div class="mySlides">
          <div class="numbertext">5 / 5</div>
          <img src="{{ site.baseurl}}/img/database/2017-12-04-Lab-model-close-modes-with-tmd/photo/IMG_2446.JPG" style="width:80%">
          <div class="text"></div>
        </div>


        <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
        <a class="next" onclick="plusSlides(1)">&#10095;</a>
       </div>
       <br>

      <div style="text-align:center">
        <span class="dot" onclick="currentSlide(1)"></span>
        <span class="dot" onclick="currentSlide(2)"></span>
        <span class="dot" onclick="currentSlide(3)"></span>
        <span class="dot" onclick="currentSlide(4)"></span>
        <span class="dot" onclick="currentSlide(5)"></span>
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
  <td style="width:100%">
    <center>
          <img src="{{ site.baseurl}}/img/database/2017-12-04-Lab-model-close-modes-with-tmd/psd/root_psd_data01.png" style="width:80%">
          <p> Root Power Spectrum </p>
   </center>
  </td>
 </tr>
 <tr>
  <td style="width:100%">
    <center>
          <img src="{{ site.baseurl}}/img/database/2017-12-04-Lab-model-close-modes-with-tmd/sv/root_sv_data01.png" style="width:80%">
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
   <td><center> N/A </center></td>
   <td><center> 4471291 </center></td>
   <td><center> 3.65 </center></td>
   <td><center> 2.3e+02 </center></td>
   <td><center> 0.32 </center></td>
   <td><center> 70 </center></td>
   <td><center> 161.94 </center></td>
   <td><center> 16 </center></td>
   <td><center><a href="#openModal1-1">View</a></center>
   <div id="openModal1-1" class="modalDialog">
	<div>
		<a href="#close" title="Close" class="close">X</a>
    <center>
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
       <img src="{{ site.baseurl}}/img/database/2017-12-04-Lab-model-close-modes-with-tmd/modeshape/mode1.gif" style="width: 800px;" >
       <p><i>Identification Results Mode 1</i></p>
      </center>
	   </div>
     </div>
    </td>
  </tr>
  <tr>
   <td><center> 2 </center></td>
   <td><center> N/A </center></td>
   <td><center> 1836091 </center></td>
   <td><center> 3.90 </center></td>
   <td><center> 2.1e+02 </center></td>
   <td><center> 0.37 </center></td>
   <td><center> 62 </center></td>
   <td><center> 119.85 </center></td>
   <td><center> 30 </center></td>
   <td><center><a href="#openModal2-1">View</a></center>
   <div id="openModal2-1" class="modalDialog">
	<div>
		<a href="#close" title="Close" class="close">X</a>
    <center>
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
       <img src="{{ site.baseurl}}/img/database/2017-12-04-Lab-model-close-modes-with-tmd/modeshape/mode2.gif" style="width: 800px;" >
       <p><i>Identification Results Mode 2</i></p>
      </center>
	   </div>
     </div>
    </td>
  </tr>
  <tr>
   <td><center> 3 </center></td>
   <td><center> N/A </center></td>
   <td><center> 741808 </center></td>
   <td><center> 3.95 </center></td>
   <td><center> 2.1e+02 </center></td>
   <td><center> 0.44 </center></td>
   <td><center> 50 </center></td>
   <td><center> 91.13 </center></td>
   <td><center> 51 </center></td>
   <td><center><a href="#openModal3-1">View</a></center>
   <div id="openModal3-1" class="modalDialog">
	<div>
		<a href="#close" title="Close" class="close">X</a>
    <center>
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
       <img src="{{ site.baseurl}}/img/database/2017-12-04-Lab-model-close-modes-with-tmd/modeshape/mode3.gif" style="width: 800px;" >
       <p><i>Identification Results Mode 3</i></p>
      </center>
	   </div>
     </div>
    </td>
  </tr>
  <tr>
   <td><center> 4 </center></td>
   <td><center> N/A </center></td>
   <td><center> 12502 </center></td>
   <td><center> 6.89 </center></td>
   <td><center> 1.2e+02 </center></td>
   <td><center> 1.02 </center></td>
   <td><center> 23 </center></td>
   <td><center> 52.63 </center></td>
   <td><center> 1.5e+02 </center></td>
   <td><center><a href="#openModal4-1">View</a></center>
   <div id="openModal4-1" class="modalDialog">
	<div>
		<a href="#close" title="Close" class="close">X</a>
    <center>
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
       <img src="{{ site.baseurl}}/img/database/2017-12-04-Lab-model-close-modes-with-tmd/modeshape/mode4.gif" style="width: 800px;" >
       <p><i>Identification Results Mode 4</i></p>
      </center>
	   </div>
     </div>
    </td>
  </tr>
  <tr>
   <td><center> 5 </center></td>
   <td><center> N/A </center></td>
   <td><center> 6909 </center></td>
   <td><center> 11.13 </center></td>
   <td><center> 74 </center></td>
   <td><center> 0.43 </center></td>
   <td><center> 52 </center></td>
   <td><center> 11.24 </center></td>
   <td><center> 3.3e+03 </center></td>
   <td><center><a href="#openModal5-1">View</a></center>
   <div id="openModal5-1" class="modalDialog">
	<div>
		<a href="#close" title="Close" class="close">X</a>
    <center>
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
       <img src="{{ site.baseurl}}/img/database/2017-12-04-Lab-model-close-modes-with-tmd/modeshape/mode5.gif" style="width: 800px;" >
       <p><i>Identification Results Mode 5</i></p>
      </center>
	   </div>
     </div>
    </td>
  </tr>
  <tr>
   <td><center> 6 </center></td>
   <td><center> N/A </center></td>
   <td><center> 8229 </center></td>
   <td><center> 11.31 </center></td>
   <td><center> 73 </center></td>
   <td><center> 0.43 </center></td>
   <td><center> 52 </center></td>
   <td><center> 12.25 </center></td>
   <td><center> 2.8e+03 </center></td>
   <td><center><a href="#openModal6-1">View</a></center>
   <div id="openModal6-1" class="modalDialog">
	<div>
		<a href="#close" title="Close" class="close">X</a>
    <center>
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
       <img src="{{ site.baseurl}}/img/database/2017-12-04-Lab-model-close-modes-with-tmd/modeshape/mode6.gif" style="width: 800px;" >
       <p><i>Identification Results Mode 6</i></p>
      </center>
	   </div>
     </div>
    </td>
  </tr>
  <tr>
   <td><center> 7 </center></td>
   <td><center> N/A </center></td>
   <td><center> 2532 </center></td>
   <td><center> 16.93 </center></td>
   <td><center> 49 </center></td>
   <td><center> 0.47 </center></td>
   <td><center> 47 </center></td>
   <td><center> 8.01 </center></td>
   <td><center> 6.6e+03 </center></td>
   <td><center><a href="#openModal7-1">View</a></center>
   <div id="openModal7-1" class="modalDialog">
	<div>
		<a href="#close" title="Close" class="close">X</a>
    <center>
    <p><i>Track Information Mode 7</i></p>
    </center>
	</div>
   </div>
   </td>
   <td><center><a href="#openModal7-2">View</a></center>
     <div id="openModal7-2" class="modalDialog">
	   <div>
		<a href="#close" title="Close" class="close">X</a>
      <center>
       <img src="{{ site.baseurl}}/img/database/2017-12-04-Lab-model-close-modes-with-tmd/modeshape/mode7.gif" style="width: 800px;" >
       <p><i>Identification Results Mode 7</i></p>
      </center>
	   </div>
     </div>
    </td>
  </tr>
  <tr>
   <td><center> 8 </center></td>
   <td><center> N/A </center></td>
   <td><center> 95240 </center></td>
   <td><center> 17.18 </center></td>
   <td><center> 48 </center></td>
   <td><center> 0.25 </center></td>
   <td><center> 87 </center></td>
   <td><center> 26.44 </center></td>
   <td><center> 6e+02 </center></td>
   <td><center><a href="#openModal8-1">View</a></center>
   <div id="openModal8-1" class="modalDialog">
	<div>
		<a href="#close" title="Close" class="close">X</a>
    <center>
    <p><i>Track Information Mode 8</i></p>
    </center>
	</div>
   </div>
   </td>
   <td><center><a href="#openModal8-2">View</a></center>
     <div id="openModal8-2" class="modalDialog">
	   <div>
		<a href="#close" title="Close" class="close">X</a>
      <center>
       <img src="{{ site.baseurl}}/img/database/2017-12-04-Lab-model-close-modes-with-tmd/modeshape/mode8.gif" style="width: 800px;" >
       <p><i>Identification Results Mode 8</i></p>
      </center>
	   </div>
     </div>
    </td>
  </tr>
  <tr>
   <td><center> 9 </center></td>
   <td><center> N/A </center></td>
   <td><center> 156698 </center></td>
   <td><center> 17.73 </center></td>
   <td><center> 46 </center></td>
   <td><center> 0.20 </center></td>
   <td><center> 1.1e+02 </center></td>
   <td><center> 26.85 </center></td>
   <td><center> 5.8e+02 </center></td>
   <td><center><a href="#openModal9-1">View</a></center>
   <div id="openModal9-1" class="modalDialog">
	<div>
		<a href="#close" title="Close" class="close">X</a>
    <center>
    <p><i>Track Information Mode 9</i></p>
    </center>
	</div>
   </div>
   </td>
   <td><center><a href="#openModal9-2">View</a></center>
     <div id="openModal9-2" class="modalDialog">
	   <div>
		<a href="#close" title="Close" class="close">X</a>
      <center>
       <img src="{{ site.baseurl}}/img/database/2017-12-04-Lab-model-close-modes-with-tmd/modeshape/mode9.gif" style="width: 800px;" >
       <p><i>Identification Results Mode 9</i></p>
      </center>
	   </div>
     </div>
    </td>
  </tr>
  <tr>
   <td><center> 10 </center></td>
   <td><center> N/A </center></td>
   <td><center> 3805 </center></td>
   <td><center> 19.56 </center></td>
   <td><center> 42 </center></td>
   <td><center> 0.61 </center></td>
   <td><center> 36 </center></td>
   <td><center> 12.14 </center></td>
   <td><center> 2.9e+03 </center></td>
   <td><center><a href="#openModal10-1">View</a></center>
   <div id="openModal10-1" class="modalDialog">
	<div>
		<a href="#close" title="Close" class="close">X</a>
    <center>
    <p><i>Track Information Mode 10</i></p>
    </center>
	</div>
   </div>
   </td>
   <td><center><a href="#openModal10-2">View</a></center>
     <div id="openModal10-2" class="modalDialog">
	   <div>
		<a href="#close" title="Close" class="close">X</a>
      <center>
       <img src="{{ site.baseurl}}/img/database/2017-12-04-Lab-model-close-modes-with-tmd/modeshape/mode10.gif" style="width: 800px;" >
       <p><i>Identification Results Mode 10</i></p>
      </center>
	   </div>
     </div>
    </td>
  </tr>
  <tr>
   <td><center> 11 </center></td>
   <td><center> N/A </center></td>
   <td><center> 19764 </center></td>
   <td><center> 29.80 </center></td>
   <td><center> 28 </center></td>
   <td><center> 0.47 </center></td>
   <td><center> 47 </center></td>
   <td><center> 9.31 </center></td>
   <td><center> 4.9e+03 </center></td>
   <td><center><a href="#openModal11-1">View</a></center>
   <div id="openModal11-1" class="modalDialog">
	<div>
		<a href="#close" title="Close" class="close">X</a>
    <center>
    <p><i>Track Information Mode 11</i></p>
    </center>
	</div>
   </div>
   </td>
   <td><center><a href="#openModal11-2">View</a></center>
     <div id="openModal11-2" class="modalDialog">
	   <div>
		<a href="#close" title="Close" class="close">X</a>
      <center>
       <img src="{{ site.baseurl}}/img/database/2017-12-04-Lab-model-close-modes-with-tmd/modeshape/mode11.gif" style="width: 800px;" >
       <p><i>Identification Results Mode 11</i></p>
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
    <img src="{{ site.baseurl}}/img/database/2017-12-04-Lab-model-close-modes-with-tmd/idresults/mode.gif" style="width: 1100px;" >
   </center>
  </td>
 </tr>
</table>
