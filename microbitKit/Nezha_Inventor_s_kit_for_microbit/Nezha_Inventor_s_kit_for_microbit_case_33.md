Case 33: Color-controlled Lights

## Introduction
To make a color-controlled lights system.

![](./images/case_33_01.png)

## Quick Start
---

### Materials Required

---
Nezha expansion board × 1

micro:bit V2 × 1

Color sensor  × 1

Rainbow LED ring  × 1

Bricks × n

### Bricks Required

![](./images/case_33_02.png)


### Connection Diagram 
---
- Insert the micro:bit, connect the color sensor to IIC port and the rainbow led ring to J1 on the Nezha expansion board as the picture shows.


![](./images/case_33_03.png)



### Assembly

Build a device as the picture shows:

![](./images/case_33_04.png)

![](./images/case_33_05.png)



Link: [https://youtu.be/I05r5ebvQXY](https://youtu.be/I05r5ebvQXY)

<iframe width="560" height="315" src="https://www.youtube.com/embed/I05r5ebvQXY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## MakeCode Programming

---

### Step 1

Click "Advanced" in the MakeCode to see more choices.

![](./images/case_01_10.png)




For programming, we need to add a package: click "Extensions" at the bottom of the MakeCode drawer and search with "nezha" in the dialogue box to download it.

![](./images/case_03_09.png)

Notice: If you met a tip indicating that some codebases would be deleted due to incompatibility, you may continue as the tips say or create a new project in the menu. 

### Step 2

### Code as below:


![](./images/case_33_10.png)



### Reference
Link: [https://makecode.microbit.org/_CoKVCRc3wJJJ](https://makecode.microbit.org/_CoKVCRc3wJJJ)

You may also download it directly below:

<div style="position:relative;height:0;padding-bottom:70%;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://makecode.microbit.org/#pub:_CoKVCRc3wJJJ" frameborder="0" sandbox="allow-popups allow-forms allow-scripts allow-same-origin"></iframe></div>  
---

### Result
- After powering on, the the lights turn on with the color detected from the color sensor.
