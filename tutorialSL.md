# START Title

## Section 1
First begin by dragging the ``||basic.show icon||`` into the ``||basic.start block||``

```blocks
basic.showIcon(IconNames.Heart)
basic.forever(function () {
	
})
```


## Section 2
Next, drag the ``||basic.show number||`` block into the ``||basic.forever|`` loop
```blocks
basic.showIcon(IconNames.Heart)
basic.forever(function () {
    basic.showNumber(0)
})
```


## Section 3
Last, drag the ``||input.temperature||`` bubble into the ``||basic.show number||`` block in the ``||basic.forever|`` loop
```blocks
basic.showIcon(IconNames.Heart)
basic.forever(function () {
    basic.showNumber(input.temperature())
})
```

## Section 4
Congratulations!  Now you can upload this program into your Micro:bit
