---
title: Thhar - A Go 3D Rendering Engine
date: 2024-04-16
tags:
  - blog
  - scienceCup
  - 3D
---

Thhar is an open-source 3D rendering engine written in Go. It utilizes the ebiten library for rendering complex shapes and supports the Wavefront .obj file format for 3D models.

Designed for ease of use, Thhar integrates with existing ebiten applications through a simple. Render function call. It offers camera control functionalities and allows for the use of multiple cameras within a scene.

Integration of the engine with ebiten allows you to only partially render in 3d. And Save on performance using 2D vector graphics when 3d rendering is not needed. Check out the [demo](/demos) page for more information and the [Github](https://github.com/tomasz-brak/thhar-3d) repo for more information on setup and usage.

This program originated in from the [Motorola Science Hub](/blog/motorolaScienceCup) competition. 

Inspired by existing Python projects, Thhar is currently under development and welcomes community contributions.
