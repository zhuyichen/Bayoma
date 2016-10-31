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

#### Gross dimensions: (some indicative dimension just to give an idea)

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

<center>
 <img src="{{ site.baseurl }}/img/database/16-10-28-brodie/Syn-6F-SVD.jpg" style="width: 600px;" >
 <p><i> Figure 5. SVD of 6F </i></p>
</center>


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
    <td><center>1</center></td>
    <td><center>2.710</center></td>
    <td><center>2.710</center></td>
    <td><center>2.710</center></td>
    <td><center>2222</center></td>
    <td><center>1</center></td>
    <td><center>1</center></td>
    <td><center>1</center></td>
    <td><center>1</center></td>
    <td><center><button id="myBtn">View</button></center>
     <!-- The Modal -->
     <div id="myModal" class="modal">
     <!-- Modal content -->
      <div class="modal-content">
      <span class="close">x</span>
      <center>
      <img src="{{ site.baseurl }}/img/database/16-10-28-brodie/synidresults.gif" style="width: 600px;" >
      <p><i> Figure 6. Identification Results </i></p>
      </center>
      </div>
     </div>

    </td>
  </tr>

</table>


<center>
 <img src="{{ site.baseurl }}/img/database/16-10-28-brodie/synidresults.gif" style="width: 600px;" >
 <p><i> Figure 6. Identification Results </i></p>
</center>



## Download
--------------

#### [Click here][dl] to download the data files.

[dl]: http://gofile.me/3sin6/7KGiNJPPb



<script>
// Get the modal
var modal = document.getElementById('myModal');

// Get the button that opens the modal
var btn = document.getElementById("myBtn");

// Get the <span> element that closes the modal
var span = document.getElementsByClassName("close")[0];

// When the user clicks the button, open the modal
btn.onclick = function() {
    modal.style.display = "block";
}

// When the user clicks on <span> (x), close the modal
span.onclick = function() {
    modal.style.display = "none";
}

// When the user clicks anywhere outside of the modal, close it
window.onclick = function(event) {
    if (event.target == modal) {
        modal.style.display = "none";
    }
}
</script>
