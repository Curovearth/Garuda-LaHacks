# GARUDA

<img align=right src="https://github.com/Curovearth/Garuda-LaHacks/blob/main/imgs/crowd.png" width="230"/>

> **Crowd Disaster** - Unruly and irresponsible crowd behaviour due to factors like sudden entry or exits, distribution of disaster relief supplies, mass evacuation or reversal in direction of pathways cause panics and stampedes. 
~ as stated by edukemy.com

## Inspiration
Hailing from a country which consitutes 17.7% of the total world's population, a country which is rich in culture, kindness and diversity, our country INDIA. Due to the immense diversity, we as people of the country are usually part of several religious festivals where we usually meet with **CROWD**. 

## So, What problems do we usually face with Crowd?
Crowds have become more frequent around the world be it because of 
* uncontrollable rise in population
* Festive gatherings
* Religious gatherings
* and other social crowd gatherings

If we divide such formation of crowds broadly into regular events and sudden events, both have risen in numbers.  

## Garuda's Motive 

<img align=right src="https://github.com/Curovearth/Garuda-LaHacks/blob/main/gif's/close-video.gif" width="450"/>

> **Garuda's motive** : 
> Monitoring you from unimaginable heights. Because, I See You!

Garuda, in Hindu mythology, the bird (a kite or an eagle) and the vahana (mount) of the god Vishnu.
From the ancient history, birds have been considered the eyes of the sky and so is our Garuda Drone. Garuda is responsible for monitoring the regions which usually faces gathering of people in huge masses. 

Monitoring takes place with the help of a camera module which is assembled at the lower portion of the drone to cover more area as compared to the cctv camera's whose line of sight is minimised because of their static position. 

Garuda as ideated by team pi will be deployed by concerned organising authorities where it will be controlled by a skilled individual. The camera module which currently works on wifi will be able to give Realtime Monitoring.  

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

   
## Challenges we ran into
Learning always pushes you to face challenges. We came accross some interesting challenges throughout the hours of hackathon. Since it was first time for few of us to play with drone, it took us the maximum time to calibrate the transmitter and reciever for the control of flight.
We initially aimed to have a more complex algorithmic approach for realtime crowd analysis but failed to do so. 
But the best part was that throughout the process we came on to several unique algorithms which we wish to inculcate in improving this project after the hackathon.

## Accomplishments that we're proud of
We were able to satisfy ourself with the project in terms of making a hardware prototype which is responsible for realtime monitoring in terms of motion estimation of the crowd.

We learned throughout the process, made mistakes but spent each hour rectifying it and learning from our mentors.

## What's next for GARUDA
* Garuda will further utilise the implementation of much more efficient algorithms to improve the overall detection.
* We also planned to encompass a path planning algorithm such as to make it autonomous 
