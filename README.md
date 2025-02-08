# Q-CAD

Goal: To establish the computational infrastructure and algorithms which can put theory-in-the-loop for experimental automation of synthesis, manipulation and characterization, accelerating autonomous discovery of new materials and chemical processes.

Specific sub-projects currently being worked upon :

1. Develop cross-platform workflows on HPC environments to create Digital Twins for material discovery, synthesis, manipulation and characterization using multi-scale simulation methodogies (for now focusing on, ab initio methods at varying fidelity, atomiistic force-fields, phase-field simulation approaches);
2. Develop AI/ML based Generative Models trained on Digital Twins to interpret experiments in real-time as well as predict new materials and/or synthesis pathways;
3. Develop an Active Learning framework that can incorpoorate uncertainties from model-predictions to spawn new Digital Twin simulations and/or experiments;
4. Establish data pipelines and storage to co-locate and co-analysze synthesis and characterization experiments as well as Digital Twins;
Deploy ML-models trained on Digital Twins on the edge to control experimental syntheis/manipulation/characterization/ in real-time;

Key Repositories:

Spec2Ham -- Solves the inverse problem of constructing a Hamiltonian from a 1D spectra, such as a Scanning Tunneling Spectroscopy (STS) measuerment, using a Bayesian Optimisation method.
MatEnsemble -- Asynchronous HPC workflow to orchestrate job submissions with in-GPU-memory on-the-fly analysis.
Spec2Struct -- Solves the inverse problem of generating atomic structures conditioned upon a given 1D spectra, such as a Scanning Tunneling Spectroscopy (STS) measurement, using a Generative Dissuion model.
HeteroBuilder -- python tools to construct quantum heterostructures.

Active Lead Developers in this Project:

Soumendu Bagchi
Ayana Ghosh
Addis Fuhr
P. Ganesh

Students/Postdocs contributing to this Project:

Ryan Morelock
Ankita Biswas
Shuyi Jia
Ankush Mishra

External collaborators and advisors for this Project:

Victor Fung
Prasanna Balachandran
