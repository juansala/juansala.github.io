---
layout: default
# title: Example project
# description: Example project description
permalink: /projects/kuka
---

# Zero-G Tumbling Target Capture via Robot Arm

In this project for my Manipulation class, I implemented IK-based trajectory control and motion planning for capture of zero-gravity tumbling objects using the Drake simulation toolbox and a Kuka iiwa robot arm model provided within the toolbox. At a high-level, it uses a pseudo-inverse controller and a pre-specified trajectory of end-effector poses in order to navigate the gripper to the correct capture pose and activate the gripper to stop the target. 

For more, feel free to check out the [technical report](https://juansala.github.io/media/Docs/6_843_Final_Report.pdf) and the short demo clip below.

<p align="center">
<iframe 
    width="560" 
    height="315" 
    src="https://www.youtube.com/embed/hcL-fXBQbfo?si=D1eAkj3UT_ZwR1Rs" 
    title="YouTube video player" 
    frameborder="0" 
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
    allowfullscreen>
</iframe>
</p>