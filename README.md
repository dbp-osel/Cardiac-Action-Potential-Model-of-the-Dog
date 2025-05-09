# Cardiac-Action-Potential-Model-of-the-Dog

This software code provides a model of canine cardiac action potential described in [1,2]. The model code is written in CellML which is an open standard based on the XML markup language [3]. The model was derived from voltage clamp experimental data from canine ventricular myocytes/tissue under nearly identical and physiological conditions. This model of the canine action potential is moderately complex with six currents, seven variables, and thirty-six parameters. The model was calibrated to both action potential duration restitution and conduction speed. The design of the model allows for comprehensive parameter sensitivity analysis and uncertainty quantification.For more information about the model please refer to [1,2]. There are a variety of OpenSource Tools to run this CellML model (see [3]).

The code itself is provided in the two files:

PathmanathanGrayCanine2019.cellml & PathmanathanGrayCanine2020mean.cellml

These two models have the same form but have slightly different paramter values. The paramter values of PathmanathanGrayCanine2019.cellml are listed in Table 1 of [1] and the paramter values of PathmanathanGrayCanine2020mean.cellml are listed in Table 1 of [2].

# Regulatory Science Tool (RST) Reference
•	RST Reference Number: RST24CV12.01  
•	Date of Publication: 08/08/2023  
•	Recommended Citation: U.S. Food and Drug Administration. (2023). Cardiac Action Potential Model of the Dog (RST24CV12.01). https://cdrh-rst.fda.gov/cardiac-action-potential-model-dog  


# Disclaimer
About the Catalog of Regulatory Science Tools  
The enclosed tool is part of the Catalog of Regulatory Science Tools, which provides a peer- reviewed resource for stakeholders to use where standards and qualified Medical Device Development Tools (MDDTs) do not yet exist. These tools do not replace FDA-recognized standards or MDDTs. This catalog collates a variety of regulatory science tools that the FDA's Center for Devices and Radiological Health's (CDRH) Office of Science and Engineering Labs (OSEL) developed. These tools use the most innovative science to support medical device development and patient access to safe and effective medical devices. If you are considering using a tool from this catalog in your marketing submissions, note that these tools have not been qualified as Medical Device Development Tools and the FDA has not evaluated the suitability of these tools within any specific context of use. You may request feedback or meetings for medical device submissions as part of the Q-Submission Program.  

For more information about the Catalog of Regulatory Science Tools, email OSEL_CDRH@fda.hhs.gov.


This software and documentation (the "Software") were developed at the Food and Drug Administration (FDA) by employees of the Federal Government in the course of their official duties. Pursuant to Title 17, Section 105 of the United States Code, this work is not subject to copyright protection and is in the public domain. Permission is hereby granted, free of charge, to any person obtaining a copy of the Software, to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, or sell copies of the Software or derivatives, and to permit persons to whom the Software is furnished to do so. FDA assumes no responsibility whatsoever for use by other parties of the Software, its source code, documentation or compiled executables, and makes no guarantees, expressed or implied, about its quality, reliability, or any other characteristic. Further, use of this code in no way implies endorsement by the FDA or confers any advantage in regulatory decisions. Although this software can be redistributed and/or modified freely, we ask that any derivative works bear some notice that they are derived from it, and any modified versions bear some notice that they have been modified.

References

[1] Pathmanathan P, Cordeiro JM, Gray RA. Comprehensive uncertainty quantification and sensitivity analysis for cardiac action potential models. Frontiers in Physiology, Frontiers in Physiology, 2019: doi.org/10.3389/fphys.2019.00721. https://pubmed.ncbi.nlm.nih.gov/31297060/

[2] Pathmanathan P, Galappaththige S, Cordeiro JM, Kaboudian A, Fenton FH, Gray RA. Data-driven uncertainty quantification for cardiac electrophysiological models: impact of physiological variability on action potential and spiral wave dynamics. Frontiers in Physiology, Frontiers in Physiology, 2020, doi.org /10.3389/fphys.2020.585400. https://pubmed.ncbi.nlm.nih.gov/33329034/

[3] CellML.Org
