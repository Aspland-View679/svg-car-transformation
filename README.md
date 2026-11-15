# SVG Car Transformation

An interactive web page that demonstrates two-dimensional translation and rotation using SVG, CSS Grid and vanilla JavaScript.

## Features

- A red car drawn with SVG shapes on a yellow canvas.
- Directional buttons to move the car up, down, left or right in 10-pixel increments.
- A numeric input to set the car's rotation angle in degrees.
- Combined translation and rotation, with position maintained between button presses.
- CSS Grid layout for the directional controls.
- Self-contained HTML, CSS and JavaScript; no external dependencies.

## Run locally

Open `index.html` in a modern web browser. No installation or internet connection is needed.

## How it works

JavaScript tracks horizontal position (`x`), vertical position (`y`) and rotation (`rotation`). Each button updates the relevant value, then applies a CSS transform to the SVG car. Directional movements accumulate; entering a rotation angle sets the current angle rather than adding to the previous angle.

## Technologies

HTML · CSS Grid · SVG · JavaScript
