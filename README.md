Implementation of data-driven ML methods to model non-linear, dynamical, systems. Algorithms, given in the two papers below have been implemented here:
"Enforcing physical conservation in neural network surrogate models for complex chemical kinetics, Wang et al, Volume 275, 114105, 2025"
"A data-driven reduced-order model for stiff chemical kinetics using dynamics-informed training, Vijayarangan et al, Volume 15, 100325, 2024"
Find all .py files in src/. Find the configurations and inputs required to run .py files in config/.
Data folder is empty, but one can use any dynamical data they want. Please note accordingly, the src/data/sources need to be changed
HydraConfig has been used for config management, while datamodule, training, validation, testing, were done on PyTorch Lightning Framework
