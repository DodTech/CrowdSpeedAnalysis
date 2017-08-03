# CrowdSpeedAnalysis
Estimating Pedestrian Speed using GPS Tracks

<p align="center">
  <img src="/images/Geo.jpg", width="350"/>  
</p>

How to reproduce:
----------------
<ol>
<li>Download or clone the repo</li>
<li>Move "testarea" vector data to the appropriate directory</li>
<li>In the script "PedestrianSpeed.py", change Paths variables to you directories</li>
<li>One-click execution</li>
</ol>

The executed operations are:
----------------
<ol>
<li>  Clipping data based on "testarea"</li>
<li>  Adding Average speed field and values </li>
<li>  Adding Instant speed field and values </li>
<li>  Adding Flow direction field and values </li>
<li>  Boxplot for average speed of the tracks</li>
<li>  3D plot for the track
</ol>

<p align="center">
  <img src="/images/Geo_Areal.JPG", width="350"/>  
</p>

<h2>Results</h2>
<p align="left">
  <img src="/images/figure_1.png", width="350"/>  
</p>

<p align="right">
  <img src="/images/figure_2.png", width="350"/>  
</p>
