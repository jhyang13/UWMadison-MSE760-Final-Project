# UWMadison-MSE760-Final-Project

## MS&E760: Molecular Modeling of Materials (001) FA24

### Student

Name: Jiahui Yang, Mechanical Engineering

Email: jyang753@wisc.edu

### Overview
This project investigates the mechanical properties of polymers by linking atom-level structural features to macroscopic behavior using machine learning (ML) and molecular dynamics (MD) simulations. The focus is on the Young's modulus of Poly(imino-1,3-phenyleneiminobut-2-ene-1,4-dioyl), leveraging data-driven models and atom-level explanations.

### Key Features
- Machine Learning: Predicts polymer properties using single-task and multitask ML models with Morgan fingerprints and SHAP (Shapley Additive Explanations) values for interpretability.
- Molecular Dynamics Simulations: Validates ML predictions with stress-strain data and detailed substructure analysis.
- Atom-Level Explanations: Highlights contributions of individual atoms and substructures to mechanical properties.
- Data Source: Utilizes the PoLyInfo database containing over 18,000 polymers and their properties.

### Workflow
- Data Preparation: SMILES representations and Morgan fingerprints.
- ML Model Training: Single-task and multitask feedforward neural networks.
- MD Simulations: Built using LAMMPS and validated with stress-strain curves.
- Explanatory Analysis: SHAP values for interpretability and refinement of structure-property relationships.

### Results
-ML predictions achieve high accuracy with an error margin of 8% compared to MD simulations.
-Atom-level contributions are identified, providing insights into polymer design.
- Integration of ML and MD demonstrates robust predictive capabilities for advanced materials.

### Future Work
- Expand ML models to include additional polymer properties.
- Incorporate topological features like cross-linking and branching.
- Explore generative models and uncertainty quantification for better reliability.

### Repository
Access the full project, including code and data, at GitHub Repository.







