---
layout:      page
title:       ClamAV - A Docker Image
date:        June 2020
image:
  path:       /assets/img/projects/ClamAV.png
  srcset:
    1920w:   
    960w:    
    480w:    
caption:     
categories:  projects
featured:    true
permalink:   /projects/clamav/
description: >
  This container allows you a very simple way to scan a mounted directory using `clamscan`.
  It will always update the ClamAV Database, by using the standard `freshclam` before running `clamscan`. If the local ClamAV Database is up-to-date, it will check and continue.
hide_description: true
links:
  - title:   DockerHub
    url:     https://hub.docker.com/r/tquinnelly/clamav-alpine
  - title:   Source
    url:     https://github.com/tquizzle/clamav-alpine
---

# ClamAV scanning Docker container based on Alpine

![Docker Pulls](https://img.shields.io/docker/pulls/tquinnelly/clamav-alpine.svg?style=for-the-badge)

[<img src="https://img.shields.io/badge/PayPal-Docker%20Love-informational?style=for-the-badge">](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=FMYAA6ZDFC4BE&source=url)

This container allows you a very simple way to scan a mounted directory using `clamscan`.

It will always update the ClamAV Database, by using the standard `freshclam` before running `clamscan`.
If the local ClamAV Database is up-to-date, it will check and continue.

* [DockerHub](https://hub.docker.com/r/tquinnelly/clamav-alpine)
* [Source - Github](https://github.com/tquizzle/clamav-alpine)