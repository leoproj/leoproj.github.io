Learning to Tune Compiler Optimizations for Symbolic Execution Acceleration
---
*Under Construction*  

###<h2 id="1"> Data </h2>

The experimental results can be downloaded from the following link.   
[Download](./file/leo.results.zip)   


ReadMe(This is from another project): 

After downloading, there are two folders in the package: gcc and llvm   
   
For gcc:   
   
	This folder saves the results of GCC:   
		gcc-rdt.txt: save test programs (id) that trigger GCC bugs by RDT   
		gcc-emi.txt: save test programs (id) that trigger GCC bugs by EMI   
		gcc-dol.txt: save test programs (id) that trigger GCC bugs by DOL   
		gcc-correcting-commits.csv: the correcting commit for each test program   
			test program (id), the correcting commit (id)   
   
   
For llvm:   

	This folder saves the results of LLVM:   
		llvm-rdt.txt: save test programs (id) that trigger LLVM bugs by RDT   
		llvm-emi.txt: save test programs (id) that trigger LLVM bugs by EMI   
		llvm-dol.txt: save test programs (id) that trigger LLVM bugs by DOL   
		llvm-correcting-commits.csv: the correcting commit for each test program   
			test program (id), the correcting commit (id)   	