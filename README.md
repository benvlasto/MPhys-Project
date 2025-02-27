# MPhys-Project
This is my MPhys project exploring extensions to the Standard Model of particle physics. The project involves deep learning with data from the LHC.

Results so far: my CLs predicting model can correctly remove 45% of invalid models whilst removing only 1% of valid models. This translates to saving more than a month of processing by the LHC computing cluster out of a year total (for the recent EWKino scan).

# Targets
- [x] Create model that predicts DM relic density better than random sampling of target range
- [x] Reduce MAE to below 25% of mean absolute target error
- [x] Create plot of MAE in bins of true relic density
- [x] Plot upper cutoff of relic density against number of valid but excluded pMSSM models
- [ ] Apply EWKino model to Bino-DM and evaluate performance
- [x] Apply same relic density cutoff technique to CLs
- [x] Characterise those models which my CLs predictor incorrectly rejects
- [ ] Recreate plots from pMSSM paper with predicted CLs