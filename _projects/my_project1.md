---
title: "LiDAR point cloud video processing software"
permalink: /projects/lidar
collection: projects
date: 2020-03-20
tags: [projects]
classes: wide
header:
    teaser: "/assets/images/lidar_teaser.png"
excerpt: "pylidartracker is a traffic analysis software for pre-processing point cloud videos from VelodyneHDL LIDAR, road user classification and tracking. The software is developed at Aalborg University Denmark, Traffic Research Group"
---

<figure>
  <img src="/assets/images/lidar_teaser.png" alt="this is a placeholder image">
</figure>

`pylidartracker` is a desktop traffic analysis software for pre-processing point cloud videos captured by a static VelodyneHDL LiDAR (so far only HDL32). Pre-processed clouds can be clustered into road users whose tracks that can be exported for fruther analysis. The software is developed at Aalborg University Denmark, [Traffic Research Group](https://vbn.aau.dk/en/organisations/forskningsgruppen-for-trafik-civil/persons/) and was first used in the master thesis on the assesment of LiDAR technology for cyclist detection [source in Danish](https://projekter.aau.dk/projekter/da/studentthesis/lidar-til-cykeldetektering(da74f7e5-656d-4d62-ac8f-4fe09523d9f0).html). To try the application, visit the associated [github page](https://github.com/mihsamusev/pylidartracker).

![GitHub](https://img.shields.io/github/license/mihsamusev/pylidartracker)
![PyPI](https://img.shields.io/pypi/v/pylidartracker)

## Features
- Open UDP Network stream `.pcap` files captured by Velodyne for preview.
- pre-processing/editing in terms of coordinate transformation, clipping, background subtraction, clustering and cluster tracking.
- Save project configuration files that can be appled to the files from similar experimental setup to improve reproducibility and avoid repetitive steps in the analysis proccess.
- Output `.json` file with detected road user ID, time and position per point cloud video frame.
{: style="text-align: justify;"}

![Preview](../assets/project1/preview.gif)
