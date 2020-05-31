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
  


> Open this page at [https://mameeewin.github.io/pop-light-tutorial/](https://mameeewin.github.io/pop-light-tutorial/)

## Use as Extension

This repository can be added as an **extension** in MakeCode.

* open [https://makecode.microbit.org/](https://makecode.microbit.org/)
* click on **New Project**
* click on **Extensions** under the gearwheel menu
* search for **https://github.com/mameeewin/pop-light-tutorial** and import

## Edit this project ![Build status badge](https://github.com/mameeewin/pop-light-tutorial/workflows/MakeCode/badge.svg)

To edit this repository in MakeCode.

* open [https://makecode.microbit.org/](https://makecode.microbit.org/)
* click on **Import** then click on **Import URL**
* paste **https://github.com/mameeewin/pop-light-tutorial** and click import

## Blocks preview

This image shows the blocks code from the last commit in master.
This image may take a few minutes to refresh.

![A rendered view of the blocks](https://github.com/mameeewin/pop-light-tutorial/raw/master/.github/makecode/blocks.png)

#### Metadata (used for search, rendering)

* for PXT/microbit
<script src="https://makecode.com/gh-pages-embed.js"></script><script>makeCodeRender("{{ site.makecode.home_url }}", "{{ site.github.owner_name }}/{{ site.github.repository_name }}");</script>
