# FYDP-SunDOG
A Repo for all the Programming and Coding activities and projects related to my Nanotechnology Engineering FYDP (Fourth Year Design Project / Capstone) SunDOG

# What is SunDOG?
SunDOG is meant to be a After Market Polymer Film produced roll to roll that is applied to Solar Panels to increase the Power Output and Efficiency.

This thin film is comprised of 3 components, the Moth Eye Antireflective Layer, the PDMS + Quantum Dot Layer and the Adhesive Layer to stick to the panel

For full details about the project read the Capstone Engineering Report named `NE_2026_20_FinalReport.pdf` in the repository

<img width="1870" height="1048" alt="image" src="https://github.com/user-attachments/assets/c9375c4d-a4c0-49b6-a315-23f5458afdd5" />

## Moth Eye Antireflective Layer
The Moth Eye Antireflective layer will also be made from PDMS, but is a nano scale geometric pattern mimicking the protein structures found on Moth's eyes making the film extremely antireflective. This means that the film will allow the Solar Panel to capture more incident light to boost it's power output

## PDMS + Quantum Dot Layer
The PDMS and Quantum Dot layer is the "secret sauce"/magic behind the film. The entire film is comprised of PDMS, a silicone polymer that is extremely environmentally resistant, 98% transparent and resistant to yellowing. This was chosen for it's high transparency, material propertiels and additional self cleaning properperties as the backbone of the film keeping it in a single shape

Within this PDMS will be a sparse distribution of Quantum Dots. Quantum Dots, which are popularized by modern Quantum Dot TV's, are an old and simple technology that is used for downshifting light to a narrow bandwidth. This will ideally provide the largest boost to solar panel power output. Where UV and Blue light, which are not well absorbed by Solar Panels can be downshifted to Red light and properly absorbed by Solar Panels to generate power

## Adhesive Layer
Last of all is the adhesive layer, which will be a simple adhesive used to stick the film to the Solar Panel

## Assembled Prototype
The assembled prototype is not identical to the initial, design. Due to manufacturing issues the Quantum Dots were dropcasted onto the PET layer and sandwiched by the PDMS layer. This was an emergency patch at the time. Despite these manufacturing issues, it is still 2% more effective than a base panel, and would be much more once we solve the issues. The orange on the panel are the Quantum Dots that were dropcasted

<img width="839" height="492" alt="image" src="https://github.com/user-attachments/assets/57cee977-db6d-4d52-92d9-79b9e6c76c80" />

## Prototype Fabrication
<img width="1230" height="792" alt="image" src="https://github.com/user-attachments/assets/c2c63e87-8856-4e87-8de7-7d902d870798" />

