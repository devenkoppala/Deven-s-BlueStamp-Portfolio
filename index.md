# CNC Pen Plotter
My project is a CNC Pen Plotter which is a machine that can draw. It uses linear rails and stepper motors so the robot can move around the plane. It can draw endless patterns and you can create your own drawings using g-code. 

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Deven K | Mountain View High School | Mechanical Engineering | Incoming Freshman |




  
<!---# Final Milestone
For your final milestone, explain the outcome of your project. Key details to include are:
- What you've accomplished since your previous milestone
- What your biggest challenges and triumphs were at BSE
- A summary of key topics you learned about
- What you hope to learn in the future after everything you've learned at BSE

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
--->
# Second Milestone
<iframe width="560" height="315" src="https://www.youtube.com/embed/ejIaXOi90mk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>


For the 2nd Milestone, I worked on the software for this project, so I could complete a drawing
- First, I flashed the Arduino Uno with the firmware that was provided with the Kit
- Next, I installed Universal G-Code Sender and changed a few settings to match the machine
- To complete my drawing I first need to create  a gcode for the machine that I can use to test it. I downloaded and copied a simple equilateral triangle and converted it to SVG and then searched for an SVG --> to GCODE converter on GitHub. After that, I was ready to try and print my first drawing
- Some challenges were the pen wasn't complete e stable and that it wouldn't be able t print too precisely 
After tinkering around with it and adjusting it for better results I re-tested but this time with a harder gcode.





# First Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/wHJjRqvzGj0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

My project is the CNC Pen Plotter, it is basically a drawing machine. For my first milestone, I completed the assembly of the project
- It utilizes Stepper and servo motors to move a pulley belt around so the machine can move around an XY plane and draw
- Has acrylic pedestals and mounts that hold up the motors and have slots to tighten the rails
- Some challenges with the nuts as some parts aren't tight enough as I want them and were able to move around
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
