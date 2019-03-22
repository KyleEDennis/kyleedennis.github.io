# MrFusionREADME
A quickstart guide to the home energy reactor by General Plasma

<!-- Add text center class div -->
![Mr. Fusion](/images/mrfusion.jpg)

Welcome to the exciting world of consumer-level applied high-energy physics, brought to you by General Plasma. This guide will show you how to install, initialize, and perform basic maintenance on your Mr. Fusion™ in minimum time.

For long-term usage, we **highly recommend** that you enroll in our supplementary courses, which are available both in-person and by virtualized telepresence:

<!-- Add class for table-active -->
Course | Description
------ | -----------
[Home Safety](https://generalplasma.com/mrfusion/courses/001) | Identify the areas and materials of your home most vulnerable to neutron flux.
[Reactor Maintenance](https://generalplasma.com/mrfusion/courses/002) | Monitoring plasma composition and containment vessel wear.
[Emergency Shutdown Procedures](https://generalplasma.com/mrfusion/courses/003) | Performing SCRAM procedures to prevent catastrophic toroid failure in the event of overload.
[Radiation Exposure Syndrome](https://generalplasma.com/mrfusion/courses/013) | Spotting the early warning signs of radiation exposure and RES mitigation techniques.


## FIRST SETUP

1. Remove device from packaging using instructions printed on top flap. Contents should include:
   - Mr. Fusion™ reactor
   - One (1) official GP He3 Reactor Fuel Pellet 
   - Printed quickstart guide
   - Warranty information
   - Regional reactor ordinance information
   - Emergency medical information
   - Five (5) iodine tablets
   - One (1) pair lead-lined gloves
   - One (1) set of high-voltage home power cables
   - Registration card
2. Identify an area of your home appropriate for reactor installation. Recommended criteria:
   - Minimum 3cm concrete/stone, 5cm soil/water, or 10cm wood/plaster between reactor and active living spaces
   - No flammable materials within 1m
   - Access to standard household high-voltage source connectors
3. Place reactor on a stable, non-flammable surface in the chosen area.
4. Connect reactor to household high-voltage source using provided cables.
5. Pull up on containment vessel release latch in front of the viewing window.
6. Remove official GP He3 Reactor Fuel Pellet from protective sheath and insert it into the containment vessel.
7. Turn the setting dial until arrow points to `FUEL PELLET (FIRST RUN)`
8. Press the green button marked `START`

## CARE & MAINTENANCE

##### Fuel
Mr. Fusion™ can accept a variety of standardized fuel pellets. Official He3-based pellets by GP are recommended, but it is also compatible with Deuterium-Tritium, Deuterium-Lithium, and select Protium-Boron pellets marked as "High-Beta Compatible."

Once the plasma toroid has been initialized with a fuel pellet, a variety of non-standard fuels can be inserted into the reactor vessel in the form of everyday materials. Lighter elements are preferred.

*__Note:__ Inserting elements heavier than Si-14 (Silicon) may result in unsafe levels of neutron flux.*

##### Emergency shutdown
In the event of malfunction, your Mr. Fusion™ can be shut down using the red button marked `STOP`.

If this fails to shut down your reactor, connect a Standard Digital Surface to the diagnostic port located on the containment vessel opposite to the viewing window using a USB-U cable and select "Console." Then enter:

<!-- encase in blockquote -->
```
init (SCRAM) [es -w -sos]
```

A confirmation window should then appear. Tap "CONFIRM", and then **immediately evacuate** all individuals within **100m** of the reactor.