# model-copram
Code for phase retrieval of signals with underlying structured sparsity level s.

Refer the paper for further details on implementation: https://arxiv.org/abs/1705.06412

phase_retrieval_sparse.m 

Runs and analyzes performances of the following sparse phase retrieval algorithms:
1. CoPRAM
2. AltMinSparse 
3. Thresholded Wirtinger Flow for sparse phase retrieval (ThWF)
4. Sparse Phase Retrieval using Truncated Amplitude Flow (SparTA)

phase_retrieval_block.m

Phase retrieval of block-sparse signals of uniform block length b and overall sparsity s. 
Runs and analyzes performance of Block CoPRAM algorithm w.r.t CoPRAM for block sparse signals.

