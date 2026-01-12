# Introduction

Qucs-S comes with the following tools:

* *Text editor*
    - A built-in plain text editor. It is very useful to inspect simulation files without leaving the Qucs-S environment.
    - Default shortcut: CTRL+1
* *Filter synthesis*
    - A tool for designing passive LC filters with various response types. Users specify the desired filter parameters such as cutoff frequency, passband ripple, and filter order, and the tool generates the corresponding component values and circuit topology, which is copied in the clipboard.
    - Default shortcut: CTRL+2
* *Active filter synthesis*
    - Generates active filter circuits using operational amplifiers and passive components. This tool supports multiple active filter topologies and provides automated synthesis of high-pass, low-pass, band-pass, and band-stop filters based on user-defined specifications.
    - Default shortcut: CTRL+3
* *Transmission line calculator*
    - Performs analysis and synthesis calculations for various transmission line types. It can determine the electrical parameters from physical dimensions or synthesize the physical dimensions from desired electrical characteristics.
    - It supports microstrip, coplanar waveguide, grounded coplanar, rectangular waveguide, coaxial line, coupled microstrip, and stripline synthesis.
    - Default shortcut: CTRL+4
* *Matching circuit*
    - Designs impedance matching networks for RF applications. This tool synthesizes the component values for different matching networks topologies based on the user specifications.
    - Default shortcut: CTRL+5
* *Atenuattor synthesis*
    - Creates resistive attenuator circuits with the specified attenuation for a number of different circuit topologies.
    - It also calculates the power dissipated on each resistor based on the input power and the attenuation factor.
    - Default shortcut: CTRL+6
* *Power combining*
    - A synthesis tool for designing power splitter and combiner networks. It can synthesize schematics for Wilkinson dividers, hybrid couplers, and other power distribution networks used in RF and microwave systems.
    - Default shortcut: CTRL+7
* *Data files converter*
    - Converts between different data file formats commonly used in circuit simulation.
    - Default shortcut: CTRL+8
* *RF Layout*
    - A tool for generating layouts and openEMS simulation scripts from Qucs-S a schematics.
    - [Developer repo](https://github.com/thomaslepoix/Qucs-RFlayout)
    - Default shortcut: CTRL+9
* [*S-Parameter Viewer & RF Synthesis Tool*](/Tools/SPViewer/SPViewer)
    - A comprehensive toolkit for RF and microwave circuit design. It combines S-parameter visualization capabilities with synthesis tools for filters, matching networks, attenuators, and power combiners. It provides Smith chart displays, parameter plotting, and automated network synthesis in a unified interface.
    - Default shortcut: CTRL+ALT+1
* *Receiver calculator*
    - Analyzes receiver system performance by calculating key metrics such as noise figure, gain, intercept points, and dynamic range through a cascade of RF components.
    - [Developer repo](https://github.com/arhiv6/rxcalc)
    - Default shortcut: CTRL+ALT+2

```{warning}
Filter synthesis, Matching circuit, Attenuator synthesis and power combining tools are legacy versions. Their capabilities are being transfered to the in S-Parameter Viewer & RF Synthesis Tool.
```