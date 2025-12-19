# FYDP-SunDOG
A Repo for all the Programming and Coding activities and projects related to my Nanotechnology Engineering FYDP (Fourth Year Design Project / Capstone) SunDOG

# What is SunDOG?
SunDOG is meant to be a After Market Polymer Film produced roll to roll that is applied to Solar Panels to increase the Power Output and Efficiency.

This thin film is comprised of 3 components, the Moth Eye Antireflective Layer, the PDMS + Quantum Dot Layer and the Adhesive Layer to stick to the panel

<img width="1870" height="1048" alt="image" src="https://github.com/user-attachments/assets/c9375c4d-a4c0-49b6-a315-23f5458afdd5" />

## Moth Eye Antireflective Layer
The Moth Eye Antireflective layer will also be made from PDMS, but is a nano scale geometric pattern mimicking the protein structures found on Moth's eyes making the film extremely antireflective. This means that the film will allow the Solar Panel to capture more incident light to boost it's power output

## PDMS + Quantum Dot Layer
The PDMS and Quantum Dot layer is the "secret sauce"/magic behind the film. The entire film is comprised of PDMS, a silicone polymer that is extremely environmentally resistant, 98% transparent and resistant to yellowing. This was chosen for it's high transparency, material propertiels and additional self cleaning properperties as the backbone of the film keeping it in a single shape

Within this PDMS will be a sparse distribution of Quantum Dots. Quantum Dots, which are popularized by modern Quantum Dot TV's, are an old and simple technology that is used for downshifting light to a narrow bandwidth. This will ideally provide the largest boost to solar panel power output. Where UV and Blue light, which are not well absorbed by Solar Panels can be downshifted to Red light and properly absorbed by Solar Panels to generate power

## Adhesive Layer
Last of all is the adhesive layer, which will be a simple adhesive used to stick the film to the Solar Panel


# Projects and Libraries
The following repo currently contains 4 Subrepos / Libraries related to the Simulations of the entire structure or simply the Moth Eye Anti Relfective Pattern. They are as follows:
- [Moth-Eye-RCWA](https://github.com/MrDNAlex/Moth-Eye-RCWA/tree/main) : Rigorous Coupled Wave Analysis (RCWA) scripts written in Julia to simulate the transparency, reflectivity and absorbtivity of the Antireflective layer, film and solar panel stack our film by solving the Maxwell Equations
- [Moth-Eye-Raytracing](https://github.com/MrDNAlex/Moth-Eye-Raytracing/tree/main) : A Custom C++ Library and application with multiple Geometries, Ray Sources and more that is used to simulate the Transparency and Reflectivity of the Moth Eye Antireflective layer in a raytracing environment
- [Moth-Eye-Raytracing-Data-Processing](https://github.com/MrDNAlex/Moth-Eye-Raytracing-Data-Processing/tree/main) : A Library of Python Scripts used to extract data and plot the results from the C++ Raytracing simulations
- [Moth-Eye-Raytracing-Python](https://github.com/MrDNAlex/Moth-Eye-Raytracing-Python/tree/main) : A Prototype Python Library used to design and simulate the Moth Eye Raytracing. This was later converted to C++ for faster speeds

# Alternative Projects
Further development of the Raytracing Library has been done in the following repo for the Final Project of my Simulation Methods class (NE 451). This furthers the implementation by adding Monte Carlo sampling elements to make more accurate simulations. This also involves further optimizations such as BVH (Bounded Volume Hierarchy) Optimizations making the raytracing over 10x faster
- [NE-451-Final-Project-Raytracing](https://github.com/MrDNAlex/NE-451-Final-Project-Raytracing/main)

# Results
Results achieved and presented to our Consultant Professor at the end of Nov 2025
<img width="1867" height="1050" alt="image" src="https://github.com/user-attachments/assets/aed275d4-b43c-4c83-9d44-04b5923ac4a2" />

<img width="1867" height="1041" alt="image" src="https://github.com/user-attachments/assets/9f78b05e-f396-46c2-8333-8ac184d85f3f" />

<img width="1868" height="1048" alt="image" src="https://github.com/user-attachments/assets/53819ec2-223a-45fa-9c9f-d9241df276f6" />


