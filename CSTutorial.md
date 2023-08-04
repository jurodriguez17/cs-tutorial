# CSTutorial (create an animation of your age 30)
## Step 1 
First drag the ``||input:onButtonPressed||``  in the work space.
```blocks
input.onButtonPressed(Button.A, function () {}
```

## Step 2 
 Next drag two ``||basic:show leds||``   blocks in ``||input:onButtonPressed||`` . On the first leds create the number 3 like in the example. 
 On the second ``||basic:show leds||`` You will create a 0 in the block. 
 As shown in the example.  
```blocks
input.onButtonPressed(Button.A, function () {
    basic.showLeds(`
        # # # # #
        . . . . #
        . . . # #
        . . . . #
        # # # # #
        `)
    basic.showLeds(`
        # # # # #
        # . . . #
        # . . . #
        # . . . #
        # # # # #
        `)
```

## Step 3 
Next drag one ``||basic:show leds||``   blocks in ``||input:onButtonPressed||`` .
Right after the previous two blocks.
 You will leave ``||basic:show leds||``   block empty . 
  As shown in the example.
```blocks
input.onButtonPressed(Button.A, function () {
    basic.showLeds(`
        # # # # #
        . . . . #
        . . . # #
        . . . . #
        # # # # #
        `)
    basic.showLeds(`
        # # # # #
        # . . . #
        # . . . #
        # . . . #
        # # # # #
        `)
    basic.showLeds(`
        . . . . .
        . . . . .
        . . . . .
        . . . . .
        . . . . .
        `)
```

## Step 4 
Next drag three(3) ``||basic:show leds||``   blocks in ``||input:onButtonPressed||`` .
At the end of the previous work.You will repear step 2 and 3. You will create
a 3 in the frist ``||basic:show leds||`` . The second ``||basic:show leds||``  you will create 0.
The last ``||basic:show leds||``  you will leave it blank.
  As shown in the example.

```blocks
input.onButtonPressed(Button.A, function () {
    basic.showLeds(`
        # # # # #
        . . . . #
        . . . # #
        . . . . #
        # # # # #
        `)
    basic.showLeds(`
        # # # # #
        # . . . #
        # . . . #
        # . . . #
        # # # # #
        `)
    basic.showLeds(`
        . . . . .
        . . . . .
        . . . . .
        . . . . .
        . . . . .
        `)
    basic.showLeds(`
        # # # # #
        . . . . #
        . . . # #
        . . . . #
        # # # # #
        `)
    basic.showLeds(`
        # # # # #
        # . . . #
        # . . . #
        # . . . #
        # # # # #
        `)
    basic.showLeds(`
        . . . . .
        . . . . .
        . . . . .
        . . . . .
        . . . . .
        `)
})

```
## Step 4 
Congratulations, now you can upload this program on your micro:bit.
