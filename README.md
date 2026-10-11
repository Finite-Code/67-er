# CP2k77

uhh, it does a spinning cyberpunk thing

## how to use it
find urself the URI (dist/uri.txt) and then just kinda use it (hope it works)

## how it works:
>  we first show the user a start button, which when clicked, we ask the JS to hide the btn and start the main loop immediately. 

PS: Ohh and it does the audio play too (usinf webaudio api ofc)
<br>

> next the main loop once started, we immediately set a alpha of 0.2 and make the canvas black, this allows some ghosting from previous frams which imo helps sell the 3D effect. <br>

> then we just get the current hardcoded postitions of center ~200*200 (since it's 400*400 canvas) and then we use a sin wave to make some basic curves! (fun math ig) and that helps us get the elliptical/circular whatever orbit effect. <br>

> then we just kinda fill in the test there, change alpha as the text travels back and forth to once again, better sell the fake 3d effect, and also we change font size for... yeah to better sell the 3d effect. <br>

> and then it just keeps looping to... yupp, better sell the 3d effect. <br>

> thx.

## how it went
So I kinda just made a spinning 6/7 logo thing. but then I thought we could do more. <br>
and so I just went ahead and added a minimal 6767Hz beep on any click or tap event. <br> <br>

at this point I was already faking 3D, getting canvas and doing audio so I also added a start button to also meet the interactive requirement, also added the drag to increase the logo orbit thing (drag cursor for wider orbit), so that I made an even stronger point. <br> <br>

## building
```
npm install
node build.mjs
```

modified the build script btw to display better stats rather than the stupid huge numbers.