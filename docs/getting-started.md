# Getting started with Arduino

An Arduino is essentially a tiny computer that can **control electricity**.

That means we can write code to turn things on and off, read signals from sensors, and control all sorts of electronic components. With an Arduino, you can control LEDs, buzzers, motors, displays, and much more.

Here are some components you might see frequently
![Components](assets/getting-started/Components.png)

Before we start working with the Arduino, let's learn how to actually work with these electronic components.

## Working With Electronic Components

### Solderless Breadboard

![Solderless Breadboard](assets/getting-started/Breadboard.png)
<center><em>(<a href="https://commons.wikimedia.org/w/index.php?curid=97240411">Image</a> By <a href="//commons.wikimedia.org/w/index.php?title=User:Guhuru&amp;action=edit&amp;redlink=1" class="new" title="User:Guhuru (page does not exist)">Guhuru</a> - <span class="int-own-work" lang="en">Own work</span>, Licensed Under <a href="http://creativecommons.org/publicdomain/zero/1.0/deed.en" title="Creative Commons Zero, Public Domain Dedication">CC0</a>).</em></center>

What you see in the image above is a solderless breadboard. It gives us an easy way to connect electronic components together without having to solder wires or components together.

You simply push the component leads and jumper wires into the holes, and the breadboard takes care of electrically connecting the components. This works because the breadboard has metal strips that connect the holes together (as you can see in the image).

The holes in the middle are connected in small rows like this:

```txt
  a b c d e     f g h i j

  ● ● ● ● ●     ● ● ● ● ●
  │ │ │ │ │     │ │ │ │ │
  └─┴─┴─┴─┘     └─┴─┴─┴─┘
```

This means any wire/component plugged into one of the holes **a, b, c, d, and e** in the same row is electrically connected to all of them. The same is true for **f, g, h, i, and j**.

 Notice, the gap down the middle of the breadboard. The five holes on the *abcde* side are **not** connected to the five holes on the *fghij* side.

There are also long rows of holes along the edges of the breadboard. These are usually used to distribute power around the circuit. Every hole along the line vertically is connected (refer to the image).

### Simple LED Circuit

We can connect components to make a simple *circuit*. Here's what it looks like.

![Simple Circuit](assets/getting-started/LEDCircuit.png)

This is a really simple circuit. The battery provides the energy to light up the LED and the resistor protects the LED from receiving too much current and blowing up.

## Installing the Arduino IDE

Now let's see what the Arduino can do. Instead of having the LED connected directly to a battery, we can have the Arduino control when the LED turns on and off. We get to decide exactly when this happens using code.


The first step is getting software to program our Arduino. We'll use the **Arduino IDE**. You can download it from the [official Arduino website](https://www.arduino.cc/en/software/).
