# LJ Code 201 - Day 17   
Second day of project week!  

I finished making a slider and text entry to change the tempo of the drum machine. Josh made a piano that kinda works with some piano note samples. Aaron found a ton more samples to play with for our machine and started working on making drum kits to switch between. Said worked on making play, pause, and reset buttons. Since I had finished my tempo slider, I started working on saving and loading states from the localStorage.  

I ran into some weird bugs while making the saving capability, but all of them boiled down to references. All I had to do was make copies of the objects at appropriate times so that I wouldn't be changing a supposedly saved state instead of my current grid. In the end, I got the bugs ironed out of the saving and we deployed a live page with saving, control buttons, and a synth piano.  

I started researching to figure out how to store the current state as a encoded string for exporting purposes. Currently the best idea I have is to encode each drum as two Unicode characters, for a total of 12 characters. Each drum could be one character, but I opted for legible characters instead of empty boxes.   
