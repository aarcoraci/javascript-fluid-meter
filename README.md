# ❗❗❗❗❗ there is a newer version (totally rewritten) of this gauges. ❗❗❗❗❗

https://github.com/aarcoraci/fluid-meter

# javascript-fluid-meter

### examples

https://codepen.io/aarcoraci/pen/abzjaOW

![Image Example](https://raw.githubusercontent.com/aarcoraci/javascript-fluid-meter/master/fluid-meter.gif)

---

### about

I've been playing with **canvas** for some time now and from time to time I do small projects just to practice.

This library (aimed to be used on old browsers) renders a percentage meter as a bowl (?) with certain amount of fluid.

### install

download the js-fluid-meter.js and add it to your project or page

### usage

create as many instances as you want. Notice the target container **requires an id**

```javascript
var fm = new FluidMeter();
fm.init({
  targetContainer: document.getElementById("fluid-meter"),
  fillPercentage: 15,
  options: {
    fontFamily: "Raleway",
    drawPercentageSign: false,
    drawBubbles: true,
    size: 300,
    borderWidth: 19,
    backgroundColor: "#e2e2e2",
    foregroundColor: "#fafafa",
    foregroundFluidLayer: {
      fillStyle: "purple",
      angularSpeed: 100,
      maxAmplitude: 12,
      frequency: 30,
      horizontalSpeed: -150,
    },
    backgroundFluidLayer: {
      fillStyle: "pink",
      angularSpeed: 100,
      maxAmplitude: 9,
      frequency: 30,
      horizontalSpeed: 150,
    },
  },
});
```

---
