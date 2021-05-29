# HappySadFace
## Step 1

Drag the ``||Basic:on start||`` block to the trash on the left main menu.
 
## Step 2
In the menu on the left, under ``||Basic:Basic||``, find the ``||Basic:show leds||`` and drag the block inside the ``||Basic:Forever||`` block
```blocks
basic.forever(function(){
 basic.showLeds(`
        . . . . .
        . . . . .
        . . . . .
        . . . . .
        . . . . .
        `)
})
```
 
## Step 3
In the ``||Basic:show leds||`` block, click on the squares to make a happy face. (The squares will look white if on) 
```blocks
basic.forever(function(){
 basic.showLeds(`
        # # . # #
        # # . # #
        . . # . .
        # . . . #
        . # # # .
        `)
})
```
 
## Step 4
In the menu on the left, under ``||Basic:Basic||``, find another ``||Basic:show leds||`` block and drag the block inside the ``||Basic:Forever||`` block under the previous ``||Basic:show leds||``
```blocks
basic.forever(function(){
 basic.showLeds(`
        # # . # #
        # # . # #
        . . # . .
        # . . . #
        . # # # .
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
 
## Step 5
In the second ``||Basic:show leds||`` block, click on the squares to make a happy face. (The squares will look white if on)
```blocks
basic.forever(function(){
basic.showLeds(`
        # # . # #
        # # . # #
        . . # . .
        # . . . #
        . # # # .
        `)
 basic.showLeds(`
        # # . # #
        # # . # #
        . . # . .
        . # # # .
        # . . . #
        `)
})
```

## Step 6
Connect the Micro:bit to the USB port on your computer. Then click on ``||LED:Download||`` (Make sure that you download the file to the Micro:bit drive")
```blocks
basic.forever(function(){
Absolute_Acceleration = input.acceleration(Dimension.Strength)
led.plotBarGraph(Absolute_Acceleration,0)
serial.writeNumber(Absolute_Acceleration)
})
```
## Step 10
Congratulations, you did it!

<script src="https://makecode.com/gh-pages-embed.js"></script><script>makeCodeRender("{{ site.makecode.home_url }}", "{{ site.github.owner_name }}/{{ site.github.repository_name }}");</script>
