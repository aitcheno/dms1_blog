---
title: Blog Post 4 Week Eight Session Two Space and Sound
published_at: 2024-05-12
disable_html_sanitization: true
---
## Problems!
Unity crashed and rebooted my whole PC while I was playtesting and I lost a lot of my progress. It hurts and makes me less motivated since I have to redo what I've done. I just need to ctrl s every time I add something new because I really don't want this to happen again. 

Hopefully I can get to the bottom of why its crashing and fix it.

## Progress
I have worked further on the textures and assets and have created the more comforting room that the player will walk up into once the stairs appear. 
![Room 2](/w08s2/room3.PNG)
I used a simple plaster texture for the walls and made it a nice dark green. I decorated the room with assets that I'd say make a room quite cosy. I wanted the room to feel a lot more welcoming than the spawn room.

I added buildings for outside for the first room. I'll make sure to add a screenshot here.

### Blender Attempt
I had a crack at making my own asset for the temple/shrine. This was because I couldn't find a suitable one somebody else has made that would house the cat statue...
![Blender](/w08s2/blender1.PNG)
I got my head around blender quite quickly, but as soon as I tried to add textures it all seemed like too much effort. I gave up sadly.


### Change of Plans
While searching for a nice big window to let light into the room, I discovered a broken one. This ultimately changed the direction of my enviroment. Instead of exiting the above room on the right, I made it so the player can climb the couch like a cat would. Onto the box and up the ladder. This addition is particularly engaging, and I think will give the player a sense of being the cat. 

Because of this, I adjusted the scale of the second room, and made it so the room and its assets are a lot larger than previously in the environment. It's sort of an Alice in Wonderland type effect. 

In the second room, the player feels cat sized and is exposed to cat related objects. 

Overall, this climbing through a broken window idea has changed some ideas within my concept, and leaves the map to be a bit more linear. Due to the placement of the window, the player has a clear direction forward.



## Sound
Keep in mind, I'm slowly adding to this section each time I update the sound in my environment.

The sources and attributions of the sounds can be found here:

https://docs.google.com/document/d/1W8nrhV-UkXEjHD3sosEKTuxc-BzSzfR4Sg4QFOfRVms/edit?usp=sharing 

### Light Hum
![Light Sound](/w08s2/slight.PNG)
I added the hum sound onto the lights in the first section of the environment. Each light differs in pitch a little bit just for some clear change when you move around the environment.

I had trouble with the sound not fading away once you moved away, but I adjusted the reach of the sound and found that the distance rolloff didn't go to down to 0.0. Fixed that and they worked perfectly. Really felt like the sound was coming from above

### Ambient Outdoor Sound
![Ambient Sound](/w08s2/ambient.PNG)
Once I had created the outdoor terrain, as seen in the next blog, I added an audio source in the sky that created the sense of outdoors. It features bird noises and an overall hum. It fits nicely in the area and I made sure it loops.

### Cat Meows and Music
Now here's the more creative bit of sound design. I have placed lamps across the outdoor environment. Each of these lamps will play a different ambient melody I have created.

They are very simply in the key of C and sine waves. I chose this because I wanted the sounds to be very pure and tranquil in that way. I also didn't want there to be any severe dissonance so all the notes are diatonic

They each loop at different rates, which creates an almost everchanging overlapping of notes. The music is pulseless and free, and that's how I want the player to feel: tranquil, free and experiencing something almost religious in nature

![REAPER](/w08s2/projectstems.PNG)
Here is my reaper project. I exported each track individually, not the master. Then I assigned each differing sound to either a lamp on the path or the cat statues at the end.
![Lamp Sound](/w08s2/spole.PNG)

The main three cat statues have the most resolving audio, where the large statue simply plays a C major chord that just changes voicing. This is to signify the end of the environment and a clear resolution.