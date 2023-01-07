---
layout: project
type: project
image: img/kbrlogo.png
title: Developing Web-server Features for the Deep Learning Team 
permalink: 
# All dates must be YYYY-MM-DD format!
date: 2020-10-10
labels:
  - Python
  - DASH
  - Plotly
summary: Maintaining features for the web server
---

## Project Abstract

Machine learning is a data-driven model which requires user-given features. Deep Learning improves on that by removing user-given requirements, allowing the algorithm to assign features to itself.  Deep Learning models require a lot of computing power when trained and would need GPUs (Graphics Processing Unit) at the ready to train them. Users need a tool that they can use to check whether a GPU is available which is why the web server, “GPU status server", is created. Dash (Python framework for making dashboards) and Plotly (Graphic Engine of Dash) were used to develop the web server. The web server displays how many GPUs there are, checks whether they are available, and who is using them. It could also show additional information on specific analytics of the GPUs like memory, disk, and CPU (Central Processing Unit). These graphs give users more analytics on specific GPUs for their deep learning models. These graphs were implemented using Dash and Plotly as they allow fast and easy features on the web server. There have also been issues with users not appearing on the web server even though they are using the GPU. This bug was due to certain users having their names longer than eight characters. This was fixed by adding a new method in the code that accepts usernames longer than eight characters. In the future, an auto-refresh feature that does not need users to manually refresh the page, should be added. By adding additional features and bug fixes to the web server, the deep learning team is provided a more informational look at GPU availability for each server host. 

## Reflection

I have learned a lot from this project whether it would be learning how to use the DASH framework of python, understanding how the website is maintained, and how to manage my time with the amount given.

<img class="gif image" src=".../img/gpustatuscluster.gif">

## Progress and Presentation

Here is my [Presentation](https://docs.google.com/presentation/d/1yPRs8vxF040HdUPke632nkWaMuBigXCOH5ZVoUWNmzE/edit?usp=sharing) that I presented at my internship
