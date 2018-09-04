# 3x3_SVD_CUDA
Fast CUDA 3x3 SVD 

This is the part of code of 

Ming Gao*, Xinlei Wang*, Kui Wu* (joint first authors), Andre Pradhana, Eftychios Sifakis, Cem Yuksel, Chenfanfu Jiang<br/>
**GPU Optimization of Material Point Methods**<br/>
ACM Transactions on Graphics (SIGGRAPH ASIA 2018), to appear.<br/>

It will produce the same result as “[Computing the Singular Value Decomposition of 3x3 matrices with minimal branching and elementary floating point operations](http://pages.cs.wisc.edu/~sifakis/project_pages/svd.html)" does. 

## How to use 

Though we only provide Visual Studio 2015 *.sln, the code doesn't depend on any external library. 

Uncomment to VERIFY_RESULTS to verify the resule with CPU version.
Uncomment/comment to use Structure of Arrays or Array of structures for matrix attributes.

The actual CUDA SVD code can be found in [svd3_cuda.h](https://github.com/kuiwuchn/3x3_SVD_CUDA/blob/master/svd3x3/svd3x3/svd3_cuda.h).

## BibTex 

Please cite the following paper if it helps. 

```
@article{Gao:2018:GPU_MPM,
 author       = {Ming Gao* and Xinlei Wang* and Kui Wu* and Andre Pradhana and Eftychios Sifakis and Cem Yuksel and Chenfanfu Jiang},
 title        = {GPU Optimization of Material Point Methods},
 journal      = {ACM Transactions on Graphics (Proceedings of SIGGRAPH Asia 2018)},
 year         = {2018},
 publisher    = {ACM Press},
 address      = {New York, NY, USA},
 note         = {(*Joint First Authors), to appear},
}  
```
