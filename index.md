## Bio

---

I am a Machine/Deep Learning, Computer Vision, and Computational Fluid Flow Researcher with a Ph.D. in Petroleum Engineering from the University of Texas at Austin. 

My Ph.D. research focus was on simulating hydrocarbon/CO2 flow in mudrocks through pore network modeling, deep learning aided image analysis, and lattice Boltzmann simulations to reduce risk during petroleum exploration or CO2 sequestration. My Master’s research involved investigating gas hydrate deposits in Northern Gulf of Mexico to understand methane migration and accumulation in heterogeneous rocks using petrophysics, thermodynamics and machine learning.

Before graduate school, I worked as a Reservoir Engineer at Oil India Limited where our team improved oil recovery through reservoir and well-level analysis for 500+ wells using analytics and modeling. I completed my Bachelor of Petroleum Engineering from the University of Pune, and I interned at Oil and Natural Gas Corporation of India and Essar Oil Limited in Mumbai during my undergraduate studies.

I am excited about applying data science techniques and building machine learning models to help analyze complex and huge datasets faster, objectively, and more accurately. I want to extract the maximum possible information from the data available from various sources, so that we can use it to make optimal decisions while guided by expert knowledge. I am interested in creating workflows which are cross-domain and have a high impact on the end consumer.

---

## Ph.D. Research

---

Mudrocks are a type of rock that act as geological seals for CO2 stored underground or for petroleum in subsurface reservoirs. They prevent leakage by stopping the fluids from flowing upwards through them. However, they can fail if the buoyant pressure of the trapped fluid overcomes their breakthrough pressure.
  
Through a combination of techniques like pore-network modeling, deep-learning aided image analysis, and lattice Boltzmann simulations, I study the structure of the mudrock seals to determine the conditions when the caprock can fail and permit flow of the underlying stored fluid. For this purpose, I have reconstructed the 3D rock structures (and the space between them) from scanning electron microscope images and conducted flow simulations using high-performance computing resources. I found that correlated heterogeneity (connected larger spaces between rock grains) can greatly increase chances of CO2/hydrocarbon leakage through the seal.
  
<img src="images/invasion%20schematic.png?raw=true" align="middle" width="700" height="220" alt="fluid invasion">

The following video shows comparison of an upwards percolating non-wetting fluid (green) such as oil, natural gas or CO2 in two grain packs (brown), one with low silt (left) and another with high silt (right). Both, the low silt (23%) and high silt (57%) grain packs have 46% porosity. The fluid flows more easily as the pressure across the grain packs increase. It can be seen that more fluid percolation occurs and earlier breakthrough occurs in the high silt grain pack due to larger pore space between the grains. 

<img src="images/percolation%20video1.gif" align="middle" width="700" height="240" alt="Fluid percolation behavior in grain packs (low/high silt">

---

## Portfolio

---

