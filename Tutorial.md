# Pop Light Tutorial

## Step 1
Set plot X Y
```blocks
basic.forever(function () {
    led.plotBrightness(0, 0, 255)
})



```
## Step 2
PickRandom at X
```blocks
basic.forever(function () {
    led.plotBrightness(randint(0, 4), 0, 255)
})

```
## Step 3
PickRandom at Y
```blocks
basic.forever(function () {
    led.plotBrightness(randint(0, 4), randint(0, 4), 255)
})

```
## Step 4
PickRandom At Brightness 0 to 255
```block
basic.forever(function () {
    led.plotBrightness(randint(0, 4), randint(0, 4), randint(0, 255))

})
```
## Step 5
You Did The Pop op PO OPO pop Pop
Try in Your Microbit
