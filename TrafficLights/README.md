# Traffic Lights

I had to do this project. I have a six-year-old. He loves to get out of bed
after 7am on Weekdays (so he misses the bus) and before 6:30 on the weekends (so
he can watch some shows). But our family rule is stay in bed until at least 7am.

Six-year-olds are just learning to tell time, and it still doesn't make sense.
But a traffic light sure does. Red means stop, Green means go. Red means stay in
bed, Green means you can get out of bed.

I've been jonesing to make some kind of light system so he can push a button and
know when to stay in bed, instead of pushing my buttons. :) Well, this year his
grandpa offered to by a Raspberry Pi 3 for any of his grandkids that could come
up with a project to use it. Perfect! Four of my six kids thought up an idea,
and the six-year-old loved the idea of a bed-time traffic light! With my full
involvement, this, unfortunately, was the only project that was completed before
the March 14 (pi day) deadline set by his grandpa for an extra surprise.

This system is simple. Three LEDs (red, amber, green), plug directly into the
Raspberry Pi (or with a breadboard), and a simple python script to run at boot
up, and... we'll see if this helps on the weekends.

# Set up

Here are the parts the plan and the programming to get this project set up.

## Parts List

  - Raspberry Pi (any version will do, this uses version 3).
    - https://www.adafruit.com/products/3055
    - or this to get most of the components below, too: https://www.adafruit.com/products/3334
  - wires
    - Using a breadboard?
      - You'll want male/female wires, female side plugs into Raspberry Pi, the
        male side into the breadboard.
        - https://www.adafruit.com/products/826
    - Wiring directly?
      - You'll want female/female
        - https://www.adafruit.com/products/1951
  - red LED
    - https://www.adafruit.com/products/299
  - amber LED
    - https://www.adafruit.com/products/3260
  - green LED
    - https://www.adafruit.com/products/299
  - power cable
    - https://www.adafruit.com/product/1995
  - button 
    - Anything will do. https://www.adafruit.com/products/476

