---
layout: post
title: Performance 400
description:
image: assets/images/tracking_exemple.jpg
nav-menu: false
show_tile: false
---

<h3>The Context</h3>
<p>Performance 400 is a work project, we developed in a team of 2.</p>
<h3>The Goal</h3>
<p>The goal was to be able to track a runner and compute it's speed. This project was made in partnership with Agnès Raharolahy, a french runner.</p>
<h3>The Technologies</h3>
<p>In order to do that, we used Python and the OpenCV library for video analysis. This allowed us to detect movement in the video, go from 2D to 3D in order to compute the speed of the runner. We created an API using Flask in order to make all the functions accessible using an app. The app was coded using Flutter.
A part of the project was also setting up a Linux Server to host the API and communicate wit the GoPro cameras.</p>

<h3>The Process</h3>
<img src="/forty-jekyll-theme/assets/images/preformace4001.png" alt="" data-position="top center" />

<p>1. The user needed to set up the camera around the track. For each camera a calibration must be done with known points. This enables the camera to detect the 3D plan of the world and go from2D to 3D. This process takes several minutes per camera because the user, through the app, must select the desired points.</p>

<p>2. Once all the cameras are installed, the run can be filmed. The user must start all the cameras before the run starts.</p>
<p>3. After the run is finished, the videos are read by the computer. For each videos, the computer detects movement in the first frames (as seen on the image in the header). The user has to select the right movement, representing the runner.</p>
<p>4. The computer then renders all the 3D points. To render a 3D point the computer uses two 2D points (from 2 different cameras) from the same time frame.</p>
<p>5. With the 3D points, the speed can then be render for the user.</p>

<h3>And now?</h3>
<p>THis technology and process was not as successful as we hoped. The results were very accurate for a small distance (3/4 meters) with 3 cameras. However, on the scale of a track field, the amount of cameras needed for a full 400m run was too big. On top of that, more cameras meant more time needed to set up everything. The project was stopped as it did not fulfill the requirements of the client.</p>

<h3>My Contribution</h3>
<p>I was one of the main developers on this project. My main focus was on the video analysis and 3D rendering. I also helped on the development of the app.</p>