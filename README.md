
# SG5103 SCM Workshop 2
Prepared by SE23PT01 Team

Vimto Soft Drinks Company
Vending Machine Control Systems(VMCS) simulation application.

Current Release : 1.0.9

#Introduction
The Vimto Soft Drinks Company operates and maintains  a large number of automatic soft drinks dispensers (vending machines) at various sites  throughout Singapore. Vimto requires a computerised control system for their new range of vending machines. For this part of the project, the system is to be designed and implemented as a computer simulation of a vending machine. The main requirements for the system are defined in "User Requirements Specification for the Vending Machine Control System (VMCS) Computer Simulation", reference ISS/VMCS/TR.1/1. The system is to be developed using object-oriented techniques and the Java programming language.

The main users of the vending machine are the:
1.	The Customer who enters Coins, selects a Drinks Brand, and collects a drinks-can from the machine.
2.	The Maintainer who monitors the stock levels of cans of each Drinks Brand and Change, and replenishes or removes stock when necessary.

In the VMCS computer simulation, which this project principally addresses, it is not possible to interface with the actual vending machine and its sensors. Hence the user panels of the vending machine, and the physical actions of the Maintainer have to be simulated. The main device chosen to achieve this is through an actor, referred to as the Controller. The sequence of the use cases which are typically performed in the system are described in the following subsections.
