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
- 5.7.4: In a frequency of 7,125MHz the electricity tends to oscillate
at 7,125 million times per second
- 5.7.8: The current generated by Hydro-Quebec is 60Hz
- 5.7.9: For example, a frequency of 100Hz means a cycle is 0.01 second
- 5.7.10: A current that has a total cycle of 0.1s is 10Hz

## Capacitors, inductors and transformers

Resonance frequency formula: `f = 1 / (2 * pi * sqrt(L * C))`

Impedance forumla: `Z = sqrt(R^2 + (Xl - Xc)^2)`

### Capacitors/condensators

Series and parallel formulas:

- In series: Ct = (C1 * C2) / (C1 + C2)
- In parallel: Ct = C1 + C2

Capacitive reactance formula: `Xc = 1 / (2 * pi * f * C)`
Inductive reactance formula: `Xl = 2 * pi * f * L`

- 5.9.3: Two condensators in series have a total capacity that is half
the lowest capacity of the condensators.
- 5.9.4: When two condensators are in parallel, the total capacity is
twice the value of one of the condensators.
- 5.9.6: For variable blade metallic capacitors, the capacity a forth factor
comes into account: the number of blades.
- 5.9.9: Three 15 microfarads condensators in parallel have a total capacity
of 5 microfarads.
- 5.9.10: Two 20 microfarads condensators in parallel could help replace a broken
10 microfarads condensator.
- 5.9.11: It's important to note that the total capacity of two or more
condensator in series is always lower than the smallest capacity of the condensator
- 5.10.2: When the frequency of an AC signal lowers, the reactance of the condensator
becomes lower.
- 5.10.3: When the frequency of an AC signal lowers, the reactance of the condensator
becomes higher.
- 5.10.5: When the frequency of an AC signal lowers, the reactance of the condensator
becomes lower.
- 5.10.8: A low reactance to radio frequencies allows a bypass condensator
to reduce noise.
- 5.10.9: A high reactance to low radio frequencies to have a a negligeable
effet on audio

### Inductors

- 5.9.1: If two windings of equal value are in series, the total inductance
is doubled
- 5.9.2: The formula of two parallel windings is `Lt = (L1 * L2) / (L1 + L2)`.
By using this formula, we can calculate the total inductance of two windings
in parallel is half the value of the lowest inductance.
- 5.9.5: The inductance of a winding is determined by: the composition of the core,
the diameters of the winding, the length of the winding and the number of turns
- 5.9.8: A defective winding of 10 microhenries can be replaced by two 5
microhenries windings in series.
- 5.10.1: We can rise the inductive reactance by rising the frequency.
- 5.10.4: The term impedance represents all of the resistance and reactance
of a circuit
- 5.10.6: We can rise the inductive reactance by rising the frequency.
- 5.10.7: A high reactance to frequencies allow a winding to reduce RF noise
- 5.10.10: A low reactance to low frequencies allow a "bobine d'arret RF" to
have a negligeable effect on signals that needs to traverse it.
- 5.10.11: We can rise the inductive reactance by rising the frequency.
- 5.11.6: The induced tension in a winding is maximal when the current variation
is maximal.
- 5.12.1: Resonance is a condition that exists when the inductive reactance and
the capacitive reactance are equal but oppposite.
- 5.12.2: In a circuit in series, the amplification of the current happens
at the resonance frequency. A resonating circuit in parallel will have a
maximal impedance and a minimal current at the resonance frequency.
- 5.12.3: The resonance is an electrical property that is used to describe
the characteristics of a circuit with a winding and a condensator.
- 5.12.4: A tuned circuit is made with a winding and a condensator.
- 5.12.5: When applying an AC tension at a variable frequency to a parallel
winding setup with condensators, the impedance is maximized at the given
frequency.
- 5.12.6: In a circuit in series, the amplification of the current happens
at the resonance frequency. A resonating circuit in parallel will have a
maximal impedance and a minimal current at the resonance frequency.
- 5.12.7: When an inductance L, a capacitor C and a resistance R are in series,
it's called a series resonating circuit. In such a circuit, the impedance
is weak but the current traversing the circuit is high  as only one current
is circulating in the circuit.
- 5.12.8: When an air condensor is used to create a resonating circuit, the
resonance frequency remains unchanged if we add a resistance to the circuit.
- 5.12.9: A resonating circuit is used in a receptor to select a specific frequency
- 5.12.10: Resonance is a condition that exists when the inductive reactance and
the capacitive reactance are equal but oppposite.
- 5.12.11: In an LCR circuit that is tuned at the source's frequency, the current
is maximal.

