## Lightning lab basics

### App Overview

Three components to lightning lab:

- Robots: Connectable and programable devices
- Programs: instructions that tell the robots what to do
- Activities: fun ways to learn and code with sphero, chariot races, painting

#### Sections

- Home
  - real time hub for LL community
- My Programs
  - you programs
  - sphero dev programs
  - community programs
- Activities
  - Workbook
  - sphero
  - community
- Drive

## Intro Programming

### Square

- Regular polygon with all sides being the same, all angles at 90
- Double tap and menu item for more info
- Tap, hold, and drag `roll` from the actions category and drop it in your program
  - Duration 2s
  - Speed 50
  - Heading 0
- Repeat this three more times changing the heading by + 90 degrees each time.
- Run the program.
- What do you notice?
  - The corners are not sharp
- Add a 1 sec delay from the controls category in between each roll
- Now `Run`
- Look at the Oval code

### Square with a loop

- A loop repeats a series of blocks.
- Remove all but our first roll and our first delay
- Drag a loop block from the controls category.
- Drag the roll and the delay into the loop block.
  - Loops have a count option.  Tap it and select 4; once for each of our squares sides.
- Now we need to increment 90 degreees to our heading on each loop
- Go to the `operators category` and drag the add operator onto the heading option in our roll block
  - This created a different type of option with `0 + 0`.  Each of those are values that can be added and used to change the heading.
  - Go to the sensor category and find `Heading`.  This is the current heading of Sphero.  We can use this to change our heading on each loop.
  - Drag and Drop `Heading` from the sensor category to the operator option we just made for headings.
  - Each loop, we need to change our heading by 90 degrees so tap the other `0` and change it to 90.
  - Each time the loop happens, we will get the current heading and add 90 to it.

## Light and Color

Sphero has 3 LED lights on it.  There are the two main ones and the blue tail light.  There are 5 action blocks that directly control the light:

1. Set color
  - Set rgb values
  - set brightness
1. Delay
  - This can be used to hold a LED color for a certain amount of time
2. Fade
  - Can change from one color to another over a period of time
3. Strobe
  - Will turn the LED light on and off over a specific time period for a set number of times
4. Back LED
  - Allos us to turn on the tail light to a specific brightness


### Jackolantern


# Appendix

## Menu Categories

- Actions
  - things that make th robot do a specific thing, movement.
- Controls
  - These allow us to control blocks of code and do things like loops (repeat a block) 
- Operators
  - These are things that allow us to change values in our programs.  We can do things like addition, substraction, and a lot more.
- Sensors
  - This category allows us to use information about what our robot is doing.  We can get information, like heading, speed, and color 

## Variables


