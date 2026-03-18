---
title: "Campus Map Navigator: Multi-Floor Indoor Routing System"
date: 2026-01-15
draft: false
description: "A highly complex multi-floor indoor navigation system modeling 1,395 nodes and 3,000+ edges using graph data structures, C++17, and a Django web interface."
featured_image: "images/projects/campus-map.png"
tags: ["C++", "Python", "Django", "Algorithms", "Data Engineering"]
---

I am excited to showcase the **Campus Map Navigator**, a comprehensive indoor routing engine designed to solve complex multi-floor navigation challenges. This project bridges the gap between high-performance backend algorithmic processing and interactive web visualization.

![Campus Map Interface](/images/campus-map.png)
*Interactive map visualization powered by Django and HTML5 Canvas*

## The Challenge

Navigating massive university campuses or corporate buildings often involves complex variables like changing floors, locating elevators versus stairs, and finding the absolute closest amenities. The challenge was to build a system capable of calculating these routes instantaneously across a massive network of pathways.

## The Solution

I architected a full-stack solution utilizing a high-performance C++ backend paired with a flexible Django web application:

- **Graph Architecture**: Modeled the environment using graph data structures containing 1,395 nodes and over 3,000 edges.
- **Advanced Routing**: Implemented Dijkstra's algorithm in C++17 to handle optimized single-floor and cross-floor traversals.
- **Smart Filtering**: Added features for stair vs. elevator preference filtering and nearest-location search capabilities.
- **Interactive UI**: Built a front-end using JavaScript and HTML5 Canvas to visually draw the calculated paths on the map in real-time.

## Technical Stack

The system relies on a seamless integration between different technologies:

- **Backend Engine**: C++17 for raw computational speed and memory management.
- **Web Framework**: Django (Python 3) to handle HTTP requests and serve the application.
- **API Integration**: Integrated the C++ engine with the Django backend via subprocesses and a JSON API pipeline.
- **Frontend**: HTML5 Canvas, JavaScript, CSS.

## Results & Impact

The result is a lightning-fast routing tool that proves the viability of using C++ for heavy backend computation while maintaining a responsive, user-friendly web interface. It heavily utilized my core competencies in applied data structures and algorithm optimization.

Check out the source code and documentation on GitHub!

[View Project on GitHub](https://github.com/M0hamedEzat/Campus-Map-Navigator)