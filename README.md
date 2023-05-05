# Tobacco and alcohol use behaviors impact genetically influenced erythroid trait variation

Shriya Shivakumar1,2, Madison B Wilken1, Victor Tsao1,3, Christopher S Thom1,*

1Division of Neonatology, Children’s Hospital of Philadelphia, Philadelphia, PA
2Bryn Mawr College, Bryn Mawr, PA
3University of Pennsylvania, Philadelphia, PA

*Correspondence: 
Christopher S Thom, MD, PhD
Children’s Hospital of Philadelphia
Colket Translational Research Bldg, Room 10-052
3501 Civic Center Blvd
Philadelphia, PA 19104
thomc@chop.edu

Genome wide association studies (GWAS) have associated thousands of loci with quantitative human blood trait variation. Blood trait loci and related genes may regulate blood cell-intrinsic biological processes, or alternatively impact blood cell development and function via systemic factors and disease processes. Clinical observations linking behaviors like tobacco or alcohol use with altered blood traits can be subject to bias, and these trait relationships have not been systematically explored at the genetic level. Using a Mendelian randomization (MR) framework, we confirmed causal effects of smoking and drinking that were largely confined to the erythroid lineage. Using multivariable MR and causal mediation analyses, we confirmed that an increased genetic predisposition to smoke tobacco was associated with increased alcohol intake, indirectly decreasing red blood cell count and related erythroid traits. These findings demonstrate a novel role for genetically influenced behaviors in determining human blood traits, revealing opportunities to dissect related pathways and mechanisms that influence hematopoiesis. 

#This branch contains instrumental variables (IVs) used in this study.

They are formatted for direct input into the TwoSampleMR or MVMR packages

Each folder is named for the type of analysis (MR or MVMR), Exposure, Outcome
e.g., MR.SmkInit.Blood contains IVs for TwoSample analysis using SmkInit as the Exposure and Blood traits as the outcome.
Each IV within that folder specifies the blood trait outcome
e.g., MR.SmkInit.HGB.IV.txt is the IV for TwSample analysis of SmkInit Exposure on HGB outcome.
