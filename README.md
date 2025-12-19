# FYDP-SunDOG
A Repo for all the Programming and Coding activities and projects related to my Nanotechnology Engineering FYDP SunDOG

# What is SunDOG?
SunDOG is meant to be a After Market Polymer Film produced roll to roll that is applied to Solar Panels to increase the Power Output and Efficiency.

This thin film is comprised of 3 components, the Moth Eye Antireflective Layer, the PDMS + Quantum Dot Layer and the Adhesive Layer to stick to the panel

## Moth Eye Antireflective Layer
The Moth Eye Antireflective layer will also be made from PDMS, but is a nano scale geometric pattern mimicking the protein structures found on Moth's eyes making the film extremely antireflective. This means that the film will allow the Solar Panel to capture more incident light to boost it's power output

## PDMS + Quantum Dot Layer
The PDMS and Quantum Dot layer is the "secret sauce"/magic behind the film. The entire film is comprised of PDMS, a silicone polymer that is extremely environmentally resistant, 98% transparent and resistant to yellowing. This was chosen for it's high transparency, material propertiels and additional self cleaning properperties as the backbone of the film keeping it in a single shape

Within this PDMS will be a sparse distribution of Quantum Dots. Quantum Dots, which are popularized by modern Quantum Dot TV's, are an old and simple technology that is used for downshifting light to a narrow bandwidth. This will ideally provide the largest boost to solar panel power output. Where UV and Blue light, which are not well absorbed by Solar Panels can be downshifted to Red light and properly absorbed by Solar Panels to generate power

## Adhesive Layer
Last of all is the adhesive layer, which will be a simple adhesive used to stick the film to the Solar Panel


# Projects and Libraries
The following repo currently contains 4 Subrepos / Libraries related to the Simulations of the entire structure or simply the Moth Eye Anti Relfective Pattern. They are as follows:
- Moth-Eye-RCWA : Rigorous Coupled Wave Analysis (RCWA) scripts written in Julia to simulate the transparency, reflectivity and absorbtivity of the Antireflective layer and full solar panel stack using our film
- Moth-Eye-Raytracing : A Custom C++ Library and application with multiple Geometries, Ray Sources and more that is used to simulate the Transparency and Reflectivity of the Moth Eye Antireflective layer in a raytracing environment
- Moth-Eye-Raytracing-Data-Processing : A Library of Python Scripts used to extract data and plot the results from the C++ Raytracing simulations
- Moth-Eye-Raytracing-Python : A Prototype Python Library used to design and simulate the Moth Eye Raytracing. This was later converted to C++ for faster speeds
