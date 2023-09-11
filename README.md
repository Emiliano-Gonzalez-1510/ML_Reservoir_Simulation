# Assisted Reservoir Simulation using AI - Proxy Model MIMO (Multiple Input - Multiple Output)

# Objective
The objective of this project is to develop a MIMO (Multiple Input, Multiple Output) proxy model using Artificial Intelligence methods (XGBoost, Random Forest, Gradient Boosting), aiming to emulate the behavior of a reservoir simulation model applied to a synthetic oilfield.

# Dataset Description
The provided "DataSimulation.csv" dataset consists of 312 simulations conducted using a conventional Black Oil reservoir simulator for the purpose of history matching a synthetic oilfield. Here is included the description of the variables:

<b>Input Variables:</b>

$AQ_Index: Aquifer Productivity Index (bpd/psi)

$ROCK_COMP: Rock Compressibility (1/psi)

$POVOMULT: Porous Volume Multiplier (adim)

$PERM_1: Permeability Multiplier Rock 1

$PERM_2: Permeability Multiplier Rock 2

$KRWMAX: Water Relative Permeability Corey endpoint (adim).

<b>Output Variables:</b>

$PWS1: Static Pressure Control Point 1 (psi)

$PWS2: RStatic Pressure Control Point 2 (psi)

$P2S3: Static Pressure Control Point 3 (psi)

$PWS4: Static Pressure Control Point 4 (psi)

$PWS5: Static Pressure Control Point 5 (psi)

$OIL_CUM: Cummulative Oil Production (bbl)

$WATER_CUM: Cummulative Water Production (bbl)

$WC1: Water Cut Control Point 1 (frac)

$WC2: Water Cut Control Point 2 (frac)

$PWFEND: Bottom Hole Pressure end (psi)

# Jupyter Notebook
To be able to see the Code in Jupyter Notebook please click on the file "Machine Learning - Reservoir Simulation History Match Optimization.ipynb"
