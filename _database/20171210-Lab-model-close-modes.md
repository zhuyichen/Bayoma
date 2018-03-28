---
layout: post-database
title: 20171210 Lab model close modes
date: 2017-12-10 00:00:00
author: Binbin Li (University of Liverpool)
setupno: 1
locationno: 13
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
    <td> Lab model with similary lateral stiffness </td>
    <td rowspan="9">
    <center>
    <p style="font-size: 16px; padding: 12px"> Liverpool, UK </p>
    <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d1000.0457394835264!2d-2.9674962574742336!3d53.40547184058334!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x487b21179d0d4789%3A0x862920629661e775!2sSchool+of+Engineering!5e0!3m2!1sen!2suk!4v1522182046544" width="500" height="400" frameborder="0" style="border:0" allowfullscreen>
    </iframe>
    </center>
    </td>
  </tr>
  <tr>
    <td class="header"><b>Type</b></td>
    <td> 3-storied shear-type building </td>
  </tr>
  <tr>
    <td class="header"><b>Gross Dimensions</b></td>
    <td> 0.25m Wide x 0.3m Long x 0.75m High </td>
  </tr>
  <tr>
    <td class="header"><b>Equipment</b></td>
    <td> 13 PCB accelerometers with 24 bit DAQ </td>
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
     <img src="{{ site.baseurl}}/img/database/2017-12-10-Lab-model-close-modes/setup/setup01.gif" style="width:100%;">
    </center>
  </td>
  <td style="width:50%">
    <center>

       <div class="slideshow-container">
        <div class="mySlides">
          <div class="numbertext">1 / 4</div>
          <img src="{{ site.baseurl}}/img/database/2017-12-10-Lab-model-close-modes/photo/IMG_2159.JPG" style="width:80%">
          <div class="text"></div>
        </div>

        <div class="mySlides">
          <div class="numbertext">2 / 4</div>
          <img src="{{ site.baseurl}}/img/database/2017-12-10-Lab-model-close-modes/photo/IMG_2160.JPG" style="width:80%">
          <div class="text"></div>
        </div>

        <div class="mySlides">
          <div class="numbertext">3 / 4</div>
          <img src="{{ site.baseurl}}/img/database/2017-12-10-Lab-model-close-modes/photo/IMG_2175 (1).JPG" style="width:80%">
          <div class="text"></div>
        </div>

        <div class="mySlides">
          <div class="numbertext">4 / 4</div>
          <img src="{{ site.baseurl}}/img/database/2017-12-10-Lab-model-close-modes/photo/IMG_2178.JPG" style="width:80%">
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

          <img src="{{ site.baseurl}}/img/database/2017-12-10-Lab-model-close-modes/psd/root_psd_data01.png" style="width:80%">

   </center>

  </td>
 </tr>
 <tr>
  <td style="width:100%">
    <center>


          <img src="{{ site.baseurl}}/img/database/2017-12-10-Lab-model-close-modes/sv/root_sv_data01.png" style="width:80%">
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
   <td><center> 122299 </center></td>
   <td><center> 3.89 </center></td>
   <td><center> 2.2e+02 </center></td>
   <td><center> 1.02 </center></td>
   <td><center> 64 </center></td>
   <td><center> 194.54 </center></td>
   <td><center> 96 </center></td>
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
       <img src="{{ site.baseurl}}/img/database/2017-12-10-Lab-model-close-modes/modeshape/mode1.gif" style="width: 800px;" >
       <p><i>Identification Results Mode 1</i></p>
      </center>
	   </div>
     </div>
    </td>
  </tr>
  <tr>
   <td><center> 2 </center></td>
   <td><center> N/A </center></td>
   <td><center> 67142 </center></td>
   <td><center> 3.94 </center></td>
   <td><center> 2.2e+02 </center></td>
   <td><center> 0.85 </center></td>
   <td><center> 77 </center></td>
   <td><center> 119.36 </center></td>
   <td><center> 2.5e+02 </center></td>
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
       <img src="{{ site.baseurl}}/img/database/2017-12-10-Lab-model-close-modes/modeshape/mode2.gif" style="width: 800px;" >
       <p><i>Identification Results Mode 2</i></p>
      </center>
	   </div>
     </div>
    </td>
  </tr>
  <tr>
   <td><center> 3 </center></td>
   <td><center> N/A </center></td>
   <td><center> 16399 </center></td>
   <td><center> 6.96 </center></td>
   <td><center> 1.2e+02 </center></td>
   <td><center> 1.06 </center></td>
   <td><center> 62 </center></td>
   <td><center> 180.16 </center></td>
   <td><center> 1.1e+02 </center></td>
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
       <img src="{{ site.baseurl}}/img/database/2017-12-10-Lab-model-close-modes/modeshape/mode3.gif" style="width: 800px;" >
       <p><i>Identification Results Mode 3</i></p>
      </center>
	   </div>
     </div>
    </td>
  </tr>
  <tr>
   <td><center> 4 </center></td>
   <td><center> N/A </center></td>
   <td><center> 18060 </center></td>
   <td><center> 11.38 </center></td>
   <td><center> 76 </center></td>
   <td><center> 0.69 </center></td>
   <td><center> 95 </center></td>
   <td><center> 157.97 </center></td>
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
       <img src="{{ site.baseurl}}/img/database/2017-12-10-Lab-model-close-modes/modeshape/mode4.gif" style="width: 800px;" >
       <p><i>Identification Results Mode 4</i></p>
      </center>
	   </div>
     </div>
    </td>
  </tr>
  <tr>
   <td><center> 5 </center></td>
   <td><center> N/A </center></td>
   <td><center> 6312 </center></td>
   <td><center> 11.46 </center></td>
   <td><center> 75 </center></td>
   <td><center> 0.84 </center></td>
   <td><center> 78 </center></td>
   <td><center> 113.86 </center></td>
   <td><center> 2.8e+02 </center></td>
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
       <img src="{{ site.baseurl}}/img/database/2017-12-10-Lab-model-close-modes/modeshape/mode5.gif" style="width: 800px;" >
       <p><i>Identification Results Mode 5</i></p>
      </center>
	   </div>
     </div>
    </td>
  </tr>
  <tr>
   <td><center> 6 </center></td>
   <td><center> N/A </center></td>
   <td><center> 2371 </center></td>
   <td><center> 17.15 </center></td>
   <td><center> 50 </center></td>
   <td><center> 0.65 </center></td>
   <td><center> 1e+02 </center></td>
   <td><center> 122.17 </center></td>
   <td><center> 2.4e+02 </center></td>
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
       <img src="{{ site.baseurl}}/img/database/2017-12-10-Lab-model-close-modes/modeshape/mode6.gif" style="width: 800px;" >
       <p><i>Identification Results Mode 6</i></p>
      </center>
	   </div>
     </div>
    </td>
  </tr>
  <tr>
   <td><center> 7 </center></td>
   <td><center> N/A </center></td>
   <td><center> 3232 </center></td>
   <td><center> 17.54 </center></td>
   <td><center> 49 </center></td>
   <td><center> 1.06 </center></td>
   <td><center> 61 </center></td>
   <td><center> 232.63 </center></td>
   <td><center> 67 </center></td>
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
       <img src="{{ site.baseurl}}/img/database/2017-12-10-Lab-model-close-modes/modeshape/mode7.gif" style="width: 800px;" >
       <p><i>Identification Results Mode 7</i></p>
      </center>
	   </div>
     </div>
    </td>
  </tr>
  <tr>
   <td><center> 8 </center></td>
   <td><center> N/A </center></td>
   <td><center> 1024 </center></td>
   <td><center> 19.89 </center></td>
   <td><center> 43 </center></td>
   <td><center> 1.66 </center></td>
   <td><center> 39 </center></td>
   <td><center> 264.36 </center></td>
   <td><center> 52 </center></td>
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
       <img src="{{ site.baseurl}}/img/database/2017-12-10-Lab-model-close-modes/modeshape/mode8.gif" style="width: 800px;" >
       <p><i>Identification Results Mode 8</i></p>
      </center>
	   </div>
     </div>
    </td>
  </tr>
  <tr>
   <td><center> 9 </center></td>
   <td><center> N/A </center></td>
   <td><center> 13960 </center></td>
   <td><center> 30.41 </center></td>
   <td><center> 28 </center></td>
   <td><center> 2.70 </center></td>
   <td><center> 24 </center></td>
   <td><center> 492.02 </center></td>
   <td><center> 15 </center></td>
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
       <img src="{{ site.baseurl}}/img/database/2017-12-10-Lab-model-close-modes/modeshape/mode9.gif" style="width: 800px;" >
       <p><i>Identification Results Mode 9</i></p>
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
    <img src="{{ site.baseurl}}/img/database/2017-12-10-Lab-model-close-modes/idresults/mode.gif" style="width: 1000px;" >
   </center>
  </td>
 </tr>
</table>
