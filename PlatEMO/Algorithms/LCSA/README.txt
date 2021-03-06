
 Copyright (C) 2020 Heiner Zille

 This work is licensed under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 
 International License. (CC BY-NC-SA 4.0). To view a copy of this license, 
 visit http://creativecommons.org/licenses/by-nc-sa/4.0/ or see the 
 pdf-file "License-CC-BY-NC-SA-4.0.pdf" that came with this code. 

 You are free to: 
 * Share ? copy and redistribute the material in any medium or format
 * Adapt ? remix, transform, and build upon the material 
 Under the following terms:
 * Attribution ? You must give appropriate credit, provide a link to the 
    license, and indicate if changes were made. You may do so in any reasonable 
    manner, but not in any way that suggests the licensor endorses you or your use.
 * NonCommercial ? You may not use the material for commercial purposes.
 * ShareAlike ? If you remix, transform, or build upon the material, you must 
   distribute your contributions under the same license as the original.
 * No additional restrictions ? You may not apply legal terms or technological 
   measures that legally restrict others from doing anything the license permits.

 Author of this Code: 
  Heiner Zille <heiner.zille@ovgu.de> or <heiner.zille@gmail.com>

 This code is based on the following publications:

 1) Heiner Zille 
    "Large-scale Multi-objective Optimisation: New Approaches and a Classification of the State-of-the-Art"  
    PhD Thesis, Otto von Guericke University Magdeburg, 2019 
    http://dx.doi.org/10.25673/32063 

 2) Heiner Zille and Sanaz Mostaghim
    "Linear Search Mechanism for Multi- and Many-Objective Optimisation"
    10th International Conference on Evolutionary Multi-Criterion Optimization (EMO 2019), 
       Lecture Notes in Computer Science, vol 11411. 
       Deb K. et al. (eds), Springer, Cham, East Lansing, Michigan, USA, March 2019  
    https://doi.org/10.1007/978-3-030-12598-1_32.

 This file is intended to work with the PlatEMO framework version 2.5. 
 Date of publication of this code: 06.04.2020 
 Last Update of this code: 06.04.2020 
 A newer version of this algorithm may be available. Please contact the author 
 or see http://www.ci.ovgu.de/Research/Codes.html. 
  
 To use this program, simply copy the complete "LCSA"-folder and its contained files 
 into the "Algorithms"-folder of the PlatEMO framework. LCSA should then be usable as any other 
 algorithm inside the framework. 
  
  File list:       
  	- LCSA/README.txt
	- LCSA/License-CC-BY-NC-SA-4.0.pdf
	
	- LCSA/LCSA.m
	- LCSA/LCSA_getNumberOfGenerationsForNormalOptimisation.m
	- LCSA/LCSA_getNumberOfGenerationsForCoefficientOptimisation.m
	- LCSA/LCSA_GA.m
	
	- LCSA/LCSA_smpso/LCSA_SMPSOUpdatePbest.m
	- LCSA/LCSA_smpso/LCSA_SMPSOOperator.m
	- LCSA/LCSA_smpso/LCSA_SMPSOUpdateGbest.m
	- LCSA/LCSA_smpso/LCSA_SMPSO.m
	- LCSA/LCSA_smpso/LCSA_CoefficientSMPSOOperator.m

	- LCSA/LCSA_nsga3/LCSA_NSGAIIIEnvironmentalSelection.m
	- LCSA/LCSA_nsga3/LCSA_NSGAIII.m
	
	- LCSA/LCSA_nsga2/LCSA_NSGAIIEnvironmentalSelection.m
	- LCSA/LCSA_nsga2/LCSA_NSGAIICrowdingDistance.m
	- LCSA/LCSA_nsga2/LCSA_NSGAII.m


  
  
  
  
  
  
