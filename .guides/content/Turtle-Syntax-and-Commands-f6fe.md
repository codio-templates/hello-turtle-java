----------
Turtle Graphics allows students to create graphical output with the Turtle Graphics library. Like a pencil on paper, the Turtle object leaves a line as it moves around the screen.

![Turtle](.guides/img/Turtle.png)

### Turtle Syntax
---
The first step is to create a Turtle object to move around the screen.

```java

	Turtle tina = new Turtle(); //creates a Turtle object called tina

```

Here are some basic commands to use with `tina` the Turtle object.

|Command|Parameter|Description|
|:-----:|:-------:|:---------:|
|`tina.forward(n)`|Where `n` represents the number of pixels|Move the turtle forward|
|`tina.backward(n)`|Where `n` represents the number of pixels|Move the turtle backward|
|`tina.right(d)`|Where `d` represents the number of degrees|Turn the turtle to the right|
|`tina.left(d)`|Where `d` represents the number of degrees|Turn the turtle to the left|

### Turtle Commands
---
Next, let's try this very simple command below. **Copy and paste** the following code in the editor on the left. Java style guidelines call for indentation within a block (an open/close brace pair.) Click the `TRY IT` button to see the graphical output.


```java
	Turtle tina = new Turtle(0, 100); //starting position of the turtle
	tina.forward(100); //moves tina forward 100 pixels
```

{Try it|terminal}(bash .guides/turtle.sh javac TurtleGraphics.java java TurtleGraphics)

<details><summary> <b>What does the <code>(0,100)</code> inside <code>Turtle()</code> do?</b></summary> This enables you to set the latitude and longitude of <code>tina</code>. In the example, <code>tina</code> starts at 0 pixel latitude and 100 pixels longitude.</details><br>

Copy and paste the code below into the editor on the left and click cthe `TRY IT` button to see the graphical output. What do you think this will create?

```
	Turtle tina = new Turtle(0, 100); 
	for (int i = 0; i < 4; i++) {
		tina.forward(100);
		tina.right(90);
	}
```

{Try it|terminal}(bash .guides/turtle.sh javac TurtleGraphics.java java TurtleGraphics)

### Customize Your Turtle
---
The following table provides additional commands you can use to customize `tina` the Turtle.

|Command|Parameter|Examples|
|:-----:|:-------:|:---------:|
|`tina.penColor("COLOR")`|Where `COLOR` represents the track or line color you want tina to leave behind|red, orange, yellow, green, blue, purple|
|`tina.shape("SHAPE")`|Where `SHAPE` represents the shape tina takes|turtle, circle, square, arrow, triangle|
|`tina.speed(s)`|Where `s` represents how many milliseconds it takes tina to perform an action|1 (fastest) through positive infinity (the larger the number, the slower tina moves)|
