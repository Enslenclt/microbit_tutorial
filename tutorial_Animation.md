# My First Animation Tutorial



## Section 1
First begin by dragging  a ``||basic.show leds||`` block into the ``||basic.forever||`` loop

```blocks
basic.forever(function () {
    basic.showLeds(`
        . . . . .
        . . . . .
        . . . . .
        . . . . .
        . . . . .
        `)
})
```


## Section 2

Next, draw a stick figure in the ``||basic.show leds||`` block
```blocks
basic.forever(function () {
    basic.showLeds(`
        . . # . .
        # # # # #
        . . # . .
        . # # # .
        # . . . #
        `)
})
```


## Section 3
Then, drag a new ``||basic.show leds||`` block into the ``||basic.forever||`` loop and re-draw your stick figure and make a slight change so that it animates.

```blocks
basic.forever(function () {
    basic.showLeds(`
        . . # . .
        # # # # #
        . . # . .
        . # # # .
        # . . . #
        `)
    basic.showLeds(`
        # . # . #
        . # # # .
        . . # . .
        # # # # #
        . . . . .
        `)
})
```

## Section 4

Right click one of your ``||basic.show leds||`` stick figures and click duplicate and then drag it to the bottom of the ``||basic.forever||``.  Make a slight change again so it animates.

```blocks
basic.forever(function () {
    basic.showLeds(`
        . . # . .
        # # # # #
        . . # . .
        . # # # .
        # . . . #
        `)
    basic.showLeds(`
        # . # . #
        . # # # .
        . . # . .
        # # # # #
        . . . . .
        `)
    basic.showLeds(`
        . . # . #
        . # # # .
        # . # . .
        . # # # #
        # . . . .
        `)
})
```

## Section 5
Next grab two ``||basic.pause(ms)||`` blocks and click the arrow to change the number of seconds or milliseconds. The shorter the time the faster the animation will go.  Try experimenting!  

```blocks
basic.forever(function () {
    basic.showLeds(`
        . . # . .
        # # # # #
        . . # . .
        . # # # .
        # . . . #
        `)
    basic.pause(200)
    basic.showLeds(`
        # . # . #
        . # # # .
        . . # . .
        # # # # #
        . . . . .
        `)
    basic.pause(200)
    basic.showLeds(`
        . . # . #
        . # # # .
        # . # . .
        . # # # #
        # . . . .
        `)
})
```

## Section 6

Congratulations you just created an animation,  Now try making your own!