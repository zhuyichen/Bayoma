---
layout: post-database
title: 160524-Brodie Tower Data
date: 2016-05-24 16:05:00
author: Yichen Zhu
setupno: 7
sensorno: 5
datadl: Available
---

## Test Information
---


<table id="myTable2">
  <tr class="header">
    <th style="width:50%;">Date</th>
    <th style="width:50%;" style="border:1px solid #ddd">Address</th>    
  </tr>
  <tr>
    <td>{{ page.date | date: "%B %-d, %Y" }}</td>
    <td rowspan="9" style="border:1px solid #ddd">
    <center>
    <p style="font-size: 16px; padding: 12px">University of Liverpool, Brownlow Street, Liverpool, L69 3GQ</p>
    <iframe
src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d1189.2414356949819!2d-2.967125279272631!3d53.4061899038967!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0x142bb768f021cfd9!2sBrodie+Tower!5e0!3m2!1sen!2suk!4v1477754248132" width="500" height="400" frameborder="0" style="border:0" allowfullscreen>
    </iframe>
    </center>
    </td>    
  </tr>
  <tr class="header">
    <th>Structure</th>
  </tr>
  <tr>
    <td>Brodie Tower, University of Liverpool</td>
  </tr>
  <tr class="header">
    <th>Type</th>
  </tr>
  <tr>
    <td>Reinforced concrete building, 7-storeys</td>
  </tr>
  <tr class="header">
    <th>Gross Dimensions</th>
  </tr>
  <tr>
    <td>25m Width x 28m Depth x 25m Height</td>
  </tr>
  <tr class="header">
    <th>Equipment</th>
  </tr>
  <tr>
    <td>4 triaxial servo-accelerometers with 24 bit digitizer and individual high precision clock</td>
  </tr>
  <tr class="header">
    <th>No. of Participants</th>
    <th style="border:1px solid #ddd">No. of Setups</th>
  </tr>
  <tr>
    <td>2 persons</td>
    <td style="border:1px solid #ddd">Seven setups, each 15 min at 50 Hz</td>
  </tr>
  <tr class="header">
     <th colspan="2"><center>Data Download</center></th>
  </tr>
  <tr>
    <td colspan="2">
    <center>
    <a href="http://gofile.me/3sin6/wqWI4T0cI"> Click Here </a>
    </center>
    </td>
  </tr>
</table>

## Photo Gallery
---

