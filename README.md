# A Collection of Image Smoothing Algorithms

### [Image Smoothing via L0 Gradient Minimization](http://www.cse.cuhk.edu.hk/leojia/projects/L0smoothing/index.html)
```
S = L0Smoothing(Im, lambda, kappa)
```
### [Local Laplacian Filters: Edge-aware Image Processing with a Laplacian Pyramid](http://people.csail.mit.edu/sparis/publi/2011/siggraph/)
```
R = lapfilter(I,sigma_r,alpha,beta,colorRemapping,domain)
```
### [Edge-Preserving Decompositions for Multi-Scale Tone and Detail Manipulation](http://www.cs.huji.ac.il/~danix/epd/)

### [A Fast Approximation of the Bilateral Filter using a Signal Processing Approach](http://people.csail.mit.edu/sparis/bf/)
```
B = bfilter2(A,w,sigma)
```

### [Nonlinear total variation based noise removal algorithms](http://en.wikipedia.org/wiki/Total_variation_denoising)
```
out = SplitBregmanROF(image,mu,tol)
```

### [Fast Global Image Smoothing Based on Weighted Least Squares](https://sites.google.com/site/globalsmoothing/)
```
F = FGS(img, sigma, lambda, joint_image, num_iterations, attenuation)
```

### [Tree Filtering: Efficient Structure-Preserving Smoothing With a Minimum Spanning Tree](https://sites.google.com/site/linchaobao/home)
```
OUT = TreeFilterRGB_Uint8(uint8_rgbimg,sigma,sig_s[,sig_r=0.05[,num_iter=1]])
```
### [Edge-Avoiding Wavelets and their Applications](http://www.cs.huji.ac.il/~raananf/projects/eaw/)
```
[A W] = EAW(I, nlevels, wavelet_type, dist_func, sigma)
```
### [Diffusion Maps for Edge-Aware Image Editing](http://www.cs.huji.ac.il/labs/cglab/projects/diffmaps/)
```

```
### Additional
Rolling Guidance Filter: http://www.cse.cuhk.edu.hk/leojia/projects/rollguidance/
Guided Image Filtering: http://kaiminghe.com/eccv10/
Adaptive Manifolds: http://inf.ufrgs.br/~eslgastal/AdaptiveManifolds/
https://arxiv.org/abs/1503.07297v1
P Milanfar: *A tour of modern image filtering: New insights and methods, both practical and theoretical*, 2013
google scholar: https://goo.gl/FFU61H
pdf: https://www.researchgate.net/profile/Peyman_Milanfar2/publication/258792315_A_Tour_of_Modern_Image_Filtering_New_Insights_and_Methods_Both_Practical_and_Theoretical/links/5465578c0cf2052b509f2f61/A-Tour-of-Modern-Image-Filtering-New-Insights-and-Methods-Both-Practical-and-Theoretical.pdf
