# HEN Hydrasynth HTML starter

## Your sketch

Your sketch exists in `index.html`.

The sketch contains some utility functions, `random()` and `map()` taken from p5js.

There is small snippet for helping with interactions. A mouse click will update some variables used in the sketch:

```
let mainOscFreq = random(60, 100);
let mainOscSync = random(2);
let mainOscOff = random(1);

// Update params on click
hydra.canvas.addEventListener('click', resetVars)

function resetVars() {
  mainOscFreq = random(60, 100);
  mainOscSync = random(2);
  mainOscOff = random(1);
}
```

## Minting

- Replace `thumb.png` with a still image of your sketch (must be named `thumb`). This can also be a gif or video, just remember to update the reference to it in `index.html`.
- Upload a zip file with the contents of `src/`