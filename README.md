# HerculesGUI-HallstromPlanetarium

User Interface for Planetarium Equipment using HTML, CSS, and JavaScript.

Updated 09June2022

Comments welcome.

This interface is part of a larger project that includes a Java (working on C# .Net version now) based desktop
application that provides the webserver for the interface. The idea is to have an interface that could be easily
modified to accommodate the various equipment installations in different planetariums.

The desktop application provides browser based User Interface that can communicate with the East Coast Control Systems
Universal Theater Control System (UTCS).  The UTCS is described as follows . . .

The Universal Theater Control System (UTCS) is a full featured presentation control system, capable of controlling
almost any device that might be utilized in a planetarium theater. This means the UTCS can control a wide range of
slide projectors, special effects projectors, video projectors, laserdisc players, DVD players, S-VHS players, and video
hard disk players. The UTCS can also provide centralized control for cove lighting, room lighting, stage lighting,
dimmer panels, digital audio units, and star projectors.

The component based design uses Intelligent Controllers to control individual devices with Modular Interfaces. Up
to 64 Intelligent Controllers can control 256 discreet devices and are linked together via a high-speed communication
network. The fl exible nature of the network allows the Intelligent Controllers to be placed wherever they are needed
in the theater. Each installation is a unique design based on the theater’s control area, seating arrangement, sound
system, lighting needs, available devices, and fi nally, what works best for the operators.

The UTCS can provide consistent, reliable, Time Code controlled automated show presentations, semi-automated
shows, or completely live presentations using nothing but manual controls.

The keystone of the UTCS is the Hercules Central Processor, which uses hardware and software components to
provide control over the theater. The Hercules Show Control Software is an easy to use interface for entering
command cues and writing Show Files. All commands are transmitted over the network via the Hercules Show
Control Card to the discreet devices through the Intelligent Controllers. The Intelligent Controllers constantly
communicate back through the network to let the Hercules Show Control Software know the status of the entire
system.

Manual control for the theater is provided through the Cygnus Manual Control System. Cygnus Manual Control
System use the same communication network as the Hercules Show Control Software. The Cygnus Manual Control
System are available in several confi gurations depending on the needs of the individual theater. The Cygnus Manual
Control System can be used to augment automated shows, or provide unscripted presentations that use audience
participation and questions as the focus.

The individual components of the UTCS will be introduced and discussed in more detail in the following chapters of
this manual. Since each theater is unique, not all components may be present in the current system.
