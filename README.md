# MPhys-Project
This is my MPhys project exploring extensions to the Standard Model of particle physics. The project involves deep learning with data from the LHC.

Results so far: the neural network (NN) trained for the EWKino dataset can categorise 45% of models as excluded or not excluded whilst incorrectly categorising fewer than 1% of models. The NN trained for the Bino dataset can categorise 29% of models whilst staying below 1% error. Together, this corresponds to saving over 150,000 hours of compute time on the LHC computing grid (assuming 20 hours per model).

# Targets
- [x] Create model that predicts DM relic density better than random sampling of target range
- [x] Reduce MAE to below 25% of mean absolute target error
- [x] Create plot of MAE in bins of true relic density
- [x] Plot upper cutoff of relic density against number of valid but excluded pMSSM models
- [x] Train model for Bino-DM and evaluate performance
- [x] Apply same relic density cutoff technique to CLs
- [x] Characterise those models which my CLs predictor incorrectly rejects
- [x] Recreate plots from pMSSM paper with predicted CLs
