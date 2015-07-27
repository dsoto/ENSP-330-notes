# Physical Science Fundamentals

To understand energy, there are several topics from physics and
chemistry for us to understand.

- units of energy
- power and energy
- different types of energy
- conservation of energy
- laws of thermodynamics
- chemistry of photosynthesis
- chemistry of combustion



## Scale of energy quantities
<!-- ![](../figures/ipcc_energy_primer.png) -->
- from IPCC Energy Primer

## Energy Units
- Joule
    - SI Unit.  One Newton-Meter.
- Kilowatt-Hour
    - Energy consumed by 1 kW load over one hour
- Calorie
    - Energy to heat one gram of water one degree Celsius
- Kilo-calorie
    - One thousand calories.  Used in food energy content.
- British Thermal Unit (BTU)
    - Energy to heat one pound of water by one degree Fahrenheit
- Quad
    - One quadrillion ($10^{15}$) BTU

## Unit Conversions
- We may wish to compare energy units that are not consistent
- Often you can look up conversions in a table
- Other times you may need to recreate the conversion


## Units

Computation of physical quantities often relies on the human to define
and use a consistent set of units of measurement.  There are tools that
allow us to add physical quantities to our calculations, but they are
not as rich as I could like them to be.  One good practice is to
explicitly include the unit name in the variable name.

    power_watt = 100
    time_sec = 30
    energy_joule = power_watt * time_sec

