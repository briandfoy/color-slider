# color-slider

A single-page color tool. Pick a base color with hue, saturation, and
lightness sliders, or type a hex code, and see its four-color (square)
and three-color (triad) schemes on color wheels.

Try it at <https://briandfoy.github.io/color-slider/>.

## Features

* Hue, saturation, and lightness sliders whose tracks show the color at each position
* An editable hex field: entering a 6-digit hex code sets the sliders
* Quartet: a color wheel with four markers and a four-slice swatch (base, +90°, +180°, +270°)
* Triad: a color wheel with three markers and a three-slice swatch (base, +120°, +240°)
* A marker's distance from the wheel's center shows saturation

## Usage

Open `index.html` in a browser. There's no build step and no dependencies.

The sliders take whole numbers, so some hex codes shift slightly when
converted to HSL and back (for example, `#123456` becomes `#123354`).
