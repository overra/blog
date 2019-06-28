---
title: Toggling Smart Devices with IFTTT, Airtable and Webhooks
date: "2019-06-28"
description: How to use IFTTT, Airtable and Webhooks to toggle LIFX Lights and
  a Wyze Cam when multiple people leave and come home.
---

# A little back story

I've owned some LIFX bulbs for a while now and I used the app to toggle the
lights off and on. We later bought a Google Home and then instead of opening
an app, my wife or I could just ask the assitant to do it. This wasn't smart
or convenient enough for me.

So I setup some applets in IFTTT to do it
based on geolocation. This turned out to not be as reliable as I would have
hoped but it was good enough. Then more recently I purchased a Wyze Cam Pan to
keep an eye on my apartment when I'm away. I decided I didn't want the camera
to be on at all times so again I decided to create an IFTTT applet to handle it.
This time using the Android wifi connect/disconnect trigger. Then I started
thinking of a trigger that requires both my wife and I leaving before turning
off the lights and turning on the camera. There didn't seem to be an easy way of
doing this with IFTTT alone so I decided that I would make my own solution.
