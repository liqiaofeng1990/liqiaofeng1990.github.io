---
title: "Marine energy conversion"
excerpt: "The ocean possesses enormous sustainable and renewable energy in the form of wave, current, salinity difference, and temperature difference. We exploit this energy fountain, by designing multi-scale machinery to convert the largely untapped wave and hydrokinetic energy. We solve the challenges from 3 perspectives: hydrodynamics, power take-off, and control.<br/><img src='/images/researchthemes_marineenergyconverter_overall.png'>"
collection: research
---

![](/images/researchthemes_marineenergyconverter_overall.png)

Marine and hydrokinetic (MHK) energy conversion technology harvests the abundant wave and current energy in the ocean. The US department of energy (DOE) has identified 3 thrust research areas to advance the technology and commericial maturation of the MHK industry:
1. hydrodynamics
2. power take-off (PTO)
3. control

Hydrodynamics refers to the optimization of the fluid-structure interaction of a device so that the ocean energy can be absorbed by the device as much as possible; PTO is the core mechanism of a MHK device, in charge of converting kinetic energy of the device into pressure energy for desalination or electricity for power generation; Control, by integrating sensors, actuators, hydrodynamic shape of the device, and unique PTO features, maximizes the power output in different working conditions and provide motion constraints in extreme conditions. These 3 components constitute what we call a "wave-to-wire"/"wave-to-water" model, i.e., the model to predict electric power or desalinized water production given a certain wave condition.

In these 3 components, hydrodynamics modelling is the most fundamental and essential one, since it directly constrains the validity of PTO modelling and control strategies. The mainstream modelling techniques can be categorized based on fidelity as in the following figure. 

![](/images/researchthemes_marineenergyconverter_hydrodynamics.png)

Linear potential flow theory is the most prevalent technique to model the hydrodynamics of wave energy converters. Linear potential flow theory assumes no viscosity of the fluid and small vibration motion of wave energy converters. So the motion and generated energy is generally overestimated by this theory. Drag damping correction, typically using Morrison's equation, can be integrated for viscosity effect. However, the small vibration motion assumption is the fundamental limitation. So in the wave energy converter design flow, linear potential flow theory is generally adopted to provide preliminary power estimation. The final system validation should resort to high-fidelity modelling techniques, such as RANS and LES.