<table id="myTable2">
 <tr>
  <td>
   <center>
   <img src="{{ site.baseurl }}/img/database/16-10-28-brodie/planview.png" style="width: 500px;" >
   </center>
  </td>
  <td>
   <center>
    <img src="{{ site.baseurl }}/img/database/16-10-28-brodie/brodie-tower.jpg" style="width: 500px;" >
   </center>
  </td>  
 </tr>
 <tr>
  <td>
   <center>
    <img src="{{ site.baseurl }}/img/database/16-10-28-brodie/sensor.jpg" style="width: 500px;" >
   </center>
  </td>
  <td>
   <center>
    <img src="{{ site.baseurl }}/img/database/16-10-28-brodie/synsetup.gif" style="width: 500px;" >
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
    <p><i>Root Power Spectrum of 6/F </i></p>
    </center>
  </td>
  <td>
   <center>
    <img src="{{ site.baseurl }}/img/database/16-10-28-brodie/svd.png" style="width: 500px;" >
    <p><i>Root Singular Value Spectrum of 6/F </i></p>
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
    <th style="width:10%;" ><center>sample c.o.v.(%)</center></th>
    <th style="width:10%;" ><center>MPV</center></th>
    <th style="width:10%;" ><center>sample c.o.v.(%)</center></th>
    <th style="width:10%;" ><center>MPV</center></th>
    <th style="width:10%;" ><center>sample c.o.v.(%)</center></th>
  </tr>

  <tr>
   <td><center> 1 </center></td>
   <td><center> 938 </center></td>
   <td><center> 2.42 </center></td>
   <td><center> 0.04 </center></td>
   <td><center> 0.96 </center></td>
   <td><center> 5.59 </center></td>
   <td><center> 0.57 </center></td>
   <td><center> 13.95 </center></td>
   <td><center><a href="#openModal1-1">View</a></center>
    <div id="openModal1-1" class="modalDialog">
  	<div>
  		<a href="#close" title="Close" class="close">X</a>
      <center>
      <img src="{{ site.baseurl }}/img/database/16-10-28-brodie/idmode1.avi.gif" style="width: 600px;" >
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
      <img src="{{ site.baseurl }}/img/database/16-10-28-brodie/idmode1.avi.gif" style="width: 600px;" >
      <p><i>Identification Results Mode 1</i></p>
      </center>
  	</div>
   </div>
   </td>
  </tr>
  <tr>
   <td><center> 2 </center></td>
   <td><center> 1086 </center></td>
   <td><center> 2.70 </center></td>
   <td><center> 0.04 </center></td>
   <td><center> 0.91 </center></td>
   <td><center> 6.11 </center></td>
   <td><center> 0.76 </center></td>
   <td><center> 14.95 </center></td>
   <td><center><a href="#openModal2-1">View</a></center>
    <div id="openModal2-1" class="modalDialog">
  	<div>
  		<a href="#close" title="Close" class="close">X</a>
      <center>
      <img src="{{ site.baseurl }}/img/database/16-10-28-brodie/idmode2.avi.gif" style="width: 600px;" >
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
      <img src="{{ site.baseurl }}/img/database/16-10-28-brodie/idmode2.avi.gif" style="width: 600px;" >
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
   <td><center> 0.02 </center></td>
   <td><center> 0.82 </center></td>
   <td><center> 3.75 </center></td>
   <td><center> 0.49 </center></td>
   <td><center> 10.43 </center></td>
   <td><center><a href="#openModal3-1">View</a></center>
    <div id="openModal3-1" class="modalDialog">
  	<div>
  		<a href="#close" title="Close" class="close">X</a>
      <center>
      <img src="{{ site.baseurl }}/img/database/16-10-28-brodie/idmode3.avi.gif" style="width: 600px;" >
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
      <img src="{{ site.baseurl }}/img/database/16-10-28-brodie/idmode3.avi.gif" style="width: 600px;" >
      <p><i>Identification Results Mode 3</i></p>
      </center>
  	</div>
   </div>
   </td>
  </tr>
  <tr>
   <td><center> 4 </center></td>
   <td><center> 39.64 </center></td>
   <td><center> 7.40 </center></td>
   <td><center> 0.06 </center></td>
   <td><center> 2.54 </center></td>
   <td><center> 4.74 </center></td>
   <td><center> 0.52 </center></td>
   <td><center> 13.89 </center></td>
   <td><center><a href="#openModal4-1">View</a></center>
    <div id="openModal4-1" class="modalDialog">
  	<div>
  		<a href="#close" title="Close" class="close">X</a>
      <center>
      <img src="{{ site.baseurl }}/img/database/16-10-28-brodie/idmode4.avi.gif" style="width: 600px;" >
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
      <img src="{{ site.baseurl }}/img/database/16-10-28-brodie/idmode4.avi.gif" style="width: 600px;" >
      <p><i>Identification Results Mode 4</i></p>
      </center>
  	</div>
   </div>
   </td>
  </tr>
  <tr>
   <td><center> 5 </center></td>
   <td><center> 94.12 </center></td>
   <td><center> 8.01 </center></td>
   <td><center> 0.05 </center></td>
   <td><center> 2.50 </center></td>
   <td><center> 3.17 </center></td>
   <td><center> 0.60 </center></td>
   <td><center> 11.66 </center></td>
   <td><center><a href="#openModal5-1">View</a></center>
    <div id="openModal5-1" class="modalDialog">
  	<div>
  		<a href="#close" title="Close" class="close">X</a>
      <center>
      <img src="{{ site.baseurl }}/img/database/16-10-28-brodie/idmode5.avi.gif" style="width: 600px;" >
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
      <img src="{{ site.baseurl }}/img/database/16-10-28-brodie/idmode5.avi.gif" style="width: 600px;" >
      <p><i>Identification Results Mode 5</i></p>
      </center>
  	</div>
   </div>
   </td>
  </tr>
  <tr>
   <td><center> 6 </center></td>
   <td><center> 120.5 </center></td>
   <td><center> 9.46 </center></td>
   <td><center> 0.03 </center></td>
   <td><center> 1.82 </center></td>
   <td><center> 2.76 </center></td>
   <td><center> 0.72 </center></td>
   <td><center> 9.75 </center></td>
   <td><center><a href="#openModal6-1">View</a></center>
    <div id="openModal6-1" class="modalDialog">
  	<div>
  		<a href="#close" title="Close" class="close">X</a>
      <center>
      <img src="{{ site.baseurl }}/img/database/16-10-28-brodie/idmode6.avi.gif" style="width: 600px;" >
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
      <img src="{{ site.baseurl }}/img/database/16-10-28-brodie/idmode6.avi.gif" style="width: 600px;" >
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
