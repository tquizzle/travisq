---
layout:      project
title:       ClamAV
date:        June 2020
image:
  path:       /assets/img/projects/ClamAV.png
  srcset:
    1920w:   
    960w:    
    480w:    
caption:     
description: >
  This container allows you a very simple way to scan a mounted directory using `clamscan`.
  It will always update the ClamAV Database, by using the standard `freshclam` before running `clamscan`. If the local ClamAV Database is up-to-date, it will check and continue.
links:
  - title:   DockerHub
    url:     https://hub.docker.com/r/tquinnelly/clamav-alpine
  - title:   Source
    url:     https://github.com/tquizzle/clamav-alpine
featured:    true
---

Well, here is some things that I hope make it to the page.