+++
title = "Sound memory"
draft = false
showMetadata =  false
date = "2026-01-17"
tags = ["hardware", "midi", "web"]
category = ["wip"]
+++

Sound memory is the idea of "what if I played a game **on** a midi-controller" come to life.

Using an old Launch Pad mini, I hacked together a memory game with animal sounds (hence, "sound memory") during the Berlin Mini Game Jam in January 2026.

A convenient part about the Launch Pad is that its grid-like interface makes for an ideal playing field. Plus, with the tactile buttons, touching it is a lot of fun! It only has three colors per button (technically 4, but yellow and amber are hard to tell apart...) that makes for nice contrains in the design of the lighting.

I could see this being fun to play with kids who are not allowed any more screentime or with visually impaired people.

Technically right now, it's all web-based: web MIDI communicates with the controller, web audio plays back the sounds.

I originally wanted it all to be Rust and then hosted on a Raspberry Pi. But with the emerging player need to configure things ("sound decks" aka other sounds, size of the grid, etc) I might just stick to the web-based approach and put the config on the now empty web page.


You can find the code here: https://github.com/lislis/sound-memory
