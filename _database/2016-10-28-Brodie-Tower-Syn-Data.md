---
layout: post-database
title: Brodie Tower Synchronous Data
date: 2016-10-28 16:05:00
author: Yichen Zhu
setupno: 7
sensorno: 5
datadl: Available
---

## Test Information
---

#### Name: Brodie Tower, University of Liverpool

#### Address: The University of Liverpool, Brownlow Street, Liverpool, L69 3GQ

#### Type: Reinforced concrete building, 7-storeys

#### Gross dimensions: About 25m Width x 28m Depth x 25m Height

#### Sensor: 4 triaxial servo-accelerometers with individual high precision clock

#### Setups: Seven setups, each 15 min at 50 Hz.


<table>
 <tr>
  <td>
   <center>
    <iframe
src="https://www.google.com/maps/embed?pb=!1m14!1m8!1m3!1d1189.2414356949819!2d-2.967125279272631!3d53.4061899038967!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0x142bb768f021cfd9!2sBrodie+Tower!5e0!3m2!1sen!2suk!4v1477754248132" width="600" height="400" frameborder="0" style="border:0" allowfullscreen>
    </iframe>
    <p><i> Figure 1.Google Map </i></p>
   </center>
  </td>
  <td>
   <center>
    <img src="{{ site.baseurl }}/img/database/16-10-28-brodie/brodie-tower.jpg" style="width: 600px;" >
    <p><i> Figure 2. Brodie Tower </i></p>
   </center>
  </td>  
 </tr>
 <tr>
  <td>
   <center>
    <img src="{{ site.baseurl }}/img/database/16-10-28-brodie/sensor.jpg" style="width: 600px;" >
    <p><i> Figure 3. Sensor </i></p>
   </center>
  </td>
  <td>
   <center>
    <img src="{{ site.baseurl }}/img/database/16-10-28-brodie/synsetup.gif" style="width: 600px;" >
    <p><i> Figure 4. Setup </i></p>
   </center>
  </td>  
 </tr>
</table>

## Power Spectrum and Singular Value Spectrum
--------------------
<table>
 <tr>
  <td>
   <center>
    <img src="{{ site.baseurl }}/img/database/16-10-28-brodie/psd.png" style="width: 600px;" >
    <p><i> Figure 5. Root Power Spectrum of 6F </i></p>
    </center>
  </td>
  <td>
   <center>
    <img src="{{ site.baseurl }}/img/database/16-10-28-brodie/svd.png" style="width: 600px;" >
    <p><i> Figure 6. Root Singular Value Spectrum of 6F </i></p>
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
    <th style="width:20%;" colspan="2"><center>Natural Frequency (Hz)</center></th>
    <th style="width:20%;" colspan="2"><center>Damping Ratio (%)</center></th>
    <th style="width:20%;" colspan="2"><center>Modal Force PSD (ug/sqrt(Hz))</center></th>
    <th style="width:20%;" colspan="2"><center>Prediction Error PSD (ug/sqrt(Hz))</center></th>
    <th style="width:10%;" rowspan="2"><center>Mode Shape</center></th>
  </tr>
  <tr class="header">
    <th style="width:10%;" ><center>MPV</center></th>
    <th style="width:10%;" ><center>c.o.v.</center></th>
    <th style="width:10%;" ><center>MPV</center></th>
    <th style="width:10%;" ><center>c.o.v.</center></th>
    <th style="width:10%;" ><center>MPV</center></th>
    <th style="width:10%;" ><center>c.o.v.</center></th>
    <th style="width:10%;" ><center>MPV</center></th>
    <th style="width:10%;" ><center>c.o.v.</center></th>
  </tr>

<tr>
 <td><center> 1 </center></td>
 <td><center> 2.424 </center></td>
 <td><center> 0.108 </center></td>
 <td><center> 0.989 </center></td>
 <td><center> 14.709 </center></td>
 <td><center> 1.065 </center></td>
 <td><center> 8.309 </center></td>
 <td><center> 1.727 </center></td>
 <td><center> 1.384 </center></td>

 <td><center><a href="#openModal1">View</a></center>
 <div id="openModal1" class="modalDialog">
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
 <td><center> 2.705 </center></td>
 <td><center> 0.127 </center></td>
 <td><center> 0.963 </center></td>
 <td><center> 16.003 </center></td>
 <td><center> 1.089 </center></td>
 <td><center> 10.181 </center></td>
 <td><center> 1.916 </center></td>
 <td><center> 1.445 </center></td>

 <td><center><a href="#openModal2">View</a></center>
 <div id="openModal2" class="modalDialog">
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
 <td><center> 3.752 </center></td>
 <td><center> 0.066 </center></td>
 <td><center> 0.818 </center></td>
 <td><center> 9.903 </center></td>
 <td><center> 0.992 </center></td>
 <td><center> 4.389 </center></td>
 <td><center> 1.014 </center></td>
 <td><center> 0.961 </center></td>

 <td><center><a href="#openModal3">View</a></center>
 <div id="openModal3" class="modalDialog">
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
 <td><center> 7.403 </center></td>
 <td><center> 0.168 </center></td>
 <td><center> 2.644 </center></td>
 <td><center> 12.683 </center></td>
 <td><center> 0.558 </center></td>
 <td><center> 9.940 </center></td>
 <td><center> 1.859 </center></td>
 <td><center> 0.733 </center></td>

 <td><center><a href="#openModal4">View</a></center>
 <div id="openModal4" class="modalDialog">
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
 <td><center> 8.003 </center></td>
 <td><center> 0.147 </center></td>
 <td><center> 2.546 </center></td>
 <td><center> 8.403 </center></td>
 <td><center> 0.863 </center></td>
 <td><center> 6.081 </center></td>
 <td><center> 1.788 </center></td>
 <td><center> 0.621 </center></td>

 <td><center><a href="#openModal5">View</a></center>
 <div id="openModal5" class="modalDialog">
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
 <td><center> 9.464 </center></td>
 <td><center> 0.088 </center></td>
 <td><center> 1.933 </center></td>
 <td><center> 7.255 </center></td>
 <td><center> 0.866 </center></td>
 <td><center> 4.766 </center></td>
 <td><center> 2.254 </center></td>
 <td><center> 0.596 </center></td>

 <td><center><a href="#openModal6">View</a></center>
 <div id="openModal6" class="modalDialog">
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


<center>
 <img src="{{ site.baseurl }}/img/database/16-10-28-brodie/synidresults.gif" style="width: 800px;" >
 <p><i> Figure 7. Identification Results </i></p>
</center>



## Download
--------------

#### [Click here][dl] to download the data files.

[dl]: http://gofile.me/3sin6/7KGiNJPPb
