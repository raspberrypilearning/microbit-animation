To create an animation, you can put **multiple** 'show leds' blocks together.

Here is an example.

```microbit
basic.showLeds(`
    . . . . .
    . . . . .
    . . # . .
    . . . . .
    . . . . .
    `)
basic.showLeds(`
    . . . . .
    . # # # .
    . # . # .
    . # # # .
    . . . . .
    `)
basic.showLeds(`
    # # # # #
    # . . . #
    # . . . #
    # . . . #
    # # # # #
    `)
```

You can find the `show leds`{:class='microbitbasic'} block in the `Basic`{:class='microbitbasic'} block menu in your Toolbox.

<img src="images/show-leds.png" alt="The Basic menu, with the 'show leds' block highlighted."  width="250"/>

Drag out three `show leds`{:class='microbitbasic'} blocks and put them together.

**Tip:** 💡 Add more blocks if you want a longer animation.

Click the squares on each one to create a pattern.

**Tip:** 💡 Hold down the mouse to select multiple LEDs as you move.

When the code runs, the LEDs will display each image in turn.

## Looping your animation

From the `Loops`{:class='microbitloops'} menu, drag a `repeat`{:class='microbitloops'} block and place it around the `show leds`{:class='microbitbasic'} blocks.

Change the number of repeats from `4` to the number of times you want the animation to repeat.

<img src="images/animation-ingredient.gif" alt="Animation showing the 'repeat' block taken from the Loops menu. The 'repeat' block is then held over the top 'show leds' block and released, making the three 'show leds' blocks snap inside it. The number is then changed from a '4' to a '2'." width="350"/>
