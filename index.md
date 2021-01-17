## Bio

---

I am a Researcher using Machine/Deep Learning, Computer Vision, and Computational Fluid Simulations in Porous Media in my work.

I have experience building machine learning workflows in the cloud and I have completed the AWS Machine Learning Specialty certification (MLS-C01). I am passionate about applying data science techniques to help analyze complex and huge datasets faster, objectively, and more accurately. I believe today's tools and technology can allow us to extract the maximum possible information from the different available data sources, so that we can use it to make optimal decisions that have a high impact on the end consumer.

I did my Ph.D. at the University of Texas at Austin, where my doctoral research involved analyzing hydrocarbon/CO<sub>2</sub> flow in rocks through image analysis, semantic image segmentation using CNNs, and fluid flow simulations in order to reduce risk during petroleum exploration or CO<sub>2</sub> sequestration. My Master’s research involved investigating gas hydrate deposits in Northern Gulf of Mexico to understand methane migration and accumulation in heterogeneous rocks using petrophysics, thermodynamics, and machine learning.

Before graduate school, I worked as a Reservoir Engineer at Oil India Limited where our team improved oil recovery through reservoir and well-level analysis for 500+ wells using statistical analysis and modeling. I completed my Bachelor of Petroleum Engineering from the University of Pune, and I interned at Oil and Natural Gas Corporation of India and Essar Oil Limited in Mumbai during my undergraduate studies.

---

## Ph.D. Research

---

Mudrocks are a type of rock that act as geological seals for CO<sub>2</sub> stored underground or for petroleum in subsurface reservoirs. They prevent leakage by stopping the fluids from flowing upwards through them. However, they can fail if the buoyant pressure of the trapped fluid overcomes their breakthrough pressure.
  
Through a combination of techniques like pore-network modeling, deep-learning aided image analysis, and lattice Boltzmann simulations, I studied the structure of the mudrock seals to determine the conditions when the caprock can fail and permit flow of the underlying stored fluid. For this purpose, I reconstructed the 3D rock structures (and the space between them) from scanning electron microscope images and conducted flow simulations using high-performance computing resources. I found that correlated heterogeneity (connected larger spaces between rock grains) can greatly increase chances of CO<sub>2</sub>/hydrocarbon leakage through the seal. I conveyed my inferences to my research sponsor, Equinor, as well as other researchers through conferences and papers for reducing the risk during petroleum exploration and carbon sequestration.
  
<img src="images/invasion%20schematic.png?raw=true" align="middle" width="700" height="220" alt="fluid invasion">

The following video shows comparison of an upwards percolating non-wetting fluid (green) such as oil, natural gas or CO<sub>2</sub> in two grain packs (brown), one with low silt (left) and another with high silt (right). Both, the low silt (23%) and high silt (57%) grain packs have 46% porosity. The fluid flows more easily as the pressure across the grain packs increase. It can be seen that more fluid percolation occurs and earlier breakthrough occurs in the high silt grain pack due to larger pore space between the grains. 

<img src="images/percolation%20video1.gif" align="middle" width="700" height="240" alt="Fluid percolation behavior in grain packs (low/high silt">

---

## Portfolio

---

