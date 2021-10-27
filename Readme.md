
` nvcc factorization.cu ILU_0_gpu.cu parILU_0_gpu.cu isai_gpu.cu  matrix.cu mmio.cpp  ReadWriteData.cpp SolverResults.cu PrecondBiCGSTAB_general_isai_gpu.cu main_bicgstab_general_isai.cpp -o general_isai `


` nvcc factorization.cu ILU_0_gpu.cu parILU_0_gpu.cu isai_gpu.cu  matrix.cu mmio.cpp  ReadWriteData.cpp SolverResults.cu PrecondBiCGSTAB_ilu_isai_gpu.cu main_bicgstab_ilu_isai.cpp -o ilu_isai `


` nvcc factorization.cu ILU_0_gpu.cu parILU_0_gpu.cu isai_gpu.cu  matrix.cu mmio.cpp  ReadWriteData.cpp SolverResults.cu PrecondBiCGSTAB_ilu_gpu.cu main_bicgstab_ilu.cpp -o ilu   `





