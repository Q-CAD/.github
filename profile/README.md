# QCAD

Goal: To establish the computational infrastructure and  algorithms which can put theory-in-the-loop for experimental automation of synthesis, manipulation and characterization, accelerating autonomous discovery of new materials, physics and chemical processes. 

Specific sub-projects currently being worked upon : 
  1. Develop cross-platform workflows on HPC environments to create Digital Twins for material discovery, synthesis, manipulation and characterization using multi-scale simulation methodogies (for now focusing on, ab initio methods at varying fidelity, atomiistic force-fields, phase-field simulation approaches);
  3. Develop AI/ML based Generative Models trained on Digital Twins to interpret experiments in real-time as well as predict new materials and/or synthesis pathways;
  4. Develop an Active Learning framework that can incorpoorate uncertainties from model-predictions to spawn new Digital Twin simulations and/or experiments; 
  5. Establish data pipelines and storage to co-locate and co-analysze synthesis and characterization experiments as well as Digital Twins;
  6. Deploy ML-models trained on Digital Twins on the edge to control experimental syntheis/manipulation/characterization/ in real-time; 

Key Repositories: 

1. Spec2Ham -- Solves the inverse problem of constructing a Hamiltonian from a 1D spectra, such as a Scanning Tunneling Spectroscopy (STS) measuerment, using a Bayesian Optimisation method.  
2. MatEnsemble -- Asynchronous HPC workflow to orchestrate job submissions with in-GPU-memory on-the-fly analysis.
3. Spec2Struct -- Solves the inverse problem of generating atomic structures conditioned upon a given 1D spectra, such as a Scanning Tunneling Spectroscopy (STS) measurement, using a Generative Dissuion model.
4. HeteroBuilder -- python tools to construct quantum heterostructures.
   
Active Lead Developers in this Project: 

1. Soumendu Bagchi
2. Ayana Ghosh
3. Addis Fuhr
5. P. Ganesh

Students/Postdocs contributing to this Project: 

 1. Ryan Morelock
 2. Ankita Biswas
 3. Shuyi Jia
 4. Ankush Mishra

External collaborators and advisors for this Project: 

1. Victor Fung
2. Prasanna Balachandran
