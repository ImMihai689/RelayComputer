T flip-flops require two relays. In order to increment they need two pins to be shorted and os output they short two pins, which means they can be easily daisy chained.
![TFlipFlop](https://github.com/ImMihai689/RelayComputer/assets/75139772/219738af-c368-45d9-af86-b219ab8096e2)

Since we also need to separate the output into another branch to go to the rest of the computer, we will use another relay to repeat the shorted pin (the top pole of RY3) and to create a signal (the bottom pole of RY3) that also has to be reversed because of how  flip-flop counters work. Shorting RY2's negative coil terminal to GND will activate the flip-flop, from any state it's in, so we can add a relay for that so we can write to it. Keep in mind that activating the flip-flop witll make it output a 0.
![betterTFlipFlop](https://github.com/ImMihai689/RelayComputer/assets/75139772/c13c043c-a7ce-44d2-9849-4c8103ad7e7f)

OR JUST USE A REGISTER AND ADD 1 OR WHATEVER VALUE
