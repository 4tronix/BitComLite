# Bit Commander Lite
Makecode extension for 4tronix Bit Commander Lite

This very simple controller for the Microbit comprises 8 buttons. This extension simplifies reacting to and testing the state of these buttons


```blocks
// Check the state of selected button P1
let myState = bclite.checkButton(bclPins.p1);

// Start running code when P15 is Pressed
bclite.onButtonEvent(bclPins.p15, bclEvents.Pressed, function () { <your code> }

// Start running code when P12 is Released
bclite.onButtonEvent(bclPins.p12, bclEvents.Released, function () { <your code> }

```



## Supported targets

* for PXT/microbit

## License

MIT
