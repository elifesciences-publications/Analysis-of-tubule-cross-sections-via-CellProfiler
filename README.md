# nalysis-of-tubule-cross-sections-via-CellProfiler
These scripts were used to quantify spermatogonial and Sertoli cell populations in cross-sections of seminiferous tubules from wildtype and mutant samples. 

Tubule_outlines_190110.cppipe creates an image with ROIs (tubule cross-sections) marked as objects. It takes as input a png file with ROIs 			outlined in red (1px width) and background region marked in blue (1px width).

Testes_Sox9_ckit_tubules.cppipe quantifies KIT+ germ cells and SOX9+ Sertoli cells in tubule cross-sections. As input, it takes one file 		 each for DNA (DAPI), DAZL, KIT, and SOX9 immunofluorescent staining. It also requires as input the output from 						Tubule_outlines_190110.cppipe marking the ROIs. Only KIT staining on cellular membrane is quantified; (nonspecific) nuclear KIT 		staining is excluded. 

Testes_Sox9_Foxc2_tubules.cppipe quantifies FOXC2+ germ cells and SOX9+ Sertoli cells in tubule cross-sections. As input, it takes one 			file each for DNA (DAPI), DAZL, FOXC2, and SOX9 immunofluorescent staining. It also requires as input the output from 					Tubule_outlines_190110.cppipe marking the ROIs.

Testes_Sox9_Plzf_tubules.cppipe quantifies PLZF+ germ cells and SOX9+ Sertoli cells in tubule cross-sections. As input, it takes one file 		  each for DNA (DAPI), DAZL, PLZF, and SOX9 immunofluorescent staining. It also requires as input the output from 							Tubule_outlines_190110.cppipe marking the ROIs.
