# All The Fishes

## README

For this assignment, I decided to focus on creating natural-looking animations. Creating animations that feel natural can be complicated, so I decided to use the JavaScript class syntax so I could keep my code organized and create similar objects, such as animated fish, more easily.

In order to make sure that all of the moving sprites in the scene were not moving to the same rhythm, I created a Counter class that I could use to assign every animated sprite in the scene a unique counter with a random starting point.

Because Pixi.js requires numerical color values, smoothly transitioning between parts of a color gradient is difficult, and I used an external library(Chroma.js) to generate an array of color samples to loop over an apply tints to a Pixi.js sprite.

To simulate bubbles, I used PIXI's Graphics class to draw a series of semi-transparent circles, and randomized their size and the direction they move along the sine wave, and increased their buoyancy in proportion to their radius to simulate how larger bubbles rise faster than smaller ones.

---

### Art Assets:

**Fish Art Assets Drawn by Sarah Lopez, used with permission**

**Rock:** https://www.pngkit.com/view/u2q8r5e6r5q8a9a9_rock-rock-pixel-art-png/

**Plant:** https://www.pngwing.com/en/free-png-zlzaj

**Randomize Icon:** https://www.pngegg.com/en/png-izzkb

**Magnifying Glass:** https://www.clipartmax.com/middle/m2H7K9H7K9i8d3Z5_magnifying-glass-pixel-art-from-the-science-pack-of-minecraft-cake-pixel/

**Pencil Placeholder:** https://www.pngmart.com/image/652931

---

### Additional Libraries Used:

Chroma.js
https://gka.github.io/chroma.js/
