# Effect of the Addition of Silicon Carbide Particles on the Mechanical Properties of a Glass Fiber Reinforced Bio-Epoxy: Experimental Analysis and Machine Learning Modeling

Bio-epoxy resins have become alternatives to traditional petroleum-derived matrices for glass fiber reinforced polymers (GFRPs) fabrication due to their environmental advantages. However, the number of studies characterizing bio-based GFRPs remains scarce compared to their petroleum-based counterparts. This study evaluates glass fiber reinforced bio-epoxy (GFRBE) composites including different silicon carbide (SiC) loadings manufactured via a vacuum-assisted hand lay-up process, and develops machine learning (ML) models to predict the composites’ mechanical performance as a function of the reinforcement contents. The unreinforced GFRBE achieved a tensile strength and modulus of 211 MPa and 12.6 GPa, and a flexural strength and modulus of 373 MPa and 14.6 GPa. The composites reached their peak tensile performance at 1.0 wt. % SiC, with 23% and 19% improvements in tensile strength and modulus, respectively. The flexural performance improved across all SiC loadings, reaching an improvement of 17% and 46% at 2.0 wt. % SiC content. Scanning electron microscopy (SEM) revealed improved fiber-matrix interfaces after adding lower SiC loadings. ML models achieved an R2 up to 0.78 and 0.98 for tensile and flexural strength predictions, demonstrating the importance of ML tools in reducing the experimental work for composite optimization.

# Models
The following models are implemented and included in this repository:

K-Nearest Neighbors (KNN): hyperparameters for KNN: {'n_neighbors=7'}

RandomForestRegressor (RFR): hyperparameters for RandomForestRegressor: {'max_depth': 30, 'min_samples_leaf': 2, 'min_samples_split': 2, 'n_estimators': 2000}

Gaussian process regressor (GPR): hyperparameters for KNN: {kernel=kernel, n_restarts_optimizer=20, alpha=0.001, normalize_y=True}, kernel = C(1.0, (1e-2, 1e2)) * RBF(10, (1e-2, 1e2))

# Usage
All files can be opened and edited using Jupyter or similar editing software. The code can then be run directly. Note that you will need to manually install any packages not already installed during the import step.
