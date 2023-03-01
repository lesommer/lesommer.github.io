---
layout: post
title: "Research engineer position : Hybrid physics-based / AI-based ocean modeling"
date: 2023-02-15
---



Our research group is advertizing for a research engeneer position to work for CNRS at [Institute of Geosciences and Environment](https://www.ige-grenoble.fr/?lang=en), Grenoble, France. 

### Mission
The general mission is to develop coupling strategies for interfacing ocean circulation models with AI-based trainable components. The selected candidate will contribute to the MEDIATION project and to the M2LINES project.

### Working context
The selected candidate will work at the Institute for Environmental Geosciences (IGE), in Grenoble, in the French Alps. This is a public research institute under the affiliation of CNRS, IRD, Univ. Grenoble Alpes, Grenoble-INP and INRAE. It brings together about 250 people, including 150 permanent members (researchers, teacher-researchers, engineers) and about a hundred contractual agents (doctoral students, postdocs, engineers and technicians). The institute also welcomes several dozen trainees and scientific visitors every year. It is spread over three sites of the Grenoble University Campus that are 5 minutes away from each other. IGE is one of the main institutes within the Observatoire des Sciences de l’Univers de Grenoble (OSUG) which is a federative structure of INSU.
The selected candidate will join the MEOM team, which has a focus on ocean/sea ice modeling and forecast  (see  https://meom-group.github.io). The activities will be supervised by Julien Le Sommer and Aurélie Albert. This work will involve strong interactions with the participants of the M2LINES (https://m2lines.github.io) and the MEDIATION projects. Key collaborators will include Bruno Raffin (INRIA, Data Move team, https://www.inria.fr/fr/datamove) and the developers of the NEMO and CROCO ocean models.

### Scientific context
The combination of machine learning with scientific computing is an active area of research which is expected to improve geoscientific models and their integration into broader numerical systems, such as climate models and operational forecasting systems. Machine learning could for instance be used for improving the representation of unresolved processes in climate models, for accelerating the execution of specific code components or for quantifying or reducing model errors. Most practical applications of machine learning to geoscientific models so far are based pre-trained machine learning models designed through supervised learning tasks formulated from high-resolution datasets.
A key practical question for geoscientific models is to define how machine learning components can be encoded and maintained into pre-existing legacy codes, written in low level abstraction languages (as FORTRAN). Several practical options exist, each coming with pros and cons. Neural networks may for instance directly be implemented in FORTRAN, one could alternatively use the C/C++-bindings of specific machine learning libraries or more generic high level coupling interfaces. But the trade-offs between these different strategies are usually model and use-case specific. 

The NEMO ocean / sea-ice model (https://www.nemo-ocean.eu) and the CROCO ocean model (https://www.croco-ocean.org) are two important tools for the oceanographic community, in particular in the context of operational forecasting systems and european Earth System Models. Their development roadmaps involve the definition of sustainable interfaces for trainable components to be leveraged on-line during model simulations. A working group dedicated to machine learning related developments has been set-up as part of the NEMO development team.  

### Activities
The selected candidate will be in charge of providing quantitative information and developing practical solutions for a sustainable implementation of trainable components into the NEMO and the CROCO ocean models. This will involve defining benchmark use-cases of machine learning based components in ocean models. These will be based for instance on subgrid parameterizations already developed as part of the M2LINES project. The selected candidate will define quantitative metrics for intercomparing the different available options for coupling AI-based trainable components and legacy ocean models, and implement several options into the NEMO and CROCO ocean models. Possible options may include Infero (https://github.com/ecmwf-projects/infero), ICCS Fortran ML Bridge (https://github.com/Cambridge-ICCS/fortran-ml-bridge), HPE SmartSim  (https://github.com/CrayLabs/SmartSim), Melissa (https://gitlab.inria.fr/melissa) or OASIS (https://oasis.cerfacs.fr/en/). The work will then involve performing systematic intercomparison based on realistic model simulations to be performed on HPC resources. The selected candidate will then write reports on the results and present the outcome of the work to relevant working group and project meetings. He/She will participate also in the discussions and meetings of the M2LINES and MEDIATION projects.

### Requirements and selection criteria
The selected candidate will hold a MSc in computer science, engineer or PhD. The selection will be based on the following scientific and technical criteria:
demonstrated experience in High Performance Computing; 
demonstrated experience in Fortran/C/C++ and Python coding;
demonstrated experience in (at least) one of the prominent machine learning frameworks (PyTorch, TensorFlow,… );
basic understanding of Computational Fluid Dynamics and subgrid closures for fluid flows;
experience in running atmospheric, ocean circulation or climate models (not compulsory);
demonstrated ability to work within a team.
The selection panel will also consider the gender balance of the entire research team. Junior candidates with a fresh title are also welcome. This position may help you build a curriculum in the very active domain of hybridization between Numerical Simulation and Deep Learning (ML4Sci)

## Job information

Employer: CNRS.
Type of contract: fixed-term.
CNRS category: BAP E
Job Type: Expert in scientific computing (E1E45).
Duration of contract: 18 months.
Expected date of hire: between April 1st and July 1st, 2023
Work quota: Full time.
Required level of studies: Completed PhD or Engineering School.
Required experience: No experience required.
Gross salary: from 2580€/month to 2970€/month (depending on experience).
Paid leave: approximately 45 days per year.
Health care: France runs a statutory health insurance system providing universal coverage for its residents (Sécurité Sociale). Most residents additionally pay for a complementary private health insurance for expenses not covered by the statutory health insurance (Mutuelle).

## If you are interested:

contact us: 
Julien.lesommer@univ-grenoble-alpes.fr and aurelie.albert@univ-grenoble-alpes.fr

apply on the [CNRS website](https://emploi.cnrs.fr/Offres/CDD/UMR5001-ALEVIA-008/Default.aspx) before April 15th

To apply please submit your CV, as well as a list of people who could be potential references. You may also include recent marks and your last Intership/Master/PhD Thesis manuscript if relevant. With your application, please provide any element (github account, code snippets, etc.) that could help us assess your skills beyond your academic record, 










