# ham-radio-notes

The notes I took while taking my ham radio permit class.
Each exam question answer will be identified by it's question number (ex.: 5.10.11)

1. [Basics of electricity & resistance](#basics-of-electricity-and-resistance)
2. [Measuring electricity & current](#measuring-electricity-and-current)
3. [Capacitors, inductors and transformers](#capacitors-inductors-and-transformers)
4. [Rules and operation](#rules-and-operation)
5. [From vacuum tubes to semiconductors](#from-vacuum-tubes-to-semiconductors)
6. [Power supplies, amps and oscillators](#power-supplies-amps-and-oscillators)
7. [A world of telecommunications and emitters](#power-supplies-amps-and-oscillators)
8. [Receivers and digital transmissions](#receivers-and-digital-transmissions)
9. [Powerlines and antennas](#powerlines-and-antennas)
10. [Antennas part 2 and interference](#antennas-part-2-and-interference)
11. [Waves, an opening to the world  and measuring equipment](#waves-an-opening-to-the-world-and-measuring-equipment)

## Basics of electricity and resistance

### Intro

[IPR-4](https://publications.gc.ca/collections/collection_2016/isde-ised/Iu64-45-3-2014-fra.pdf)
is the Canadian reference for which bands are available for which license.

Ham radio logo is the following:

[![Ham radio logo](https://upload.wikimedia.org/wikipedia/commons/2/2c/International_amateur_radio_symbol.svg)](https://en.wikipedia.org/wiki/Amateur_radio)

Canadian Band plan:

[![Canadian band plan](https://www.rac.ca/mivahih/2023/06/IBC_July2023_Bandplan_0%E2%80%9330-796x1024.jpg)](https://www.rac.ca/rac-0-30-mhz-band-plan/)

Canadian Radio Frequency Allocation table:

[![Canadian Radio Frequency Allocation table](http://canadianspectrumpolicyresearch.org/wp-content/uploads/2016/08/2014_Canadian_Radio_Spectrum_Chart.jpg)](https://ised-isde.canada.ca/site/spectrum-management-telecommunications/en/learn-more/key-documents/consultations/canadian-table-frequency-allocations-sf10759)

### Electricity

- 5.2.1: Gold, silver and copper are good conductors.
- 5.2.2: Materials such as glass, porcelain, rubber, plastic and wood are good insulators.
- 5.2.4: The most used condutor is copper.
- 5.2.5: Material that conduct electricity well are called conductors.
- 5.2.6: Material that conduct electricity poorly are called insulators.
- 5.2.8: The opposite of resistance is conductance.
- 5.11.5: The instance of a magnetic field in a free space is directly proportional
to the intensity of the current flowing through the conductor.
- 5.11.7: In a conductor, the induced tension is perpendicular to the magnetic
field andto the direction of the current.
- 5.11.9: All magnets have a north and south pole. North and south poles
attract each other, while poles of the same type repel each other.
- 5.11.10: A permanent magnet is typically made of iron.

### Resistance

- 4.6.1: The fourth band represents the tolerance of the resistor.
- 4.6.2: The 3 first color bands on a resistor represent the value
of the resistor represented in ohms.
- 4.6.3: The first band represents the first digit of the value of the resistor.
The second band represents the second digit of the value of the resistor.
The third band represents the number of zeros to add to the value of the resistor.
The fourth band represents the tolerance of the resistor.
- 4.6.4: The actual resistance will typically be within 5%, 10% and
sometimes 20% of the value of the resistor.
- 4.6.5: The resistance of a resistor is represented by a color code.
- 4.6.6: Resistance of great quality will typically only vary by 0.1%.
- 4.6.7: When using an LED, the real resistance doesn't matter much.
20% is typically fine.
- 4.6.8: When a carbon resistor is heated, it's resistance increases.
The resistance changes based on it's heat coefficient.
- 4.6.9: Gold typically indicates a 5% tolerance.
Silver typically indicates a 10% tolerance. No band typically indicates a 20% tolerance.
- 4.6.10: The third band will, for example,
distinguish a 100ohm resistor from a 1000ohm resistor.
- 5.2.3: When a resistor gets hot, it means it's dissipating energy.
- 5.2.7: Resistance is measured in ohms. It's represented by the omega symbol.
- 5.2.10: The resistance of a conductor varies with it's heat.
- 5.2.11: The most used resistance is the carbon resistor.
- 5.5.3: When in parallel within a circuit, the total resistance is lower than
the lowest resistance of the resistors in parallel.
- 5.5.5: Resistors in series are added together.
- 5.5.6: For example, 5 10ohm resistors in series will have a total resistance
of 50ohms.
- 5.5.7: For example, 5 24ohm resistors in series will have a total resistance
of 120ohms.
- 5.5.8: When multiple resistors are in parallel and have the same value,
the total resistance formula is `Rt = R / n` where `R` is the resistance and
`n` is the number of resistors. When they are not of the same value, the
formula is `Rt = (r1 * r2)/(r1 + r2)`.
- 5.5.9: For example, a total of 4 68ohms resistors in parallel will have a
total resistance of 17ohms.
- 5.6.1: When we need to dissipate energy has heat, it's best to pick a
larger resistor even if a smaller one has the same ohmic value.
- 5.6.10: There's also an advantage to replacing a 50ohm resistor with two 100ohm
resistors in parallel. The power of the circuit will be higher
despite the same ohmic value.
- 5.6.11: The power rating of a resistors is based on it's ability to dissipate
heat.

### Next class

Read chapter 3 and 4 of the electricity book.

## Measuring electricity and current

### Measuring electricity

Here is the unit conversion chart:

[![Unit conversion](http://sciencepedagogics.pbworks.com/f/1311886367/PREFIXES.PNG)](http://sciencepedagogics.pbworks.com/w/page/43781129/Metric%20Unit%20Prefixes)

Here are the formulas for calculating power, tension and current:

[![Ohms Law Chart](https://www.electrical101.com/wpimages/ohms-law-peir-symbol.webp)](https://www.electrical101.com/ohms-law.html)

More specifically, here are the formulas where **P** is power, **E** is tension,
**R** is resistance and **I** is current:

1. I^2 * R = P
2. E * I = P
3. E^2 / R = P
4. sqrt(P/R) = I
5. P / E = I
6. E / R = I
7. squart(P * R) = E
8. I * R = E
9. P / I = E
10. E^2/P = R
11. P / I^2 = R
12. E / I = R

- 5.1.1: A dial indicating 3,535MHz is equal to 3535 kHz.
- 5.1.2: If we measure a current of 3000 mA, it's equal to 3A.
- 5.1.3: If we measure a tension of 3500 mV, it's equal to 3.5V.
- 5.1.4: A condensator of 1000000 pF is equal to 1 uF.
- 5.1.5: A 500mW transmitter is equal to 0.5W.
- 5.1.6: a kOhm is equal to 1000 ohms.
- 5.1.7: A tension of 6,6 kVolts is equal to 6600 V.
- 5.1.8: A current of a quarter Amp can be written as 250 mA.
- 5.1.9: A tension of 2 volts is equal to 2000 mV.
- 5.1.10: a MHz is equal to 1000000 Hz.
- 5.1.11: An inductance of 10000 uH can be written as 10 mH.
- 5.2.9: Tension drop is the difference between the tension at the beginning
and the end of the circuit
- 5.3.1: Power is the word used to express the speed at which energy is
used
- 5.3.2: Out of a 40W, 80W and 100W lightbulb, the 100W lightbulb will be the
- 5.3.3: Watts are used to express the power of a circuit
- 5.3.4: When a circuit is opened,
one that consumes the most
- 5.3.5: When a circuit requires too much current,
it'll short circuit
- 5.3.6: Watts are used to express the power of a circuit
- 5.3.7: To know the power, we multiply the tension by the current
- 5.3.8: To know the power, we multiply the tension by the current
- 5.3.9: In a circuit, when a resistance becomes too hot it means the current
has too much power
- 5.3.10: High resistance tend to have a large body and a large wire. These
characteristics allow them to dissipate heat faster.
- 5.3.11: Of a 5W, 2.5W, a 10W and a 20W, the resistance that can dissipate
the most heat is the 20W one
- 5.4.1: A current of 2 amps goes through a 50 ohms resistance, which voltage appears
appears at the leads?
- 5.4.2: The current is equal to voltage divided by resistance
- 5.4.3: Resistance is equal to voltage divided by current
- 5.4.4: Voltage is equal to current multiplied by resistance.
- 5.4.5: If a 12V battery has a current of 0.25A in it's circuit, what is the
resistance of the circuit?
- 5.4.6: Calculate the resistance required to obtain a drop of 100V with
the current is 0.8mA
- 5.4.7: Which tension is required to force a current of 4.4A through a resistance
of 50 ohms?
- 5.4.8: A lamp has a resistance of 30 ohms with a current of 6V, how many amps
is circulating in the lamp?
- 5.4.9: Which tension is necessary to force a current of 200 mA though a lamp
that has a resistance of 25 ohms?
- 5.4.10: Voltage is equal to current multiplied by resistance.
- 5.4.11: If a battery has 3V and is pushing a 300mA current, what is the resistance
in the circuit?
- 5.5.1: The current given by a circuit is equal to the sum of the current
circulating in all branches of the circuit.
- 5.5.2: The sum of the current circulating in each resistor is equal to the
total current drained in the battery.
- 5.5.4: If two resistors have a value of 1000 ohms, the total current is
80mA.
- 5.5.10: If two resistance are placed in parallel and the resistance
of resistor A has a current twice as high as resistor B, this means
resistor A is twice as low as resistor B.
- 5.6.2: How many Watts will be used by a lamp of 12 volts and 0.2A?
- 5.6.3: What is the power of a transmitter that consumes 500mA under 12V?
- 5.6.4: The max power of 2 resistors of 500ohms and 1 watt can dissipate
2 watts
- 5.6.5: The max power of 2 resistors of 500ohms and 1 watt can dissipate
2 watts
- 5.6.6: If we double the tension applied between two resistors, the current
will quadruple
- 5.6.7: The total power is equal to the sum of the power of each resistor
no matter the configuration
- 5.6.8: A 12V lamp has a power of 30W. The current consumed is 30/12.
- 5.6.9: What is the total power of 2 10ohms resistors connect in series
to a 10V battery?
- 5.8.1: We can say that by doubling the power, we gain 3dB
- 5.8.2: We can decrease the power of a transmitter by 3dB by dividing
it's power by 2
- 5.8.3: We can increase a transmitters power by 6dB by multiplying
it's power by 4
- 5.8.5: an emitter of 500W has a signal strength of S9 + 20db.
If the power is lowered by 150W, it's strength will be S9 + 10dB.
- 5.8.6: Decibels (dB) is a unit to express the ratio between two values.
- 5.8.7: If a transmitter goes from 1W to 2W, it's a gain of 3dB
- 5.8.8: The power of an emitter that rises from 5W to 50W thanks to
a linear amp. The gain is 10dB.
- 5.8.9: To increase the power of your 2W emitter, you add a 9dB amp. The
new power is 16W as 9dB is equal to 8W.
- 5.8.11: A HAM radio brings 100W signal gives it a signal strength
of S9 + 30dB. To reduce your signal to S9, you need to reduce
your power by 100mW. A 30dB reduction is equal to 1000.

### Current

#### DC Current

- 3.16.1: Wet cell accumulators each have 2 volts cells. That's why
a car battery has 6 cells to get roughly 12 volts.
- 3.16.2: The current given by battery has a north and south pole
- 3.16.3: Batteries that can be recharged are called accumulators
or secondary battery
- 3.16.4: Lithium-Ion batteries are a source of electro-motive force
- 3.16.7: A primary battery is a battery that can't be recharged. It's
typicaly carbon-zinc batteries
- 3.16.5: A big difference between a carbon-zin battery and a lithium-ion
one is that only the lithium-ion battery can be recharged
- 3.16.6: A tension drop is provoked by the resistance of a circuit
- 3.16.8: If we exceed the capacity of a battery, it's charge wont last
as long
- 3.16.9: To rise the current of a circuit, batteries can be placed in parallel
- 3.16.10: To rise the tension, you can add batteries in series
- 3.16.11: A nickel-cadmium battery should never be shorted

#### AC Current

- 3.17.8: The current given by Hydro-Quebec is generally 120V and 240V
- 5.7.1: The frequency of a current is the number of times the current
alternates from positive to negative in a second
- 5.7.2: The frequency at which humans can hear is between 20Hz and 20kHz
- 5.7.3: The frequency at which humans can hear is between 20Hz and 20kHz
- 5.7.4: In a frequency of 7,125MHz the electricity tends to scillate
at 7,125 million times per second
- 5.7.8: The current generated by Hydro-Quebec is 60Hz
- 5.7.9: For example, a frequency of 100Hz means a cycle is 0.01 second
- 5.7.10: A current that has a total cycle of 0.1s is 10Hz

## Capacitors, inductors and transformers

TODO

## Rules and operation

TODO

## From vacuum tubes to semiconductors

TODO

## Power supplies, amps and oscillators

TODO

## A world of telecommunications and emitters

TODO

## Receivers and digital transmissions

TODO

## Powerlines and antennas

TODO

## Antennas part 2 and interference

TODO

## Waves, an opening to the world and measuring equipment

TODO