[Constructing a Synthetic NMR Well-log using Machine Learning](https://github.com/abhishekdbihani/synthetic_well-log_polynomial_regression)

Generated a workflow for synthetic reconstruction of a missing nuclear magnetic resonance (NMR) well log from other well logs (Gamma Ray, Caliper, Resistivity logs and the interpreted porosity) at a Gulf of Mexico location, through feature engineering, time-series analysis techniques, and multivariate polynomial regression modeling using the Scikit-learn library to increase the training R2 value from 0.26 (multivariate linear regression) to 0.54.

<img src="images/KC151-logs.png?raw=true" align="middle" width="400" height="300" alt="Well-logs at KC-151" >

***

[Home Credit Default Risk Recognition](https://github.com/abhishekdbihani/Home-Credit-Default-Risk-Recognition)

Trained a binary classifier in Python to recognize the risk of housing loan default in imbalanced data using a complete end-to-end machine learning workflow. Used ETL processes to connect relational databases through automated feature engineering, and applied machine learning methods like logistic regression, random forest, and gradient boosting (Scikit-learn, XGBoost, LightGBM) for understanding client factors that cause loan default. Improved ROC AUC from 0.745 (base case) to 0.786 on the test dataset with K-fold cross-validation and hyperparameter tuning methods like grid/random search, and Bayesian optimization.

<img src="images/roc_auc_compare.PNG?raw=true" align="middle" width="400" height="300" alt="ROC AUC classifier comparison" >

***

[MudrockNet: Semantic segmentation of mudrock SEM images](https://github.com/abhishekdbihani/deeplabV3_pores-grains)

Constructed a conventional image processing and segmentation (MATLAB) workflow for ground-truth, and a convolutional neural network segmentation model termed MudrockNet (using Deeplab-v3+ architecture with TensorFlow)  to identify features like pores, silt grains, and clay from scanning electron microscope (SEM) images with > 90% pixel-accuracy, and mean intersection over union (mIoU) test results (> 0.65) better than the random forest method (~ 0.5).

<img src="images/sem_sample1.png?raw=true" align="middle" width="550" height="270" alt="sem image">

***

[Multiphase LBM Toolbox: Permeable media analysis using the Palabos library and in-house codes](https://github.com/je-santos/MultiphasePorousMediaPalabos)

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3842280.svg)](https://doi.org/10.5281/zenodo.3842280)

Co-developed and released an open-source computational simulation toolbox for modeling multiphase flows in porous media on high-performance computing (HPC) resources, and characterizing petrophysical properties of complex porous geometries. The toolbox uses the Palabos library (C++) for lattice Boltzmann (LBM) simulations and in-house scripts created in MATLAB for calculating petrophysical properties like capillary pressure curves, relative permeability and the percolation pathway across grain packs/image slices in complex porous geometries .

<img src="images/nw_flow.jpg?raw=true" align="middle" width="340" height="300" alt="nonwetting fluid"> 

***

[Uniaxial Compaction and Force-chain Analysis of Bidisperse Grain packs](https://github.com/abhishekdbihani/compaction_LIGGGHTS)

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.4021433.svg)](https://doi.org/10.5281/zenodo.4021433)

Created a workflow to simulate creation of a bidisperse (two-sized) grain pack under gravity and study the grain behavior subjected to uniaxial compaction, using the LIGGGHTS library (C++) on HPC resources. Scripts for post-processing like calculating, plotting and visualizing coordination numbers and force chains to study the grain behavior when subjected to compaction are also provided.

<img src="images/example%20compaction%20picture.png?raw=true" align="middle" width="550" height="320" alt="sem image">

---

## Skills

---

**Programming:** MATLAB, Python, C++, Git, Bash, SQL

**Libraries:** NumPy, SciPy, Pandas, Scikit-learn, Matplotlib, Seaborn, OpenCV, PyTorch, TensorFlow, Keras, PySpark, XGBoost, LightGBM, Featuretools, Hyperopt, Palabos, LIGGGHTS

**Analytics:** Tableau, SPSS

**Cloud Computing:** AWS (SageMaker, S3, EC2, ECR, Kinesis, Glue, Athena, QuickSight)

**Technical Knowledge:** Subsurface Machine / Deep Learning, Computer Vision, Image Analysis, AWS, Neural Networks, Statistical Analysis, High-Performance Computing, Computational Fluid Dynamics (CFD) in Porous Media, Digital Rock Physics, Petrophysics, Reservoir Engineering 

---

## Certifications

---

<img src="images/certification%20logos.png?raw=true" align="middle" width="600" height="250" alt="certification logos">

[AWS Certified Machine Learning - Specialty (MLS-C01)](https://www.youracclaim.com/earner/earned/badge/fef4071d-9451-4316-9258-df8b5b9bae2e) (2020). AWS.

[Computer Vision Nanodegree](https://graduation.udacity.com/confirm/SC5C7E5A) (2020). Udacity

[Machine Learning Engineer Nanodegree](https://graduation.udacity.com/confirm/CSYW6GKW) (2020). Udacity

---


## Education

---

<img src="images/education%20logos.PNG?raw=true" align="middle" width="600" height="230" alt="certification logos">

<b> The University of Texas at Austin, USA </b>

Ph.D. - Petroleum Engineering,  			            		         	          May 2020

M.S.  - Petroleum Engineering, 						 		       	                    May 2016

<b> Maharashtra Institute of Technology, University of Pune, India </b>

B.E.  - Petroleum Engineering (Honors: Silver Medalist),			 		        May 2011

---

## Experience

---

<img src="images/experience%20logos.PNG?raw=true" align="middle" width="700" height="120" alt="certification logos">

<b> Graduate Researcher </b> – Center for Subsurface Energy & the Environment (CSEE), University of Texas at Austin, Aug 2014 – May 2020

<b> Reservoir Engineer </b> – Geology & Reservoir Engineering Department, Oil India Limited (OIL), Oct 2011 – Jul 2014

<b> Undergraduate Intern </b> – Oil and Natural Gas Corporation of India (ONGC), Jan 2011 – Jun 2011 

<b> Summer Intern </b> – Essar Oil Limited, Jun 2010 – Jul 2010

---

## Publications

---
[Google Scholar](https://scholar.google.com/citations?hl=en&user=U0P3iV4AAAAJ)

[ORCID](https://orcid.org/0000-0002-1522-4192)<a itemprop="sameAs" content="https://orcid.org/0000-0002-1522-4192" href="https://orcid.org/0000-0002-1522-4192" target="orcid.widget" rel="me noopener noreferrer" style="vertical-align:top;"><img src="https://orcid.org/sites/default/files/images/orcid_16x16.png" style="width:1em;margin-right:.5em;" alt="ORCID iD icon"></a>

---

### A)	Peer-Reviewed Journal Articles

*Bihani A.*, Daigle H. (2019). On the Role of Spatially Correlated Heterogeneity in Determining Mudrock Sealing Capacity for CO2 Sequestration. Marine and Petroleum Geology, 106(106), 116–127. https://doi.org/10.1016/j.marpetgeo.2019.04.038. [PDF](https://doi.org/10.1016/j.marpetgeo.2019.04.038)

*Bihani A.*, Daigle H., Santos J., Landry C., Prodanović M., Milliken K. (in-review). MudrockNet: Semantic Segmentation of Mudrock SEM Images through Deep Learning. Computers & Geosciences. [PDF](https://www.researchgate.net/publication/343808876_MudrockNet_Semantic_Segmentation_of_Mudrock_SEM_Images_through_Deep_Learning)

*Bihani A.*, Daigle H., Santos J., Landry C., Prodanović M., Milliken K. (in-review). Investigating Silt Bridging in Marine Muds of the Kumano Forearc Basin through Image Analysis. Marine & Petroleum Geology. [PDF](https://www.researchgate.net/publication/345731962_Investigating_Silt_Bridging_in_Marine_Muds_of_the_Kumano_Forearc_Basin_through_Image_Analysis)

*Bihani A.*, Daigle H. (in-review). Seal Capacity, Force Chains, and Percolation in Silt-Clay Mixtures. Preprint. https://doi.org/10.1002/essoar.10504349.1. [PDF](https://doi.org/10.1002/essoar.10504349.1)

Daigle, H., Cook, A. E., Fang, Y., *Bihani, A.*, Song, W., Flemings, P. B. (in-press). Gas-driven tensile fracturing in shallow marine sediments. Journal of Geophysical Research- Solid Earth. https://doi.org/10.1002/essoar.10503987.1. [PDF](https://doi.org/10.1002/essoar.10503987.1)


### B)	Conference and Non-reviewed Publications

*Bihani A.* (2018). The Effects of Lifting the U.S. Oil Export Ban on Market Equilibrium. Journal of Petroleum Resource Economics, October. [PDF](https://www.researchgate.net/publication/328492767_The_Effects_of_Lifting_the_US_Oil_Export_Ban_on_Market_Equilibrium)

Daigle H., Cook A., Malinverno A., Nole M., *Bihani A.*, Andris R., Wei L., Hillman J. (2017). P 1693- Methane transport and accumulation in coarse-grained reservoirs in the Terrebonne Basin, northern Gulf of Mexico, 9th International Conference on Gas Hydrates, June 25-30, Denver, CO. [PDF](https://www.semanticscholar.org/paper/Methane-Transport-and-Accumulation-in-Reservoirs-in-Daigle-Cook/934e47919721d01fa51c7f2dbad24e65bd1cc463?p2df)

Jain D., *Bihani A.* (2014). PETROTECH A-2238: Crude Oil Viscosity Correlations: A Novel Approach for Upper Assam Basin. Petrotech Conference, 12-15 Jan, New Delhi, India. [PDF](https://www.researchgate.net/publication/274310547_Crude_oil_viscosity_correlations_A_novel_approach_for_Upper_Assam_Basin)

Haindade Z., *Bihani A.*, Javeri S., Jere C. (2012). SPE 157119: Enhancing Flow Assurance using Co-Ni Nanoparticles for Dewaxing of Production Tubing. SPE International Oilfield Nanotechnology Conference and Exhibition, 12-14 June, Noordwijk, The Netherlands.https://doi.org/10.2118/157119-MS. [PDF](https://doi.org/10.2118/157119-MS)

Padalkar C., Arora A., Punase A., Patwardhan S., *Bihani A.* (2012). P-092: Improved Core recovery using in-situ freezing. 9th Biennial International Conference and Exposition on Petroleum Geophysics. 16-18 February, Hyderabad, India. [PDF](https://www.spgindia.org/spg_2012/spgp092.pdf)

Arora A., *Bihani A.*, Padalkar C., Punase A., Patwardhan S. (2011). IPTC 14669: Side-wall Coring: Advanced In-situ Freeze-Core Technique. International Petroleum Technology Conference, 15-17 November, Bangkok, Thailand. https://doi.org/10.2523/IPTC-14669-MS. [PDF](https://doi.org/10.2523/IPTC-14669-MS)

Punase A., *Bihani A.*, Patane A., John A., Arora A., Padalkar C. (2011). SPE 142658: ‘SOYBEAN SLURRY’- A New Effective, Economical and Environmentally Friendly Solution for Oil Congealing. SPE Project and Facilities Challenges Conference at METS, 13-16 Feb, Doha, Qatar. https://doi.org/10.2118/142658-MS. [PDF](https://doi.org/10.2118/142658-MS)

### C) Oral Presentations

*Bihani A.*, Daigle H., Santos J., Landry C., Prodanović M., Milliken K. (2019). H44B-06: Insight into the Sealing Capacity of Mudrocks determined using a Digital Rock Physics Workflow. AGU Fall Meeting, 9-13 December, San Francisco, USA. [Abstract](https://ui.adsabs.harvard.edu/abs/2019AGUFM.H44B..06B/abstract)

*Bihani A.*, Daigle H. (2018). Grain-scale Modeling of Seal Capacity in Heterogeneous Mudrocks. Center for Petroleum and Geosystems Engineering Research Showcase, 23rd August, Austin, USA.

*Bihani A.*, Daigle H. (2018). Investigating Capillary Pressure Behavior in Mudrocks through Grain Scale Modeling. Interpore Annual Meeting, 14-17 May, New Orleans, USA. [Abstract](https://events.interpore.org/event/2/contributions/210/)

*Bihani A.*, Mundhe P. (2014). A Review of Water Injection Operations and Requirements in Oil India Limited. March 14th, Geology and Reservoir Department, Oil India Limited. Duliajan, Assam, India.

*Bihani A.* (2013). An Overview of High Pour-Point Oil and Heavy Oil Reserves in Upper Assam Basin. December 26th, Geology and Reservoir Department, Oil India Limited. Duliajan, Assam, India.

### D) Poster Presentations 

*Bihani A.*, Daigle H., Santos J., Landry C., Prodanović M., Milliken K. (2019). Insight into the Sealing Capacity of Mudrocks determined using Digital Rock Physics. TACC Symposium for Texas Researchers (TACCSTER), 26-27 September, Austin, TX, USA. http://dx.doi.org/10.26153/tsw/6874. [PDF](http://dx.doi.org/10.26153/tsw/6874)

*Bihani A.*, Daigle H. (2019). Investigating Sealing Capacity and Percolation in Mudrocks through Grain Scale Modeling. Presented at the Spring 2019 Virtual Poster Showcase, American Geophysical Union, Washington, DC.

*Bihani A.*, Daigle H. (2019). Poster 79: Investigating Capillary Pressure Behavior in Mudrocks through Grain Scale Modeling. Graduate and Industry Networking Conference, 5 February, Austin, TX. [Abstract](https://sites.utexas.edu/gain/2019-abstracts/poster-79/)

*Bihani A.*, Daigle H., Cook A., Glosser D., Shushtarian A. (2015). OS23B-1999: Pore Size Distribution and Methane Equilibrium Conditions at Walker Ridge Block 313, Northern Gulf of Mexico. AGU Fall Meeting, 14-18 December, San Francisco, USA. [Abstract](https://ui.adsabs.harvard.edu/abs/2015AGUFMOS23B1999B/abstract)

*Bihani A.*, Haindade Z., Jain D. (2012). A study on Electrolysis assisted Gas-Lift for Dewatering CBM Reservoirs. Association of Petroleum Geologists Conference, 30 September, Duliajan, Assam, India. 

### E) Published Datasets 

*Bihani, A.*, & Daigle, H. (2019, March 5). Bidisperse sphere packs generated under gravity. Digital Rocks Portal. http://doi.org/10.17612/P74T20. [Data set](http://doi.org/10.17612/P74T20)

*Bihani, A.*, Daigle, H., Prodanovic, M., Milliken, K., Landry, C., & E. Santos, J. (2020, January 20). Mudrock images from Nankai Trough. Digital Rocks Portal. https://doi.org/10.17612/BVXS-BC79. [Data set](https://doi.org/10.17612/BVXS-BC79) 

### F) Published Code Repositories

*Bihani, A.*, & Daigle, H. (2020, September 9). Uniaxial Compaction and Force-chain Analysis of Bidisperse Grain Packs. Zenodo. http://doi.org/10.5281/zenodo.4021433. [Code](http://doi.org/10.5281/zenodo.4021433)

Santos J. E., *Bihani, A.*, & Landry, C. J. (2020, May 25). MP-LBM-UT: Multiphase LBM Toolbox for permeable media analysis. Zenodo. http://doi.org/10.5281/zenodo.3842280. [Code](http://doi.org/10.5281/zenodo.3842280)


---

## Professional Development

---

**Awards**

Department of Petroleum and Geosystems Engineering Research Award,  			     GAIN Conference Austin, 2019 <br/>
<i> Award for best research poster among 20+ candidates </i>

Advanced Communicator Bronze / Competent Leader,  					                   Toastmasters International, 2011 <br/>
<i> Awards for completing 20 public speaking assignments and holding 10+ roles in Toastmasters meetings  </i>

Ravindra Kulkarni Silver Medal,                                               Maharashtra Institute of Technology, 2011 <br/>
<i> Award for 2nd highest grade in graduating class of 70+ students  </i>

**Grants and Fellowships**

Statoil/Equinor Fellowship, 									                                 UT Austin, 2016 – 2019 <br/>
<i> Doctoral Fellowship for 3 years of $58,000 per year for studying flow in porous media through numerical simulations  </i>  

Research Fellowship, U.S. Department of Energy,						                   UT Austin, 2014 – 2016 <br/>
<i> Masters Fellowship for 2 years of $55,000 per year for studying deposition and flow of methane hydrates in the Gulf of Mexico  </i>  

**Service**

Graduate Faculty Selection Committee, 								                         UT Austin, 2017 – 2019 <br/>
<i> Interviewed potential new department faculty, met external department reviewers, and conducted outreach activities  </i>  

Young Professionals Committee - Society of Petroleum Engineers,               Duliajan Section, 2012 - 2014 <br/>
<i> Organized quarterly Distinguished Lecture Programs, conducted outreach activities to raise awareness about energy production and conservation </i>  

Presiding Officer – Dibrugarh Constituency, Indian Parliamentary Election,  	 Election Commission of India, 2014 <br/>
<i> Supervised team of six allowing 749 people to vote in the Indian Parliamentary election of 2014  </i>  

Vice President, Public Relations,  					                                 Toastmasters Club of Pune – West, 2010 – 2011 <br/>
<i> Promoted Toastmasters to the general public and conducted PR activities to increase membership strength by maintaining club website, editing club magazine, and interviewing with local news media </i>   

President, 	                                                                 Society of Petroleum Engineers Student Chapter, 2010 – 2011 <br/>
<i> Organized national-level conference by raising 6000 USD and received the Gold Standard award for exceptional work  </i>  

Editor, 	Society of Petroleum Engineers Student Chapter, 2009 – 2010 <br/>
<i> Enabled design and publication of annual departmental magazine by assembling competent team, delegating work, filtering and editing of submitted articles while meeting editorial deadlines </i> 

Webmaster, 	Toastmasters Club of Pune,  2009 – 2011 <br/>
<i> Maintained and updated club website, posted new articles and sent out periodic invitations for the weekly meeting  </i> 


**Memberships in Professional Societies**

Member, American Geophysical Union (AGU)

Member, International Society for Porous Media (Interpore)

Member, Society of Petroleum Engineers (SPE) 

Member, Society of Petrophysicists and Well Log Analysts (SPWLA)

Member, The Computer Vision Foundation (CVF)

Member, Toronto Machine Learning Society	 (TMLS)	


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

<p> <a href="pdf/Abhishek%20-%20resume%202020%20-%202pgs.pdf" target="_blank"> Here </a> is a copy of my resume. </p>

---

