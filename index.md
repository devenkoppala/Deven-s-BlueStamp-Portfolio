# CNC Pen Plotter
My project is a CNC Pen Plotter which is a machine that can draw. It uses acrylic mounts that support linear rails and stepper motors. The motors move a pulley belt around which permits the machine to move around an XY plane similar to the movement of a 3d printer except in 2d. It has a servo motor at the end of one mount which acts as the pen up and down function which is the z-axis in this case. It has an Arduino uno with A4988 stepper drivers attached which is the main board connected to all the motors. The machine uses gcode to give instructions to the CNC machine and it takes that and draws.   
| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Deven K | Mountain View High School | Mechanical Engineering | Incoming Freshman |




  
# Final Milestone
<iframe width="560" height="315" src="https://www.youtube.com/embed/Q0wurrk0d7g" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For my final milestone, I completed a drawing of my own
To do this I would have to find an image that wouldn't be too difficult for the machine and it would have to be the right size
I found a cool Greek pattern and resized it so it would fit on the plane and then converted it into a code file. I experimented around with it and found that the machine made lines when it was trying to travel around the plane which ruined the drawing. To fix this, I had to go into notepad ++ and find all the places where this is the G0 commands which is where all the unwanted lines where I added M5 before and M3S500 after which puts the pen up and then down so there are no extra lines
After that, I was set to test, and this time it worked ver well created the image with minimal errors.

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
--->
# Second Milestone
<iframe width="560" height="315" src="https://www.youtube.com/embed/ejIaXOi90mk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>


For the 2nd Milestone, I worked on the software for this project, so it could complete a drawing
- First, I flashed the Arduino Uno with the firmware that was provided with the kit, so the machine would have basic instructions installed
- Next, I installed Universal G-Code Sender and changed a few settings to match the machine. This program allows me to send gcode to CNC machines and give mine the instructions to draw
- To complete my drawing I first need to create  a gcode for the machine that I can use to test it. To test, I wanted to start with something simple, so I  downloaded and copied a simple equilateral triangle and converted it to SVG, and then searched for an SVG --> to GCODE converter on GitHub. I found one quite easily and after that, I was ready to test. A few challenges were the pen wasn't always stable and the paper surface wasn't completely smooth either which caused there to be smudges and parts where the machine couldn't pass through
After tinkering around with it and adjusting it for better results I re-tested but this time with a harder gcode.





# First Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/wHJjRqvzGj0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

My project is the CNC Pen Plotter, it is basically a drawing machine. For my first milestone, I completed the assembly of the project
 It utilizes acrylic pedestals and mounts that hold up the motors, and bearings for the rails, and have slots to tighten the rails
- It also has stepper and servo motors to move a pulley belt around so the machine can move around an XY plane and draw
- A aluminum profile holds the cables for the connections of the stepper and servo motors 
-  Some challenges were that the nuts weren't all tight enough so the parts could move around causing there to be errors in the drawing
- To fix this I had to use a screwdriver to secure it very tightly so I wouldn't have to re-adjust it after
- I also had trouble with some of the screws, but I realized that it is because the acrylic parts weren't in the exact spots and weren't layered correctly, but those are easy fixes.
- Afterwards, I plan to test some of the g-codes that were given with the project and then create my own


# Starter Project

<iframe width="560" height="315" src="https://www.youtube.com/embed/Tg4g277qics?start=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>


Initially, I had tried to complete the digital clock but I had struggled with the little room for soldering and because of this, I had short-circuited an IC chip which killed the clock. I wasn't able to solder carefully enough for the jam packed board, so I chose the Robot badge with blinking LEDs since it had much more room for the solder.  I would need to have good soldering skills for my main project, so this project was really simple but it was an easy way to learn and develop my soldering skills. To assemble I soldered a battery holder and 2 LEDS onto the board and then attached a 3-volt battery, and a clip so it could attach to something.



<!---# Schematics 
Here's where you'll put images of your schematics. [Tinkercad](https://www.tinkercad.com/blog/official-guide-to-tinkercad-circuits) and [Fritzing](https://fritzing.org/learning/) are both great resources to create professional schematic diagrams, though BSE recommends Tinkercad because it can be done easily and for free in the browser. --->

<!---# Code
Here's where you'll put your code. The syntax below places it into a block of code. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize it to your project needs.

```c++
void setup() {
  // put your setup code here, to run once:
  Serial.begin(9600);
  Serial.println("Hello World!");
}

void loop() {
  // put your main code here, to run repeatedly:

}
``` 
--->
<!---# Bill of Materials
Here's where you'll list the parts in your project. To add more rows, just copy and paste the example rows below.
Don't forget to place the link of where to buy each component inside the quotation marks in the corresponding row after href =. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize this to your project needs. 

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
|:--:|:--:|:--:|:--:|
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
|:--:|:--:|:--:|:--:|
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |
|:--:|:--:|:--:|:--:|

--->
