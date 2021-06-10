#here I build a basic project frame which will coupling pyTorch with Openfoam used for FGM model

#the file structure is as follows,

#(PROJECT)/
                 |_software/ 
	         |_ pyTorch/libtorch/
	 |_run/
	         |_0/T                 # identify the boundary condition	
 	 |_solver/
                         |_appName.C    # the code of the sovler/ function from pyTorch? 
                         |_createFields.H # head file needed
                         |_Make/   
		|_files          # give the location of the output file
                                |_options    # give the location of the needed head file and library
	 |_src/	                  # the basic libray used will be put under this directory
 	         

#after construct network (using *.py files) on pytorch:
#add header file to all head files of openfoam;
#load the netwrok by:    torch::jit::sccipt::Module torchModel_=torch::jit::load(network.pt);

#reference: https://zhuanlan.zhihu.com/p/32479795
                   https://mp.weixin.qq.com/s/0xFIaBRgTfESYpHndA-kNw
	   https://blog.csdn.net/jiongnima/article/details/103324839(pytorch)


