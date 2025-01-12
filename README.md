# reproducible-tensor-completion-state-of-the-art
Collection of popular and reproducible tensor completion works.

Criteria: works must have codes available, and the reproducible results demonstrate state-of-the-art performances.


**This list is maintained by:**

**Xi-Le Zhao, Teng-Yu Ji, Tai-Xiang Jiang, Meng Ding, Yu-Bang Zheng** **[[Email]](https://zhaoxile.github.io/) (UESTC)**


## Excellent Review
* Tensor Decompositions and Applications (SIAM Review 2009), Tamara G. Kolda and Brett W. Bader  
* Tensor Decompositions for Signal Processing Applications: From Two-way to Multiway Component Analysis (IEEE SP 2015), Andrzej Cichocki et al.
* Tensor Decomposition for Signal Processing and Machine Learning (IEEE TSP 2017), Nicholas D. Sidiropoulos et al.
* Sparse Recovery: From Vectors to Tensors (National Science Review 2017), Yao Wang et al.
* Low Rank Tensor Completion for Multiway Visual Data (Signal Processing 2019), Zhen Long et al.
* Tensor Completion Algorithms in Big Data Analytics (TKDD 2019), Qingquan Song et al.

## CANDECOMP/PARAFAC Decomposition
 * BCPF [[Web]](https://qibinzhao.github.io/) [[Code]](https://github.com/qbzhao/BCPF) [[PDF]](https://arxiv.org/abs/1401.6497)
   * Bayesian CP factorization of incomplete tensors with automatic rank determination (PAMI 2015), Qibin Zhao et al.


## Tucker Decomposition
* SNN [[Web]](https://www.cs.rochester.edu/u/jliu/publications.html) [[Code]](http://peterwonka.net/Publications/code/LRTC_Package_Ji.zip) [[PDF]](https://www.cs.rochester.edu/u/jliu/paper/Ji-ICCV09.pdf)
   * Tensor Completion for Estimating Missing Values in Visual Data (PAMI 2012), Ji Liu et al.
* TMac [[Web]](https://www.math.ucla.edu/~wotaoyin/papers/tmac_tensor_recovery.html) [[Code]](https://www.math.ucla.edu/~wotaoyin/papers/tmac_tensor_recovery.html) [[PDF]](https://www.math.ucla.edu/~wotaoyin/papers/tmac_tensor_recovery.html)
 * Parallel matrix factorization for low-rank tensor completion (Inverse Problems and Imaging), Yangyang Xu et al.
* Tensor-tensor algebra for optimal representation and compression of multiway data, Misha E. Kilmer et al.
* KBR [[Web]](http://gr.xjtu.edu.cn/web/dymeng/1;jsessionid=F03A6AE30867A1EE7DE9D577DD4E253D) [[Code]](https://github.com/XieQi2015/KBR-TC-and-RPCA) [[PDF]](https://ieeexplore.ieee.org/iel7/34/4359286/08000407.pdf)
   * Kronecker-Basis-Representation Based Tensor Sparsity and Its Applications to Tensor Recovery (PAMI 2017), Qi Xie et al.

  
## Tensor Singular Value Decomposition(Maintained by Ben-Zheng Li)
* TNN [[Web]](http://www.ece.tufts.edu/~shuchin/) [[Code]](http://www.ece.tufts.edu/~shuchin/tensor_completion_and_rpca.zip) [[PDF]](https://www.zpascal.net/cvpr2014/Zhang_Novel_Methods_for_2014_CVPR_paper.pdf)
   * Novel Methods for Multilinear Data Completion and De-noising Based on Tensor-SVD (IEEE Conference on Computer Vision and Pattern
Recognition 2014), **Zemin Zhang et al.**
* TRPCA [[Web]](https://canyilu.github.io/publications/) [[Code]](https://github.com/canyilu/Tensor-Robust-Principal-Component-Analysis-TRPCA) [[PDF]](https://arxiv.org/abs/1804.03728)
   * Tensor Robust Principal Component Analysis with A New Tensor Nuclear Norm (IEEE Transactions on Pattern Analysis and Machine Intelligence 2018), **Canyi Lu et al.**
* MTPCP [[Web]](http://math.swu.edu.cn/s/math/index2jiaoshoutea14sub1.html)[Code][[PDF]](https://ieeexplore.ieee.org/document/9064895?denied=)
   * Low-Tubal-Rank Plus Sparse Tensor Recovery With Prior Subspace Information (IEEE Transactions on Pattern Analysis and Machine Intelligence 2021), **Jian-Jun Wang et al.**
 * 3DTNN [[Web]](https://zhaoxile.github.io/) [[Code]](https://github.com/zhaoxile/Mixed-Noise-Removal-in-Hyperspectral-Image-via-Low-Fibered-Rank-Regularization) [[PDF]](https://zhaoxile.github.io/paper/2020/Mixed%20Noise%20Removal%20in%20Hyperspectral%20Image%20via%20Low-Fibered-Rank%20Regularization.pdf)
   * Mixed Noise Removal in Hyperspectral Image via Low-Fibered-Rank Regularization (IEEE Transactions on
Geoscience and Remote Sensing 2020), **Yu-Bang Zheng et al.**
* PSTNN [[Web]](https://sites.google.com/view/taixiangjiang/) [[Code]](https://github.com/zhaoxile/Multi-dimensional-imaging-data-recovery-via-minimizing-the-partial-sum-of-tubal-nuclear-norm) [[PDF]](https://zhaoxile.github.io/paper/2019/Multi-dimensional%20imaging%20data%20recovery%20via%20minimizing%20the%20partial%20sum%20of%20tubal%20nuclear%20norm.pdf)
   * Multi-dimensional imaging data recovery via minimizing the partial sum of tubal nuclear norm (Journal of Computational and Applied Mathematics 2020), **Tai-Xiang Jiang et al.** 
* TNN-DCT [[Web]](https://canyilu.github.io/publications/)[[Code]](https://github.com/canyilu/Tensor-robust-PCA-and-tensor-completion-under-linear-transform)[[PDF]](https://canyilu.github.io/publications/2019-CVPR-TNNtrans.pdf)
   * Low-Rank Tensor Completion With a New Tensor Nuclear Norm Induced by Invertible Linear Transforms (IEEE Conference on Computer Vision and Pattern
Recognition 2019), **Canyi Lu et al.**
* TTNN [[Web]](https://dblp.org/pid/68/2077.html)[[Code]](https://github.com/xjzhang008/Transformed-Tensor-SVD)[[PDF]](https://onlinelibrary.wiley.com/doi/10.1002/nla.2299)
   * Robust tensor completion using transformed tensor singular value decomposition (Numerical Linear Algebra with Applications 2020), **Guangjing Song et al.**
* t-SVDM [[Web]](https://mkilme01.pages.tufts.edu/) [Code] [[PDF]](https://www.pnas.org/content/118/28/e2015851118?__cf_chl_jschl_tk__=pmd_q2NSds777roBnmlkyZ._oWUyt3inwbvjxppxHTIgiWk-1632368958-0-gqNtZGzNAeWjcnBszQk9)
   * Tensor-tensor algebra for optimal representation and compression of multiway data (Proceedings of the National Academy of Sciences of the United States of America 2021), **Misha E. Kilmer et al.**
* Framelet [[Web]](https://it.swufe.edu.cn/info/1106/6154.htm)[[Code]](https://github.com/TaiXiangJiang/Framelet-TNN)[[PDF]](https://ieeexplore.ieee.org/document/9115254)
   * Framelet Representation of Tensor Nuclear Norm for Third-Order Tensor Completion (IEEE Transactions on Image Processing 2020), **Tai-Xiang Jiang et al.**
* CT-LRTC [[Web]](https://zhaoxile.github.io/)[Code][[PDF]](https://ieeexplore.ieee.org/abstract/document/9372832)
   * Multi-Dimensional Visual Data Completion via Low-Rank Tensor Representation Under Coupled Transform (IEEE Transactions on Image Processing 2021), **Jian-Li Wang et al.**
* TQN [[Web]](https://canyilu.github.io/publications/)[Code][[PDF]](https://link.springer.com/article/10.1007/s10994-021-05987-8)
   * Tensor Q-rank: new data dependent definition of tensor rank (Machine Learning 2021), **Hao Kong et al.**
* DTNN [[Web]](https://taixiangjiang.github.io/)[Code][[PDF]](https://taixiangjiang.github.io/paper/2021/TNNLS-Dictionary_Learning_With_Low-Rank_Coding_Coefficients_for_Tensor_Completion.pdf)
   * Dictionary Learning With Low-Rank Coding Coefficients for Tensor Completion (IEEE Transactions on Neural Networks and Learning Systems 2021), **Tai-Xiang Jiang et al.**
## Tensor Train Decomposition
* TMac-TT [[Web]](https://sites.google.com/site/jbengua/home) [[Code]](https://sites.google.com/site/jbengua/home/projects/efficient-tensor-completion-for-color-image-and-video-recovery-low-rank-tensor-train/TMacTT_Images.zip?attredirects=0&d=1) [[PDF]](https://www.researchgate.net/publication/303821165_Efficient_Tensor_Completion_for_Color_Image_and_Video_Recovery_Low-Rank_Tensor_Train)
   * Efficient Tensor Completion for Color Image and Video Recovery: Low-Rank Tensor Train (IEEE TIP2017), Johann A. Bengua et al.
* MF-TTTV  [[Web]](https://zhaoxile.github.io/) [[Code]](https://github.com/zhaoxile) [[PDF]](https://zhaoxile.github.io/paper/2019/Low-Rank%20Tensor%20Completion%20Using%20Matrix%20Factorization%20Based%20on%20Tensor%20Train%20Rank%20and%20Total%20Variation.pdf)
   * Low-Rank Tensor Completion Using Matrix Factorization Based on Tensor Train Rank and Total Variation (JSC2019), Meng Ding et al.
   

## Tensor Ring Decomposition
 * TRLRF [[Web]](https://qibinzhao.github.io/) [[Code]](https://github.com/yuanlonghao/TRLRF) [[PDF]](https://arxiv.org/abs/1809.02288)
   * Tensor Ring Decomposition with Rank Minimization on Latent Space: An Efficient Approach for Tensor Completion (AAAI 2019), Longhao Yuan et al.



## Deep Learning
 * TT-LSTM [[Web]](https://www.dbs.ifi.lmu.de/~tresp/) [[Code]](https://github.com/Tuyki/TT_RNN) [[PDF]](http://proceedings.mlr.press/v70/yang17e/yang17e.pdf)
   * Tensor-Train Recurrent Neural Networks for Video Classification (ICML 2017), Yinchong Yang et al.
 * TT-Layer [[Web]](https://github.com/Bihaqo) [[Code]](https://github.com/Bihaqo/TensorNet) [[PDF]](https://papers.nips.cc/paper/5787-tensorizing-neural-networks.pdf)
   * Tensorizing Neural Networks (NIPS 2015), Alexander Novikov et al.



   
 ## Tensor Toolbox
 * Tensor Toolbox [[Web]](https://www.sandia.gov/~tgkolda/TensorToolbox/index-2.6.html)
 * Tensorlab [[Web]](https://www.tensorlab.net/) 
 * TDALAB [[Web]](https://github.com/andrewssobral/TDALAB)  
 * TT-Toolbox  [[Web]](https://github.com/oseledets/TT-Toolbox) 
 

## Real-World Applications



## Commonly Used  Dataset
 * Videos [[Web]](http://trace.eas.asu.edu/yuv/) 
 * Multi-spectral Images [[Web]](http://www.cs.columbia.edu/CAVE/databases/multispectral/) 
 * Hyper-spectral Images [Web] 

## Commonly Used Image Quality Metrics
 * PSNR (Peak Signal-to-Noise Ratio) [[Wiki]](https://en.wikipedia.org/wiki/Peak_signal-to-noise_ratio) [[Matlab Code]](https://www.mathworks.com/help/images/ref/psnr.html) 
 * SSIM (Structural similarity) [[Wiki]](https://en.wikipedia.org/wiki/Structural_similarity) [[Matlab Code]](http://www.cns.nyu.edu/~lcv/ssim/ssim_index.m) 




   