# Projects and Libraries
The following repo currently contains 4 Subrepos / Libraries related to the Simulations of the entire structure or simply the Moth Eye Anti Relfective Pattern. They are as follows:
- [Moth-Eye-RCWA](https://github.com/MrDNAlex/Moth-Eye-RCWA/tree/main) : Rigorous Coupled Wave Analysis (RCWA) scripts written in Julia to simulate the transparency, reflectivity and absorbtivity of the Antireflective layer, film and solar panel stack our film by solving the Maxwell Equations
- [Moth-Eye-Raytracing](https://github.com/MrDNAlex/Moth-Eye-Raytracing/tree/main) : A Custom C++ Library and application with multiple Geometries, Ray Sources and more that is used to simulate the Transparency and Reflectivity of the Moth Eye Antireflective layer in a raytracing environment
- [Moth-Eye-Raytracing-Data-Processing](https://github.com/MrDNAlex/Moth-Eye-Raytracing-Data-Processing/tree/main) : A Library of Python Scripts used to extract data and plot the results from the C++ Raytracing simulations
- [Moth-Eye-Raytracing-Python](https://github.com/MrDNAlex/Moth-Eye-Raytracing-Python/tree/main) : A Prototype Python Library used to design and simulate the Moth Eye Raytracing. This was later converted to C++ for faster speeds

# Alternative Projects
Further development of the Raytracing Library has been done in the following repo for the Final Project of my Simulation Methods class (NE 451). This furthers the implementation by adding Monte Carlo sampling elements to make more accurate simulations. This also involves further optimizations such as BVH (Bounded Volume Hierarchy) Optimizations making the raytracing over 10x faster
- [NE-451-Final-Project-Raytracing](https://github.com/MrDNAlex/NE-451-Final-Project-Raytracing/main)

# Simulations
The following shows the Raytracing and RCWA Scenarios that were simulated for the Device Validation Portion of the FYDP

## RCWA 
Crosssectional geometries of RCWA tests
<img width="974" height="723" alt="image" src="https://github.com/user-attachments/assets/ba1bc46f-89c0-4e32-b6fe-1d98bcc429b8" />

## Raytracing
### Python Raytracing Tests
Test Scenarios to test the Python Version of the Raytracer
<img width="735" height="573" alt="image" src="https://github.com/user-attachments/assets/bafae195-63eb-48f7-a1b0-94828b91af66" />
<img width="737" height="578" alt="image" src="https://github.com/user-attachments/assets/a0473f2b-0d2d-4a2f-813a-b9175c549f6c" />

### C++ Raytracer Tests
The following shows the simulation scenarios tested by the C++ Raytracer
#### Initial Benchmarking Simulations
Initial test simulations that were run to benchmark the raytracer and estimate the devices performance.
<img width="926" height="405" alt="image" src="https://github.com/user-attachments/assets/dd877889-0e1c-4318-a4ee-15b2fcff9f67" />
<img width="691" height="707" alt="image" src="https://github.com/user-attachments/assets/90e04493-b073-4ee1-aca6-78434efbe354" />
<img width="696" height="701" alt="image" src="https://github.com/user-attachments/assets/fe145a52-15cb-4e4c-a1a3-b53ca80e9cc6" />
<img width="801" height="477" alt="image" src="https://github.com/user-attachments/assets/adbdeb3f-73e2-46d2-8b49-ef9a95b13362" />
<img width="721" height="725" alt="image" src="https://github.com/user-attachments/assets/603012b0-13a2-4f14-ab22-97fa21fb5ee9" />
<img width="778" height="463" alt="image" src="https://github.com/user-attachments/assets/08682919-7322-437a-8bed-d9b789338f18" />
<img width="975" height="534" alt="image" src="https://github.com/user-attachments/assets/97d5314a-eaf6-4acf-a5ce-2e778265948f" />

#### Solcore Data Simulations
Simulations ran to establish data curves which were then subsequently used for the Solcore simulations to estimate the device PCE
<img width="949" height="623" alt="image" src="https://github.com/user-attachments/assets/6b2a50c5-c590-4bc0-85ae-d034a55a9984" />
<img width="952" height="607" alt="image" src="https://github.com/user-attachments/assets/69b0f518-5bc1-4dfc-9d5e-b4bf25686e24" />
<img width="936" height="597" alt="image" src="https://github.com/user-attachments/assets/249c4489-66c1-4acf-b106-fea1fdfea427" />
<img width="941" height="609" alt="image" src="https://github.com/user-attachments/assets/510e3a00-bd4e-4844-840c-816a0416db5e" />
<img width="947" height="598" alt="image" src="https://github.com/user-attachments/assets/bd273997-47a8-4d11-bf67-175f19333cd8" />
<img width="949" height="599" alt="image" src="https://github.com/user-attachments/assets/7ad276c0-6cac-4d45-91a6-58bb6483894a" />
<img width="974" height="644" alt="image" src="https://github.com/user-attachments/assets/f27d83b1-e612-48e0-92b3-208f8b8069f5" />

# Results
## Consultant Presentation
Results achieved and presented to our Consultant Professor at the end of Nov 2025
<img width="1867" height="1050" alt="image" src="https://github.com/user-attachments/assets/aed275d4-b43c-4c83-9d44-04b5923ac4a2" />

<img width="1867" height="1041" alt="image" src="https://github.com/user-attachments/assets/9f78b05e-f396-46c2-8333-8ac184d85f3f" />

<img width="1868" height="1048" alt="image" src="https://github.com/user-attachments/assets/53819ec2-223a-45fa-9c9f-d9241df276f6" />

## RCWA 
The results received by the RCWA simulations
<img width="974" height="446" alt="image" src="https://github.com/user-attachments/assets/9feb4dc6-2f02-4cd6-95c9-f1a9498175fa" />
<img width="974" height="446" alt="image" src="https://github.com/user-attachments/assets/54fc6af0-514a-43af-99fe-ebbb1ddb1b33" />
<img width="974" height="446" alt="image" src="https://github.com/user-attachments/assets/d40d7fea-ec7b-4995-aedc-190eba8a7c67" />
<img width="974" height="468" alt="image" src="https://github.com/user-attachments/assets/090a9127-776d-4f38-b660-c0af54bbb9e2" />
<img width="974" height="468" alt="image" src="https://github.com/user-attachments/assets/2b3d49c4-cd09-4c71-a734-c6d4835b217a" />
<img width="974" height="468" alt="image" src="https://github.com/user-attachments/assets/87d3ca3e-a744-4640-ad6f-853d04144bd9" />
<img width="973" height="320" alt="image" src="https://github.com/user-attachments/assets/2e2ead54-0bce-4de3-aca4-c63a53f3d28f" />
<img width="973" height="320" alt="image" src="https://github.com/user-attachments/assets/a1f17afc-3df3-4972-8df5-8afd743e0766" />
<img width="973" height="320" alt="image" src="https://github.com/user-attachments/assets/e190fa7c-dcc8-4b82-96a4-9276e7039a6b" />
<img width="973" height="320" alt="image" src="https://github.com/user-attachments/assets/84c95a34-66b2-4aa5-9afa-a5bb3de033b0" />

### C++ Initial Benchmark Raytracer
<img width="975" height="399" alt="image" src="https://github.com/user-attachments/assets/2fa3bc8c-748f-46d4-8882-7bee8d5c38d0" />
<img width="973" height="406" alt="image" src="https://github.com/user-attachments/assets/2b2a50af-274a-4c68-893c-58644f14803c" />
<img width="973" height="406" alt="image" src="https://github.com/user-attachments/assets/e32972d0-1c88-4776-8226-b60d5338e5ee" />
<img width="973" height="406" alt="image" src="https://github.com/user-attachments/assets/594ae4f7-6855-4045-8aac-44d36e36d7fe" />
<img width="973" height="406" alt="image" src="https://github.com/user-attachments/assets/21cae2f5-8e41-4f7b-b05d-c1f76d0fd648" />
<img width="974" height="609" alt="image" src="https://github.com/user-attachments/assets/0342fd4d-b600-4a9b-bb34-edf5fe943ac4" />
<img width="974" height="431" alt="image" src="https://github.com/user-attachments/assets/efba8213-c6e8-416f-9cdf-1012463b2e64" />

### Solcore C++ Raytracer 
<img width="973" height="279" alt="image" src="https://github.com/user-attachments/assets/df775a3c-181f-445d-b080-e12d44718c68" />
<img width="973" height="279" alt="image" src="https://github.com/user-attachments/assets/ea06f57a-e9e2-4536-bc4a-84ae6fa13f6e" />
<img width="973" height="279" alt="image" src="https://github.com/user-attachments/assets/c54860e6-29c8-4fa9-897b-844ff80ddadc" />
<img width="974" height="280" alt="image" src="https://github.com/user-attachments/assets/70182dd9-4863-4e9b-9a2c-318cff5f9c85" />
<img width="974" height="280" alt="image" src="https://github.com/user-attachments/assets/b4ba97b9-b7bf-4ee1-a053-bc292c055461" />
<img width="974" height="278" alt="image" src="https://github.com/user-attachments/assets/65b1e65d-e98f-4e56-bfa1-133d514d897b" />
<img width="973" height="279" alt="image" src="https://github.com/user-attachments/assets/624f1b05-5baa-400d-b1ee-62980a835aa0" />

