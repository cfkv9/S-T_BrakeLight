# S-T_BrakeLight

Welcome to your first project as an member of the Missouir S&T FSAE Team!

Formula SAE Brake Light Guide Lines
T7.4 Brake Light

T7.4.1 The car must be equipped with a red brake light. The brake light itself has to have a black background and a rectangular, triangular or near round shape with a minimum shining surface of at least 15cm². The brake light must be clearly visible from the rear in very bright sunlight. When LED lights are used without a diffuser, they may not be more than 20mm apart. If a single line of LEDs is used, the minimum length is 150mm.

T7.4.2 This light must be mounted between the wheel centerline and driver‟s shoulder level vertically and approximately on vehicle centerline laterally.

The rules are pretty simple. With the LED's we use, we'll have no problem getting them bright enough.

Constructing the Brake Light

The voltage source will be 12 V. We will be using 20 surface mount LED's and 4 surface mount Resistors. There will be 5 LED's in series with with a resistor. We will then have 4 of these LED's and resistor combinations in parallel with each other. You will need to pull up the data sheet for the LED to find out what its forward voltage is (i.e. the voltage needed for the LED to turn on and operate). You will use this value to calculate what resistance you will need for your brake light, but more on that later. With so many LED's, the board is going to get kind of hot. To help with this, we need to add via to help with the heat dissipation. I would say about 4-5 vias should be fine. Vias work by connecting the tip and bottom of the boards so you have more surface area. NOTE: Do not calculate a resistance value. We have had over current/heat issues and we need to first test our previous years design and then see if higher resistance is necessary.

We will be using these LEDs:
http://www.mouser.com/Search/ProductDetail.aspx?R=XPEBRD-L1-0000-00601virtualkey57280000virtualkey941-XPEBRDL10000601

These are the resistor style:
https://www.mouser.com/ProductDetail/279-35205R6JT?R=35205R6JTvirtualkey20420000virtualkey279-35205R6JT

Tutorial Videos on Eagle
https://www.youtube.com/playlist?list=PLB4C63828A483E756
