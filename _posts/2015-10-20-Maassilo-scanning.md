---
layout: post
title:  "Scanning of the Maassilo building (Rotterdam) with the Leica scanner and the Google Tango tablet"
categories: news
date:   2015-10-20
author: Abdoulaye Diakité
---

<div align="justify">
<font size="4">

<div class="row">
  <div class="col-sm-12 col-md-4">
    <img src="/img/2015/scanning_maassilo5.jpg" style='height: 100%; width: 100%; object-fit: contain' />
  </div>
	<div class="col-sm-12 col-md-4">
    <img src="/img/2015/scanning_maassilo3.jpg" style='height: 100%; width: 100%; object-fit: contain' />
  </div>
  <div class="col-sm-12 col-md-4">
    <img src="/img/2015/scanning_maassilo2.jpg" style='height: 100%; width: 100%; object-fit: contain' />
  </div>
</div>

<br> <br>

Always aiming at producing 3D models that can be used to test the tools developed in the SIMs3D project, people from TU Delft were at the Maassilo building in Rotterdam to perform laser scanning of some parts of the building.
The Maassilo, known to be a huge building was a particular challenge for this task. We used the Leica scanner for the building ground rooms that have a high ceiling (6 meters), and we dedicated the Tango to the underground floor 
(approximately 2.5 meters). Of course, due to the size of the rooms of the building several scanning was necessary to cover enough data.

<br> <br> <br>

<div class="row">
  <div class="col-sm-12 col-md-4">
    <img src="/img/2015/maassilo_obj02.png" style='height: 100%; width: 100%; object-fit: contain' />
  </div>
	<div class="col-sm-12 col-md-4">
    <img src="/img/2015/maassilo_obj04.png" style='height: 100%; width: 100%; object-fit: contain' />
  </div>
  <div class="col-sm-12 col-md-4">
    <img src="/img/2015/maassilo_obj06.png" style='height: 100%; width: 100%; object-fit: contain' />
  </div>
</div>

<br> <br>

<div class="row">
  <div class="col-sm-12 col-md-4">
    <img src="/img/2015/maassilo_obj07.png" style='height: 100%; width: 100%; object-fit: contain' />
  </div>
	<div class="col-sm-12 col-md-4">
    <img src="/img/2015/maassilo_obj09.png" style='height: 100%; width: 100%; object-fit: contain' />
  </div>
  <div class="col-sm-12 col-md-4">
    <img src="/img/2015/maassilo_obj10.png" style='height: 100%; width: 100%; object-fit: contain' />
  </div>
</div>

<br> <br>

<div class="row">
  <div class="col-sm-12 col-md-4">
    <img src="/img/2015/maassilo_obj11.png" style='height: 100%; width: 100%; object-fit: contain' />
  </div>
	<div class="col-sm-12 col-md-4">
    <img src="/img/2015/maassilo_obj13.png" style='height: 100%; width: 100%; object-fit: contain' />
  </div>
  <div class="col-sm-12 col-md-4">
    <img src="/img/2015/maassilo_obj14.png" style='height: 100%; width: 100%; object-fit: contain' />
  </div>
</div>

<br> <br>

The images above illustrate the meshes obtained from the Tango tablet. The latter provides a very interesting app named <a href="https://developers.google.com/project-tango/tools/constructor">Project Tango Constructor</a> and available on 
Google Play platform, that allows to build real time meshes on the flight. It uses all the main sensors integrated to the tablet to continuously track its position while performing acquisition of the 3D data. The advantage of this
app is that large surfaces can be covered without any need of registration and a large type of spaces including anywhere the hand can reach can also be covered. One can see on the screen the surface that has been scanned, 
and one can navigate in the virtual scene as he walks in the real world that was acquired. This gives an idea of the numerous applications that such tool can make feasible, mostly in the indoor buidling modeling and navigation area.

<br> <br>

Nevertheless, some limitations has to be considered. The depth sensor of the tablet works in a range between 0.5 and 4 meters, thus when one gets too close of an object or too far from it, the information is 
naturally not perceived. Furthermore, in the case of big buildings such as Maassilo, the battery issue has also to be considered. Indeed, since the meshing is performed in real time, the more one acquire new points the more 
the size of the data increases and the processing becomes greedy in performance. Thus after using the tablet for approximately more than 1 hour and 20 minutes, it heats up and the processing of the global mesh may fail while 
getting saved, leading to a waste of all the acquired data. 

<br> <br>

So after loosing few data acquired we decided to make several short scannings of 15-25 minutes instead of a long single ones. We will therefore have to face the registration issue anyway. The underground rooms of the Maassilo are 
more complex due the old manifacture machines they contain. Even for a human it is hard to cover all the space by walk, and as scanning with the tablet is very intuitive, one will naturally try to fill all the gaps that appear 
on the screen as he goes and that represent the non acquired surfaces. But others problems of the acquisition comes from the multiple movements that may make the Tango loses its track of the position and result in a displacement of 
the acquired data. Scanning too empty spaces or places without many patterns also results in the same behavior. We finally performed the scanning in 11 times, requiring two battery charging (that goes quite fast with the mini-dock 
provided with the tablet). We will now study how to perform registration on all those data and also how we exploit them efficiently in the SIMs3D project. 

<br> <br>

A deeper study including more details, stats and the results of the other scanners is coming soon.

</font>
</div>
