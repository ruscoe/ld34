# Ludum Dare 34

Source code for my entry in [Ludum Dare 34](http://ludumdare.com/), a themed
game jam.

This game combines both the winning themes - *Growing* and *Two button controls*.

## Requirements

* [Pixi.js](http://www.pixijs.com/)

## Set Up

The game expects the Pixi.js library to be in a directory named `lib`.

To set up using git:

```bash
mkdir lib
cd lib
git clone git@github.com:pixijs/pixi.js.git
```

Then open index.html in your web browser.

## How to Play

Use the left and right arrow keys to rotate the outer circles. Keep the inner
circle growing by matching the color of the top outer circle to the color of
the inner circle.

Score a point every time the inner circle reaches its maximum size.

The inner circle will shrink slowly over time and quickly when the wrong outer
circle color is selected.

Your score will be reset if the inner circle shrinks to its minimum size.

## License

Released under the The MIT License.

http://www.opensource.org/licenses/mit-license.php