### Transformers (not the robot kind)

Formula for windings and tension: `V (primary) / V (secondary)
= (# windings primary) / (# windings secondary)`

Formula for the transformation ratio: `Np / Ns = Ep / Es = Is / Ip`

- 5.11.1: When there is no charge in the secondary windings, the current
of the primary winding is a magnetizing current.
- 5.11.2: The secondary winding of a transformer is using 2A at 6.3V. What is
the approximate power of it's primary? 12.6W
- 5.11.3: A primary winding if using 250mA at 240V. If the transformer
doesn't lose enegery, what is the secondary winding's current if it's
supplied 12V? 5 Amps
- 5.11.4: A transformer having a primary winding of 250 turns and a secondary
winding of 500 turns will have a voltage ratio of 1:2. If we give it 120V,
the secondary winding will have 240V.
- 5.11.8: A transformer with a 100% efficiency will have a transformation
ratio of 1/5. This means that if we see a 50mA current on the secondary winding,
the primary winding will have a 250mA current being applied.
- 5.11.11: When the energy transfer between the primary and secondary windings
some energy is lost as heat in the metal plates.

## Rules and operation

Membership levels go as follows: Individual member -> Club -> RAQI -> RAC -> ITU

Here are the high levels bands:

- HF: 1.8 to 30MHz
- VHF: 50 to 54Mhz and 144 to 148MHz
- UHF: 430 to 450MHz

Here are the most common modes:

- CW: Continuous wave
- SSB: Single side band
- AM: Amplitude modulation
- FM: Frequency modulation
- Digital: PSK31, RTTY, SSTV, JT8, JT65, FT8, FT4, etc.

Basic license gives you access to:

- Radio bands above 30MHz
- 250W of power on emmission
- You can install and use your own reception equipment (except repeaters)

Basic license with distinction gives you access to:

- All ham bands

Superior license:

- Can emmit up to 1000W
- Can build emitters & repeaters
- Can command remote fixed stations

| Prefixes | Province              |
| ---      | ---                   |
| VE1 VA1  | Nova Scotia           |
| VE2 VA2  | Quebec                |
| VE3 VA3  | Ontario               |
| VE4 VA4  | Manitoba              |
| VE5 VA5  | Saskatchewan          |
| VE6 VA6  | Alberta               |
| VE7 VA7  | British Columbia      |
| VE8      | Northwest Territories |
| VE9      | New Brunswick         |
| VE0      | International waters  |
| VO1      | Newfoundland          |
| VO2      | Labrador              |
| VY1      | Yukon                 |
| VY2      | Prince Edward Island  |
| VY0      | Nunavut               |

Number of questions in the exam:

- 25 questions about rules and politics
- 9 questions about exploitation and procedures
- 21 questions about the station assembly
- 6 questions about the components
- 13 questions about the elements and theory of electronic
- 8 questions about wave propagation
- 6 questions about interference and scrambling

Here are the bands:

| Wave length meters | Band MHz | Frequency MHz | Width of band kHz |
| ---  | ---    | ---    | ---   |
| 160  | 1.8    | 2.0    | 6     |
| 80   | 3.5    | 4.0    | 6     |
| 40   | 7.0    | 7.3    | 6     |
| 30   | 10.1   | 10.15  | 1     |
| 20   | 14.0   | 14.35  | 6     |
| 17   | 18.068 | 18.168 | 6     |
| 15   | 21.0   | 21.45  | 6     |
| 12   | 24.89  | 24.99  | 6     |
| 10   | 28.0   | 29.7   | 20    |
| 6    | 50.0   | 54.0   | 30    |
| 2    | 144.0  | 148.0  | 30    |
| 1.25 | 220.0  | 225.0  | 100   |
| 70cm | 430    | 450    | 12MHz |
| 33cm | 902    | 928    | 12MHz |

