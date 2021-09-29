----------

Instruction through Codio is built around the guides feature. This is a brief description on how the demo on the previous page was built. Please see the [**documentation**](https://docs.codio.com/authoring.html) for more information about content authoring with guides.

### Build on this Starter Pack
---
Please note that there are softwares, files, scripts, etc. preconfigured in this **Hello Turtle in Java** Starter Pack that allow for use of turtle in Java. 

* `turtle.sh` file is a Bash script that allows for efficient operations on multiple files in the command line. 
* `Turtle.java` is called to enable the Turtle Graphics library.

Follow the directions below to build out this project with your own activities in turtle:

### Code Editor File
---
Add a `.java` file to this project. This is the file students will edit. Right-click on the name of your project or book in the directory tree on the left. Select `New File...` and then type its name and file extension. Copy and paste the following template code into the new file.

```
public class filename {
  public static void main(String[] args) {
	
  }
}
```

### Page Layout
---
Each page in the guide can have its own layout. You can select how many panels you want, and what information goes in each panel. Click the wrench in the top-right corner of your guide. You can select the layout from here. 

When setting up Turtle Graphics, set the code editor file in panel 0, and the server in panel 1. The guide will be in panel 2. 

![Open Tabs](.guides/img/OpenTabs.png)

### Try It Button
---
|||
Use the following markdown syntax when creating the `Try It` button:

```markdown
{Try it|terminal}(bash .guides/turtle.sh javac filename.java java filename)
```
|||

Below is an image highlighting what happens after the `TRY IT` button is clicked.

![.guides/img/JavaTurtleOutput](.guides/img/JavaTurtleOutput.png)

1. `TRY IT` button is clicked by the user.
2. The `Terminal` tab is opened.
3. The terminal runs the command to compile the program and to display the graphical output.
4. The output is displayed as a canvas on the bottom left panel.
5. Click the tab to go back to the code editor.
6. Click the `x` to close the canvas and exit the program. Alternatively, you can also press the `Ctrl` and `z` keys (Windows) or the `control` and `z` keys (Mac).

### Add this Project to a Course
---
You can add this project as an assignment to an existing course:

1. In the course module, click **Add Assignment**.
2. On the Create Assignment page, click **Project based**.
3. To import a project, click the **Click here** link under **Starting Point.** 
4. Click **Copy Project** and browse to the project and select it.
5. Click **Create.**