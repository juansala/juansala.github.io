---
layout: default
permalink: /projects/
---

<style>
    .image-container {
    display: flex;
    align-items: center;
    padding-bottom: 70px;
    position: relative;
    /* display: inline-block; */
}

    .image-wrapper {
    position: relative;
    display: inline-block;
}

    .image-wrapper img {
    max-width: 400px; /* Adjust the width of the image as needed */
    height: auto;
    display: block;
    transition: opacity 0.3s ease; /* Smooth fade transition */
    border-radius: 20px;
}

    .image-wrapper .overlay {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: rgba(0, 0, 0, 0.6); /* Semi-transparent background */
    color: white;
    display: flex;
    align-items: center;
    justify-content: center;
    opacity: 0;
    transition: opacity 0.3s ease; /* Smooth fade transition */
    border-radius: 20px;
}

    .image-wrapper:hover .overlay {
    opacity: 1; /* Show overlay on hover */
}

.description {
    font-size: 22px; /* Adjust the font size of the description */
    /* color: #333; Adjust the color of the description */
    font-family: "Open Sans", "Helvetica Neue", Helvetica, Arial, sans-serif;
    color: #606c71;
    margin-right: 20px; /* Adjust the spacing between the image and text */
}
</style>

# Projects (click the images to learn more!)

<div class="image-container">
    <h2 id="vision-based-autonomy-for-a-quadruped-robot">Vision-based Autonomy for a Quadruped Robot<br>
    <p class="description">Developing a ROS2 software stack to perform control, localization, and mapping on the open-source <a href="https://github.com/stanfordroboticsclub/StanfordQuadruped">Stanford pupper</a> quadruped robot. <br><br>The goals of this project are to re-enforce my robot autonomy fundamentals and to further hone my C++ skills.</p></h2>
    <div class="image-wrapper">
        <!-- <a href="https://example.com"> -->
        <img src="https://juansala.github.io/media/Images/pupper.jpg" alt="pupper">
        <div class="overlay"></div>
        <!-- </a> -->
    </div>
</div>

<div class="image-container">
    <h2 id="leader-follower-coordination-of-soft-robotic-fish">Leader-follower Coordination of Soft Robotic Fish<br>
    <p class="description">A vision-based coordination strategy for autonomous, untethered soft robotic fish that I worked on for my graduate research project. <br><br>Presented and <a href="https://ieeexplore.ieee.org/document/9965882">published</a> at the 2022 IEEE OES AUV Symposium.</p></h2>
    <div class="image-wrapper">
        <!-- <a href="https://example.com"> -->
        <img src="https://juansala.github.io/media/Images/sofi_diagram.PNG" alt="fish_diagram">
        <div class="overlay"></div>
        <!-- </a> -->
    </div>
</div>

<div class="image-container">
    <h2 id="hexapod-gazebo-simulation">Hexapod Gazebo Simulation<br>
    <p class="description">A ROS/Gazebo simulation for a hexapod robot designed for locomotion over lunar terrain. <br><br>Developed to verify continually evolving system architecture for submission to NASA BIG Idea Challenge 2022.</p></h2>
    <div class="image-wrapper">
        <a href="https://juansala.github.io/projects/worms">
        <img src="https://juansala.github.io/media/Images/worms_hex_sim.png" alt="worms_hexapod">
        <div class="overlay"></div>
        </a>
    </div>
</div>

<div class="image-container">
    <h2 id="ring-watch">Ring Watch<br>
    <p class="description">A silly watch that tells you the time via a single RGB LED... and fits on your ring finger! Based on the ATtiny85 and PCF8523 real time clock.</p></H2>
    <div class="image-wrapper">
        <a href="https://juansala.github.io/projects/ring_watch">
        <img src="https://juansala.github.io/media/Images/ring_watch_topview.png" alt="ring_hexapod">
        <div class="overlay"></div>
        </a>
    </div>
</div>

<!-- # Wall Follower -->

<!-- # Peltier Cooler -->

<!-- # Spacecraft Pose Estimator -->