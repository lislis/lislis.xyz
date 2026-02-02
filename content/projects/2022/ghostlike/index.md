+++
title = "ghostlike"
draft = false
showMetadata =  false
date = "2023-02-25"
tags = ["theater", "performance", "participation", "software", "hardware"]
category = ["finished"]
[params]
photocredit = "Louisa-Marie Nübel"
+++

The first part of the "21st century hauntings" trilogy, ghostlike, explores the motive of the ghost and hauntings.

Through the trope of exploring a haunted mansion, the performers encounter ghosts that haunt their communities, confront people who have ghosted them and coming to terms with being the ghost outside of mainsteam society.

The entire performance is participatory: the audience receives flashligths upon entering and the stage is fitted with three boxes, marked with differently colored LEDs.

At certain points in the narrative, when the ghosts are encountered, the audience has to solve small, light-based puzzles by shining their flashlights at the boxes.

Is the puzzle solved in time, the ghost is banned and a special performance is unlocked. If the timer runs out, the haunting continues and the performance restarts at the lobby of the mansion.

Depending on how the audience solved the puzzles, there are two possible endings.

Technically, each sensor box had an ESP32 and a photoresistor inside it (and LEDs and a powerbank). The ESPs continuously send their readings to a Raspberry PI that acts as an access point and also hosts a server and web-interface. From the FOH I can oversee the status of the boxes, control the LEDs and thus play the puzzles with the audience. I do however communicate the puzzle outcome to the light and sound technicians by talking.

You can find the code for the
- sensor boxes here https://github.com/lislis/ghostlight-sketches
- server and dashboard here https://github.com/lislis/ghostlight

I worked on this piece together with STERNA | PAU as part of my [media arts fellowship by the federal state NRW](https://www.medienwerk.nrw/en/projects/sterna-pau-lisa-passing-audience-participation-lab-2/).


{{< youtube 8fFKJ6TCZ7s>}}


More at https://www.sternapau.de/projekte/ghostlike/
