---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">

<script>
var _hmt = _hmt || [];
(function() {
  var hm = document.createElement("script");
  hm.src = "https://hm.baidu.com/hm.js?3e3ac010d74e14b7ea608faa27aacc7d";
  var s = document.getElementsByTagName("script")[0]; 
  s.parentNode.insertBefore(hm, s);
})();
</script>

<!-- Global site tag (gtag.js) - Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-VZEWKM2DNL"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-VZEWKM2DNL');
</script>

  Hello,I am a graduate student of University of Electronic Science and Technology, majoring in signal and information processing, mainly focusing on visual target tracking. After my master's degree in 2019, I worked as a senior algorithm engineer at DiDi Chuxing.  
 
  **<font color=red>I am currently looking for a Ph.D. position. Contact me if you are interested in supervising me!</font><br />**

  Click [CV](/cv) to know more detail of me.


Research interests
======
My research interests focus on Robotics, Computer Vision, and UAVs.


Education
======
* M.S. in Signal and Information Processing, UESTC, July 2019 at [IDIP-lab](https://idiplab.uestc.cn/) under the supervision of Prof. Peng Zhenming.

* B.S. in Optical Information Science and Technology, UESTC, June 2016

Work experience
======
*  2019.7 - 2022.4: Senior Machine Learning Engineer, DiDi Chuxing  
   * **ETA, Map team:** Train ML\DL models to predict accurate arrival time (ETAs) to calculate fares, estimate pickup times, match riders to drivers, plan deliveries, and more. The ETA model's QPS is the highest at DiDi.


* 2015.10 - 2016.4: Intern, DJI.
  *  **Flight control group:** Develop BSP and HAL layer code and adapt sensors such as barometer, IMU, and UWB. I am also involved in developing the open platform OnboardSDK.


Innovation Startup
======
* Founder of **Yuanliu Automatic Co. Ltd.**  
  * Uses tilt-rotor VTOL fixed-wing UAVs to collect aerial images of tobacco fields in mountainous areas of Guizhou.
  * Automatically tobacco Seedling detects algorithm for quantity counting. 
  * System has been launched into production.

* Certification 
  * Company got certified  "Certificate of conformity of high and new-tech enterprise" (Issued by Science and Technology Department of Sichuan Province)

* Fields of Bussiness
  * Tobacco planting manage system  

  * Automatically tobacco Seedling quantity counting.  

  * Almost the same as manual counting.  
<div class="w3-content w3-display-container" style="max-width:600px;max-height:400px;">
   <!-- Slideshow -->
   <!-- 
            Tobacco planting manage system. 
         Automatically tobacco detect. 
         Almost the same as manual counting. 
         Company got certified  "Certificate of conformity of high and new-tech enterprise. 

   --->
   <div class="w3-display-container mySlides2">
      <img  src="files/tobacco2.png"  style="width:600px;height:400px">
        <div class="w3-display-bottomleft w3-large w3-container w3-padding-16 w3-black">
          Tobacco planting manage system.
        </div>
   </div>

   <div class="w3-display-container mySlides2">
      <img  src="files/tobacco_detect.png" style="width:600px;height:400px">
        <div class="w3-display-bottomleft w3-large w3-container w3-padding-16 w3-black">
            Automatically tobacco detect.
        </div>
   </div>

   <div class="w3-display-container mySlides2">
      <img  src="files/tobacco_count.png" style="width:600px;height:400px">
        <div class="w3-display-bottomleft w3-large w3-container w3-padding-16 w3-black">
            Almost the same as manual counting. 
        </div>
   </div> 

   <div class="w3-display-container mySlides2">
      <img  src="files/YL-certifi.jpg" style="width:600px;height:400px">
        <div class="w3-display-bottomleft w3-large w3-container w3-padding-16 w3-black">
          Company got certified  "Certificate of conformity of high and new-tech enterprise.
        </div>
   </div>
    <div class="w3-display-container mySlides2">
      <img  src="files/UAV_takeoff_Moment.jpg" style="width:600px;height:400px">
        <div class="w3-display-bottomleft w3-container w3-padding-16 w3-black">
          Our first prototype tilt-rotor STOL airplane. 
        </div>
    </div>
    
   <button class="w3-button w3-black w3-display-left" onclick="plusDivs(-1)">&#10094;</button>
   <button class="w3-button w3-black w3-display-right" onclick="plusDivs(1)">&#10095;</button>
</div>
<div class="w3-center w3-display-bottommiddle" style="width:100%">
    <span class="w3-badge demo w3-border" onclick="currentDiv(1)"></span>
    <span class="w3-badge demo w3-border" onclick="currentDiv(2)"></span>
    <span class="w3-badge demo w3-border" onclick="currentDiv(3)"></span>
    <span class="w3-badge demo w3-border" onclick="currentDiv(4)"></span>
    <span class="w3-badge demo w3-border" onclick="currentDiv(5)"></span>
  </div> 
<script>
   var slideIndex = 1;
   showDivs(slideIndex);
   
   function plusDivs(n) {
     showDivs(slideIndex += n);
   }
   
   function showDivs(n) {
     var i;
     var x = document.getElementsByClassName("mySlides2");
     if (n > x.length) {slideIndex = 1}
     if (n < 1) {slideIndex = x.length}
     for (i = 0; i < x.length; i++) {
       x[i].style.display = "none";  
     }
     x[slideIndex-1].style.display = "block";  
   }
</script>


Competitions 
======
* **National Champion** on 2015 ABU Asia-Pacific Robot Contest(Robocon)    
  * Badminton robot we build that can play well with humans.  

  <video id="video" controls="" preload="none" poster="files/badminton-robot_Moment.jpg" width="600px" height="400px" autoplay muted>
        <source id="mp4" src="files/badminton-robot.mp4" type="video/mp4" height="500px" width="700px">
  </videos>

* **National Second prize** on 2015 National Undergraduate Electronic Design Contest
  <img src="files/UAV-2015.jpg" style="width:600px; height:400px;">
 <div class="w3-display-bottomleft w3-container w3-padding-16 w3-black">
    UAV completed the tasks of fixed-point take-off and landing, picking up items, and line patrol.
  </div>  

Publication
======
Thesis

[1]卢耀坤. 复杂场景运动目标跟踪算法研究[D].电子科技大学,2019.  [[brief]](files/brief-of-dissertation.pdf)  [[pdf]](files/thesis-tracking.pdf)


Skills
======
* C++\Python\Scala
* Tensorflow\Spark
* OpenCV\ROS
*	CET-6