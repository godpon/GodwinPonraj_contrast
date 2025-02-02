---
title:  "Tactile Sensors for Sensing and Adaptive control in Robotic manipulators"
mathjax: true
layout: post
categories: media
contribution: Lead Contributer ( <i>Conceptualization</i> | <i>Design</i> | <i>Fabrication</i> | <i>Experimentation</i> | <i>Characterization</i> | <i>Writing</i> )
---
<style>
  .post_container {
  display: flex;
  flex-direction: row;
  align-items: center;
  justify-content: space-between;
  flex-wrap: wrap;
}

/* Set padding-left or padding-right equal to 0 in main code */
.flex-item-text {
  flex: 35%;
/*   border: 1px solid blue; */
  padding-left:1em;
  padding-right:1em;
  justify-content: space-around;
}

.flex-item-pic {
  flex: 58%;
/*   border: 1px solid blue; */
  padding: 5px;
  align-content: space-around;
}

/* Responsive layout - makes a one column layout instead of a two-column layout */
@media (max-width: 800px) {
  .post_container {
    flex-direction: column;
  }
  .flex-item-text{
    padding: 0px;
  }
  .flex-item-pic{
    max-width: 90%;
  }
}

</style>
<!--
<div align="right" style="margin-top: 0px; padding-top: 0px;">
  Contribution: Lead (Conceptualisation | Design | Experimentation | Characterisation | Writing)
</div>
-->
<div class="post_container">
      <div class="flex-item-pic">
        <img src="/GodwinPonraj/assets/Fig_Tact_manipulator.jpg" height = "100%">
      </div>
      <div class="flex-item-text" align="justify" style="padding-right:0px">
        The ability to sense and measure object properties based on touch is known as tactile sensing. The flexibility and dexterity of soft robots can be fully explored, only with efficient tactile feedback from the environment or the objects the robot interact with. This work discusses the development of a soft fabric based piezoresistive tactile sensor, the related calibration experiments, procedures and some application examples like orientation estimation and tactile feedback control. 
      </div>
</div>

<!--more-->
<br>
<div class="post_container">
      <div class="flex-item-text" align="justify" style="padding-left:0px">
        To hold an object firmly and do the required task, the orientation of the object with respect to the robotic hand gripper is one of the necessary key information. Humans can sense the orientation of an object based on vision, kinesthetic sensation, or touch sensation. Similarly, robots shall also be able to estimate grasped object orientation just based on tactile sensing without knowing manipulator kinesthetic or kinematics. 
      </div>
      <div class="flex-item-pic">
        <video width="100%" height= "100%" controls>
          <source src="/GodwinPonraj/assets/Vid_Tilt_sensing_compressed.mp4" type="video/mp4">
          Your browser does not support mp4 video.
        </video>
      </div>
</div>

A new approach for object orientation estimation from a multilayered tactile sensor was introduced in this work. Video above shows the proposed mechanism of tilt sensing based on the tactile sensor inputs. 

<div class="post_container">
      <div class="flex-item-text" align="justify" style="padding-left:0px">
        The feedback control is demonstrated in a cutting task wherein the tactile sensor data was used to identify the different cutting phases. A completely fabric based sensor was used in this task by using conductive fabric instead of printed traces on PET substrate. Fabric based sensors are flexible, stretchable and can confer to both hard and soft surfaces easily. The task at hand is to cut a slice of bread and stop automatically when the knife hits the cutting board. 
      </div>
      <div class="flex-item-pic">
        <video width="100%" height= "100%" controls>
          <source src="/GodwinPonraj/assets/Vid_bread_cutting.mp4" type="video/mp4">
          Your browser does not support mp4 video.
        </video>
      </div>
</div>

A soft pneumatically controlled robotic gripper similar to that in was used to grab the knife and cut the bread. The tactile sensor is attached to the interior surface of one of the fingers of the soft robotic gripper holding the knife. The force exerted by the hand while the cutting action was performed was monitored continuously via the sensor reading. The sensor measured a periodic pattern during the cutting process due to the change in force exerted by the knife on the tactile sensor during the to and fro motions of the cutting action. When the knife hits the board, the amplitude of the signal reduces due to the relatively smoother surface of the cutting board. This change in pattern of the sensor reading is used to detect the point when to stop the cutting action. 

The tactile sensors developed in this project formed the basis of several other tactile based projects in the future. Some examples include providing tactile feedback for soft-material enhanced gripper for manipulation of fragile and soft objects, slip detection and correction, tactile sensing for clinical and surgical devices, etc.

<div style="padding:10px; border-bottom: 1px solid lightgray; border-left: 5px solid darkgray;">
<u>Related Publications:</u><br>
<ol>
<li><b><i>G. Ponraj</i></b> and H. Ren, “Estimation of Object Orientation Using Conductive Ink and Fabric Based Multilayered Tactile Sensor,” in 2018 IEEE International Conference on Robotics and Automation (ICRA), May 2018, pp. 4135–4141, <a href="https://ieeexplore.ieee.org/document/8461031/">doi: 10.1109/ICRA.2018.8461031</a>.</li>

<li><b><i>G. Ponraj</i></b>, S. K. Kirthika, N. V. Thakor, C. H. Yeow, S. L. Kukreja, and H. Ren, “Development of flexible fabric based tactile sensor for closed loop control of soft robotic actuator,” in IEEE International Conference on Automation Science and Engineering, Aug. 2017, vol. 2017-Augus, pp. 1451–1456, <a href="http://ieeexplore.ieee.org/document/8256308/">doi: 10.1109/COASE.2017.8256308</a>.</li>

<li>S. K. Kirthika, <b><i>G. Ponraj</i></b>, and H. Ren, “Fabrication and comparative study on sensing characteristics of soft textile-layered tactile sensors,” IEEE sensors Lett., vol. 1, no. 3, pp. 1–4, Jun. 2017, <a href="https://ieeexplore.ieee.org/abstract/document/7934368">doi: 10.1109/LSENS.2017.2708425</a>.</li>

<li>I. N. Kalupahana, <b><i>G. Ponraj</i></b>, G. Zhu, C. Li, and H. Ren, “Real-time object detection and manipulation using biomimetic musculoskeletal soft robotic grasper addressing robotic fan-handling challenge,” in Control Systems Design of Bio-Robotics and Bio-mechatronics with Advanced Applications, Academic Press, 2020, pp. 115–141, <a href="https://doi.org/10.1016/B978-0-12-817463-0.00004-6">doi: /10.1016/B978-0-12-817463-0.00004-6</a>.</li>
</ol>
</div>