Frequencies below 30MHz tend to be LSB, above 30MHz tends to be USB.
30MHz is a non-phone band.

Phonetic alphabet:

| Letter | Phonetic Alphabet |
|--------|-------------------|
| A      | Alpha             |
| B      | Bravo             |
| C      | Charlie           |
| D      | Delta             |
| E      | Echo              |
| F      | Foxtrot           |
| G      | Golf              |
| H      | Hotel             |
| I      | India             |
| J      | Juliet            |
| K      | Kilo              |
| L      | Lima              |
| M      | Mike              |
| N      | November          |
| O      | Oscar             |
| P      | Papa              |
| Q      | Quebec            |
| R      | Romeo             |
| S      | Sierra            |
| T      | Tango             |
| U      | Uniform           |
| V      | Victor            |
| W      | Whiskey           |
| X      | X-ray             |
| Y      | Yankee            |
| Z      | Zulu              |

Q Codes:

| Q-Code | Meaning                                      |
|--------|----------------------------------------------|
| QRA    | What is the name of your station?            |
| QRZ    | Who is calling me?                           |
| QRG    | Will you tell me my exact frequency?         |
| QRL    | Are you busy?                                |
| QRM    | Is my transmission being interfered with?    |
| QRN    | Are you troubled by static?                  |
| QRO    | Shall I increase power?                      |
| QRP    | Shall I decrease power?                      |
| QRQ    | Shall I send faster?                         |
| QRS    | Shall I send more slowly?                    |
| QRT    | Shall I stop sending?                        |
| QRV    | Are you ready?                               |
| QRX    | When will you call me again?                 |
| QRZ    | You are being called by callsign.            |
| QSB    | Is my signal fading?                         |
| QSL    | Can you acknowledge receipt?                 |
| QSO    | Can you communicate with callsign direct?    |
| QSY    | Shall I change frequency?                    |
| QTH    | What is your location?                       |
| QSY    | I am changing frequency to frequency.        |

## From vacuum tubes to semiconductors

- 4.2.1: The Zener diode is used to regulate tension.
- 4.2.2: Diode can be used to rectify signals. They can also be used to
demodulate radio frequency signals.
- 4.2.3: The basis of regulation is the following: When the Zener diode is
in use, you can either lower or raise the tension and yet the tension will
remain the same at it's output.
- 4.2.4: Rectifying is the process of converting an AC signal into a DC signals
- 4.2.5: The electrodes of a diode are called anodes and cathodes.
- 4.2.6: If we apply an AC signal to a diode we get a pulsating DC signal.
- 4.2.7: In a diode,  electrons move from the cathode to the anode.
- 4.2.8: There's a few types of diodes with different characteristics:
capacitive diodes (varicap), light emitting diodes (LED), Zener diodes,
Schottky diodes, tunnel diodes, triacs, thyristors, etc.
- 4.2.9: The Zener diode is used to regulate tension.
- 4.2.10: For a diode to conduct electricity, the anode must be at a direct polarity
- 4.5.1: In certain circuits, such as linear amplifiers, vacuum tubes are
prefered as they support a higher power.
- 4.5.2: Vacuum tubes can amplify a signal thats weak but requires
a lot of voltage.
- 4.5.3: A vacuum triode and a transistor have something in ommon: they
can be amplify a signal
- 4.5.4: Anodes only work when it has the highest positive potential because
the electrons are attracted to it. This is however only if the anode is
attached to the positive pole of the battery.
- 4.5.6: The anode the furthest away from the filament is they one that
is used to heat the cathode.
- 4.5.7: Cathodes emit electrons (typically in tungsten)
- 4.5.8: A vacuum tube works when electrons are emitted from the cathode as long
as they're heated and the anode is positively charged.
- 4.5.9: Triodes contain 3 components and a filament. The cathode, the mesh and the
anode (plate).

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
