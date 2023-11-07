# RCTVW：Representative Coefficient Total Variation for Efficient Infrared Small Target Detection
**Matlab implementation of "*Representative Coefficient Total Variation for Efficient Infrared Small Target Detection*", 
## *Highlights:*
#### 1. * (a) Based on the theorem that representative coefficient matrix can inherit the spatial structure of data matrix, we impose TV constraint representative coefficient matrix to explore local smooth prior, which not only reduces computational complexity but also removes noise in complex scenes.* (b) Different from existing methods which usually design convex rank function or non-convex rank function to describe the low-rank property of background image, we maintain the low-rank property of background image by controlling the number of columns of representative coefficient matrix. This avoids computing SVD and solving complex regularization terms.*
 <p align="center"> <img src="https://raw.github.com/LiuTing20a/NFTDGSTV/master/Figs/flow.png" width="90%"> </p>
 
 #### 2. *To demonstrate the advantages of the NFTDGSTV method, we compare it with other eiught methods on six different real infrared image scenes.*
 <p align="center"> <img src="https://raw.github.com/LiuTing20a/NFTDGSTV/master/Figs/ZST1.png" width="90%"> </p>
 <p align="center"> <img src="https://raw.github.com/LiuTing20a/NFTDGSTV/master/Figs/ZST2.png" width="90%"> </p>
 
## Get Started
Run Demo_RCTVW.

## Details
For details such as parameter setting, please refer to [<a href="[https://ieeexplore.ieee.org/abstract/document/10286118">pdf</a>].



## Citation

```
  @article{liu2023representative,
  title={Representative Coefficient Total Variation for Efficient Infrared Small Target Detection},
  author={Liu, Ting and Yang, Jungang and Li, Boyang and Wang, Yingqian and An, Wei},
  journal={IEEE Transactions on Geoscience and Remote Sensing},
  year={2023},
  publisher={IEEE}
}

```

## Contact
**Any question regarding this work can be addressed to [liuting@nudt.edu.cn](liuting@nudt.edu.cn).**