[Multiphase LBM for Porous Media using the Palabos library](https://github.com/je-santos/MultiphasePorousMediaPalabos)

Co-developed a computational simulation toolbox for modeling multiphase flows on high-performance computing (HPC) resources, and characterizing petrophysical properties of complex porous geometries. The toolbox uses the Palabos library (C++) for lattice Boltzmann (LBM) simulations and in-house scripts created in MATLAB for calculating petrophysical properties like capillary pressure curves, relative permeability and the percolation pathway across grain packs/image slices in complex porous geometries .

<img src="images/nw_flow.jpg?raw=true" align="middle" width="340" height="300" alt="nonwetting fluid"> 

***

[Constructing a Synthetic NMR Well-log using Machine Learning](https://github.com/abhishekdbihani/synthetic_well-log_polynomial_regression)

Generated a workflow for synthetic reconstruction of a missing nuclear magnetic resonance (NMR) well log from other well logs (Gamma Ray, Caliper, Resistivity logs and the interpreted porosity) at a Gulf of Mexico location, through feature engineering, time-series analysis techniques, and multivariate polynomial regression modeling using the Scikit-learn library to increase the training R2 value from 0.26 (multivariate linear regression) to 0.54.

<img src="images/KC151-logs.png?raw=true" align="middle" width="400" height="300" alt="Well-logs at KC-151" >

***

[Semantic segmentation of mudrock SEM images](https://github.com/abhishekdbihani/deeplabV3_pores-grains)

Constructed conventional (MATLAB) and convolutional neural network (Deeplab-v3+ with TensorFlow) based image processing and segmentation workflows to identify features like pores, silt, and clay from scanning electron microscope (SEM) images with > 90% pixel-accuracy, and mean intersection over union (mIoU) results (~ 0.75) better than the random forest method (~ 0.5).

<img src="images/sem_sample1.png?raw=true" align="middle" width="550" height="300" alt="sem image">

***

[Uniaxial Compaction and Force-chain Analysis of Bidisperse Grain packs](https://github.com/abhishekdbihani/compaction_LIGGGHTS)

Created a workflow to simulate creation of a bidisperse (two-sized) grain pack under gravity and study the grain behavior subjected to uniaxial compaction, using the LIGGGHTS library (C++) on HPC resources. Scripts for post-processing like calculating, plotting and visualizing coordination numbers and force chains to study the grain behavior when subjected to compaction are also provided.

<img src="images/example%20compaction%20picture.png?raw=true" align="middle" width="550" height="300" alt="sem image">

---

## Skills

---

**Programming:** MATLAB, Python, C++, Git, Bash

**Libraries:** NumPy, SciPy, Pandas, Scikit-learn, Matplotlib, OpenCV, PyTorch, TensorFlow, XGBoost, Seaborn, Keras, Palabos, LIGGGHTS, OpenMP, MPI

**Analytics:** Spotfire, Tableau, SPSS

**Databases:** MySQL

**Cloud Computing:** AWS (SageMaker)

**Technical Knowledge:** Subsurface Machine / Deep Learning, Computer Vision, Neural Networks, High-Performance Computing, Computational Fluid Simulations in Porous Media, Digital Rock Physics, Petrophysics 

---

## Publications

---
[Google Scholar](https://scholar.google.com/citations?hl=en&user=U0P3iV4AAAAJ)

---

### A)	Peer-Reviewed Journal Articles

*Bihani A.*, Daigle H. (2019). On the Role of Spatially Correlated Heterogeneity in Determining Mudrock Sealing Capacity for CO2 Sequestration. Marine and Petroleum Geology, 106(106), 116–127.

### B)	Conference and Non-reviewed Publications

*Bihani A.* (2018). The Effects of Lifting the U.S. Oil Export Ban on Market Equilibrium. Journal of Petroleum Resource Economics, October. 

Daigle H., Cook A., Malinverno A., Nole M., *Bihani A.*, Andris R., Wei L., Hillman J. (2017). P 1693- Methane transport and accumulation in coarse-grained reservoirs in the Terrebonne Basin, northern Gulf of Mexico, 9th International Conference on Gas Hydrates, June 25-30, Denver, CO.

Jain D., *Bihani A.* (2014). PETROTECH A-2238: Crude Oil Viscosity Correlations: A Novel Approach for Upper Assam Basin. Petrotech Conference, New Delhi, India.

Haindade Z., *Bihani A.*, Javeri S., Jere C. (2012). SPE 157119: Enhancing Flow Assurance using Co-Ni Nanoparticles for Dewaxing of Production Tubing. SPE International Oilfield Nanotechnology Conference and Exhibition, 12-14 June, Noordwijk, The Netherlands.

Padalkar C., Arora A., Punase A., Patwardhan S., *Bihani A.* (2012). P-092: Improved Core recovery using in-situ freezing. 9th Biennial International Conference and Exposition on Petroleum Geophysics. 16-18 February, Hyderabad, India. 

Arora A., *Bihani A.*, Padalkar C., Punase A., Patwardhan S. (2011). IPTC 14669: Side-wall Coring: Advanced In-situ Freeze-Core Technique. International Petroleum Technology Conference, 15-17 November, Bangkok, Thailand. 

Punase A., *Bihani A.*, Patane A., John A., Arora A., Padalkar C. (2011). SPE 142658: ‘SOYBEAN SLURRY’- A New Effective, Economical and Environmentally Friendly Solution for Oil Congealing. SPE Project and Facilities Challenges Conference at METS, 13-16 Feb, Doha, Qatar.             
### C) Oral Presentations

*Bihani A.*, Daigle H., Santos J., Landry C., Prodanović M., Milliken K. (2019). H44B-06: Insight into the Sealing Capacity of Mudrocks determined using a Digital Rock Physics Workflow. AGU Fall Meeting, 9-13 December, San Francisco, USA.

*Bihani A.*, Daigle H. (2018). Grain-scale Modeling of Seal Capacity in Heterogeneous Mudrocks. Center for Petroleum and Geosystems Engineering Research Showcase, 23rd August, Austin, USA.

*Bihani A.*, Daigle H. (2018). Investigating Capillary Pressure Behavior in Mudrocks through Grain Scale Modeling. Interpore Annual Meeting, 14-17 May, New Orleans, USA.

*Bihani A.*, Mundhe P. (2014). A Review of Water Injection Operations and Requirements in Oil India Limited. March 14th, Geology and Reservoir Department, Oil India Limited. Duliajan, Assam, India.

*Bihani A.* (2013). An Overview of High Pour-Point Oil and Heavy Oil Reserves in Upper Assam Basin. December 26th, Geology and Reservoir Department, Oil India Limited. Duliajan, Assam, India.

### D) Poster Presentations 

*Bihani A.*, Daigle H., Santos J., Landry C., Prodanović M., Milliken K. (2019). Insight into the Sealing Capacity of Mudrocks determined using Digital Rock Physics. TACC Symposium for Texas Researchers (TACCSTER), 26-27 September, Austin, TX, USA.

*Bihani A.*, Daigle H. (2019). Investigating Sealing Capacity and Percolation in Mudrocks through Grain Scale Modeling. Presented at the Spring 2019 Virtual Poster Showcase, American Geophysical Union, Washington, DC.

*Bihani A.*, Daigle H. (2019). Poster 79: Investigating Capillary Pressure Behavior in Mudrocks through Grain Scale Modeling. Graduate and Industry Networking Conference, 5 February, Austin, TX.

*Bihani A.*, Daigle H., Cook A., Glosser D., Shushtarian A. (2015). OS23B-1999: Pore Size Distribution and Methane Equilibrium Conditions at Walker Ridge Block 313, Northern Gulf of Mexico. AGU Fall Meeting, 14-18 December, San Francisco, USA.

*Bihani A.*, Haindade Z., Jain D. (2012). A study on Electrolysis assisted Gas-Lift for Dewatering CBM Reservoirs. Association of Petroleum Geologists Conference, 30 September, Duliajan, Assam, India. 

### E) Datasets 

*Bihani, A.*, & Daigle, H. (2019, March 5). Bidisperse sphere packs generated under gravity. Retrieved February 23, 2020, from http://www.digitalrocksportal.org/projects/204

*Bihani, A.*, Daigle, H., Prodanovic, M., Milliken, K., Landry, C., & E. Santos, J. (2020, January 20). Mudrock images from Nankai Trough. Retrieved February 23, 2020, from http://www.digitalrocksportal.org/projects/259

---

## Professional Development

---

**Awards**

Department of Petroleum and Geosystems Engineering Research Award,  			     GAIN Conference Austin, 2019

Advanced Communicator Bronze / Competent Leader,  					                   Toastmasters International, 2011

**Grants and Fellowships**

Statoil/Equinor Fellowship, 									                                 UT Austin, 2016 – 2019

Research Fellowship, U.S. Department of Energy,						                     UT Austin, 2014 – 2016

**Service**

Graduate Faculty Selection Committee, 								                         UT Austin, 2017 – 2019

Young Professionals Committee - Society of Petroleum Engineers,                Oil India Limited, 2012 - 2014 

Presiding Officer – Dibrugarh Constituency, Indian Parliamentary Election,  	 Election Commission of India, 2014

Vice President, Public Relations,   					                                 Toastmasters Club of Pune – West, 2010 – 2011

President, 	                                                                 Society of Petroleum Engineers Student Chapter, 2010 – 2011

**Memberships in Professional Societies**

Member, American Geophysical Union (AGU)

Member, International Society for Porous Media (Interpore)

Member, Society of Petroleum Engineers (SPE) 

Member, Society of Petrophysicists and Well Log Analysts (SPWLA)

---

## Teaching Experience

---

*Role:* Teaching Assistant

*Course:* Petroleum and Geosystems Engineering Design

*Period:* Fall - 2019

*Instructor:* Dr. Hugh Daigle

*Responsibilities:*

Grading fortnightly progress reports and holding office hours for a senior design project about field development and reservoir management, consisting of through oil-in-place estimation, decline curve analysis, material balance studies, and drainage radii calculations using a combination of available field data.

---

## Download

---

<p> <a href="pdf/Abhishek%20-%20ds%20resume%20v3%20-%20Spring%202020.pdf" target="_blank"> Here </a> is a copy of my resume. </p>

---
