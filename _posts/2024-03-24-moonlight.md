---
title: Links for Gaming
author: Hohastudios
date: 2024-03-24
category: blog
layout: post
---

# Using moonlight

Stream games from a host PC with NVIDIA gfx card to another 

1. Download install moonlight client

https://moonlight-stream.org/?ref=evanw.com

2. Install sunshine on server. GeForce experience no longer supported as of writing.  

3. Host server must have a display connected. Seems cannot run headless

4. Connect moonlight client to remote host

5. A pin is required to connect, this will pop up on the sunshine server admin, at localhost:47990

6. Controller will not work until vgiemu has been installed. At time of writing, no longer maintain but still works

https://github.com/nefarius/ViGEmBus/releases

7a. (Optional) connecting ps4 controller might not work unless ds4 is installed via https://ds4-windows.com/

7b. (Optional) hidHide is needed in order to avoid the infamous multi controller issue. Ds4 emulates a controller, but real controller will double entry and render the controller not usable  

https://github.com/nefarius/HidHide

