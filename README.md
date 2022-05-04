<h1 align=center>GARUDA</h1>

<div align=center>

> Monitoring you from unimaginable heights. Because, I See You!

</div>

<div align=center>
    <img src="https://img.shields.io/github/forks/Curovearth/Garuda-LaHacks?style=social">  <img src="https://img.shields.io/badge/Garuda-V1-green">  <img src="https://img.shields.io/github/stars/Curovearth/Garuda-LaHacks?style=social"> <a href="https://youtu.be/Ocs9JZ9gDhU"><img src="https://img.shields.io/badge/YouTube-FF0000?style=plastic&logo=youtube&logoColor=white"/></a>
</div>
<br>
<img align=right src="https://github.com/Curovearth/Garuda-LaHacks/blob/main/imgs/crowd.png" width="230"/>

> **Crowd Disaster** - Unruly and irresponsible crowd behaviour due to factors like sudden entry or exits, distribution of disaster relief supplies, mass evacuation or reversal in direction of pathways cause panics and stampedes. 
~ as stated by edukemy.com

## Inspiration
Hailing from a country which consitutes 17.7% of the total world's population, a country which is rich in culture, kindness and diversity, our country INDIA. Due to the immense diversity, we as people of the country are usually part of several religious festivals where we usually meet with **CROWD**. 

## So, What problems do we usually face with Crowd?
Crowds have become more frequent around the world be it because of 
* Uncontrollable rise in population
* Festive gatherings
* Religious gatherings
* Other social crowd gatherings

If we divide such formation of crowds broadly into regular events and sudden events, both have risen in numbers.  

## Garuda's Motive 

<details>
    <summary>Find out, what Garuda means?</summary><br>

<img align=right src="https://github.com/Curovearth/Garuda-LaHacks/blob/main/gif's/close-video.gif" width="350"/>

> **Garuda's motive** : 
> Monitoring you from unimaginable heights. Because, I See You!

Garuda, in Hindu mythology, the bird (a kite or an eagle) and the vahana (mount) of the god Vishnu.
From the ancient history, birds have been considered the eyes of the sky and so is our Garuda Drone. Garuda is responsible for monitoring the regions which usually faces gathering of people in huge masses. 

Monitoring takes place with the help of a camera module which is assembled at the lower portion of the drone to cover more area as compared to the cctv camera's whose line of sight is minimised because of their static position. 

Garuda as ideated by team pi will be deployed by concerned organising authorities where it will be controlled by a skilled individual. The camera module which currently works on wifi will be able to give Realtime Monitoring.  

</details>
    
## Garuda - Working?

| <img width=450 src="https://github.com/Curovearth/Garuda-LaHacks/blob/main/gif's/esp32%20closeup.gif"/> | <img width=450 src="https://github.com/Curovearth/Garuda-LaHacks/blob/main/gif's/rough-fly.gif"> |
| --- | --- |
| A close up view | Testing phase inside hostel room |

<p align=center><i>Ropes tied to avoid the drone lifting up suddenly because of sudden throttle</i></p>

<p>Garuda's monitoring/analysis primarily works on the computer vision technique via ESP32 camera module.</p>
<h3>Steps..</h3>
<ul>
<li>The live stream video comes via esp32</li>
<li>We use OpenCV as a library to perform image processing techniques realtime.</li>
    <li>Dense Optical Flow: Optical flow is the pattern of apparent motion of image objects between two consecutive frames caused by the movement of object or camera. It is 2D vector field where each vector is a displacement vector showing the movement of points from first frame to second. [According to the Documentation of openCV]</li>
</ul>

## Navigating through the Repo 🧭

- Necessary details about how to play with the code: Head to <a href="https://github.com/Curovearth/Garuda-LaHacks/tree/main/3-optical%20flow#readme">Dense Optical Flow used by Garuda</a>
- Configuration of ESP32 camera with arduino: Head to <a href="https://github.com/Curovearth/Garuda-LaHacks/tree/main/ESP32#readme">ESP32 with Arduino</a>
   
## Challenges we ran into 😅

<details>
    <summary><i>If you wish to know</i></summary>

Learning always pushes you to face challenges. We came accross some interesting challenges throughout the hours of hackathon. Since it was first time for few of us to play with drone, it took us the maximum time to calibrate the transmitter and reciever for the control of flight.
We initially aimed to have a more complex algorithmic approach for realtime crowd analysis but failed to do so. 
But the best part was that throughout the process we came on to several unique algorithms which we wish to inculcate in improving this project after the hackathon.

## Accomplishments that we're proud of
We were able to satisfy ourself with the project in terms of making a hardware prototype which is responsible for realtime monitoring in terms of motion estimation of the crowd.

We learned throughout the process, made mistakes but spent each hour rectifying it and learning from our mentors.

</details>
    
## What's next for GARUDA
* Garuda will further utilise the implementation of much more efficient algorithms to improve the overall detection.
* We also planned to encompass a path planning algorithm such as to make it autonomous 

## Do you wish to contribute or Support us?

1. Let's make this project much better **together**.
2. Fork it and make a valid pull request. 
3. To look for more projects head over to the contributors profile:

| <img src="https://avatars.githubusercontent.com/u/71594140?s=100&v=4" align=center width=70> | <img src="https://avatars.githubusercontent.com/u/64013307?v=4" align=center width=70> | <img src="https://avatars.githubusercontent.com/u/72257400?s=100&v=4" align=center width=70> | <img src="https://avatars.githubusercontent.com/u/70833069?s=100&v=4" align=center width=70> |  <img src="https://avatars.githubusercontent.com/u/64500580?v=4" align=center width=70> |
| --- | --- | --- | --- | --- |
| <a href="https://github.com/anvit1618">@Anvit Agarwal</a> | <a href="https://github.com/Curovearth">@Swarup Tripathy</a> | <a href="https://github.com/yatharthagr7">@Yatharth Agarwal</a> | <a href="https://github.com/Zayd1602">@Mohammad Zayd</a> | <a href="https://github.com/shubhamppl">@Shubham Chauhan</a> |

4. If you like the project do give it a ⭐
5. Want to have discussion, feel free to hmu @ <a href="https://discord.com/channels/718336604887973939"><img src="https://img.shields.io/badge/Discord-7289DA?style=plastic&logo=discord&logoColor=white"></a>

***
