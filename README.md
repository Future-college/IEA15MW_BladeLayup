# IEA 15Mw FOWT model with balde layup
(1) The refernce FOWT model: The IEA 15 Mw reference wind turbine with the UMaine VolturnUS-S semisubmersible floating platform is used as the reference FOWT model.
(2) The initial layup: The blade NUMAD model developed by the UTD is used as the reference model for blade layup, which is converted to the Precom input data with 50 cross sections for calculating mass and stiffness matrices.
(3) The adjusted layup: The initial layup model is adjusted so the generated mass and stiffness distributions along the blade span could match with the BeamDyn model in the reference FOWT model better as shown in below figures for the adjusted layup and mass-stiffness distributions.
(4) The original Cross sections 44, 45 are removed so the layup model in this repo contains only 48 cross sections.

The initial and adjusted blade layup:
<img width="697" height="516" alt="image" src="https://github.com/user-attachments/assets/957f16a1-983d-4843-848e-169850436d16" />

The corresponding mass and stiffness comparisons between the initial and adjusted blade layup:
<img width="886" height="993" alt="image" src="https://github.com/user-attachments/assets/5732aa51-3e11-4303-957f-801360fe129c" />
