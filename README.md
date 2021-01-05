# Segmentation-unsupervised-machine-learning

***

## Evaluating performance of microwave image reconstruction algorithms: extracting tissue types with segmentation using machine learning

### Abstract
The manuscript Kurrant, D.; Omer, M.; Abdollahi, N.; Mojabi, P.; Fear, E.; LoVetri, J. Evaluating Performance of Micro-wave Image Reconstruction Algo-rithms: Extracting Tissue Types with Segmentation Using Machine Learning. J. Imaging 2021, 7, x. https://doi.org/10.3390/xxxxx presents a medical imaging segmentation technique to automatically segment medical microwave breast images into regions of interest corresponding to various tissue types. The segmentation leads to the decomposition of the breast interior into disjoint tissue masks. An array of region and distance-based metrics are applied to compare masks extracted from reconstructed images and ground truth models. The quantitative results reveal the accuracy with which the geometric and dielectric properties are reconstructed, and are supplemented with qualitative information. Consequently, the methods presented provide a framework that effectively furnishes quantitative and qualitative assessment of regions that contain a specific tissue. The resulting information facilitates comparisons that provide valuable insight into complex issues that impact image quality. 

### Supplementary Materials
This repository provides detailed results for all cases presented in section 3.1 including the clusters after each iteration and the evolution of the PDF of the data over the region segmented as tumor (or region of interest) and region segmented outside tumor. Moreover, videos are provided to demonstrate the iterative unsupervised machine learning approach used to refine the number of clusters to segment the interior of an *Extremely Dense* breast, *Scattered Density* breast, and an *Heterogeneously Dense* breast.

***

### Figures

***

![](https://github.com/djkurran/Segmentation-unsupervised-machine-learning/blob/master/Figure%20S1%20Model%201%20forward%20model%20segmentation%20results.png)
1. Figure S1: Model 1 forward model segmentation results. (a) Region R extracted from forward model; (c) Evolution of clusters at *k = 3, 4, 6*, and *8*; (d) Evolution of PDF over data within tumor region and outside tumor region where numbers indicate iteration; (e) PDF over data within clusters *c<sub>2</sub>*, and (f) clusters *c<sub>3</sub>* (blue line) to *c<sub>8</sub>* (black line). Cluster *c<sub>2</sub>* corresponds to fatty tissue, *c<sub>3</sub>*-*c<sub>4</sub>* corresponds to transition tissue, *c<sub>5</sub>*-*c<sub>7</sub>* fibroglandular tissues, and *c<sub>8</sub>* corresponds to malignant tissue, which are mapped to segmentation masks leading to segmented image (b).

![](https://github.com/djkurran/Segmentation-unsupervised-machine-learning/blob/master/Figure%20S2%20Case%203.1a%20Segmentation%20results%20of%20reconstruction%20derived%20from%20detailed%20internal%20structure%20prior-Real%20component.png)
2. Figure S2: Case 3.1a Segmentation results of reconstruction derived from detailed internal structure prior-Real component. (a) Region R extracted from Real component; (c) Evolution of clusters at *k = 3, 4, 6*, and *10*; (d) Evolution of PDF over data within tumor region and outside tumor region where numbers indicate iteration; (e) PDF over data within clusters *c<sub>2</sub>*, and (f) clusters *c<sub>3</sub>* (blue line) to *c<sub>10</sub>* (black line). Cluster *c<sub>2</sub>* corresponds to fatty tissue, *c<sub>3</sub>*-*c<sub>4</sub>* corresponds to transition tissue, *c<sub>5</sub>* - *c<sub>9</sub>* fibroglandular tissues, and *c<sub>10</sub>* corresponds to malignant tissue, which are mapped to segmentation masks leading to segmented image (b).

![](https://github.com/djkurran/Segmentation-unsupervised-machine-learning/blob/master/Figure%20S3%20Case%203.1a%20Segmentation%20results%20of%20reconstruction%20derived%20from%20detailed%20internal%20structure%20prior-Imaginary%20component.png)
3. Figure S3 Case 3.1a Segmentation results of reconstruction derived from detailed internal structure prior-Imaginary component. (a) Region R extracted from Imaginary component; (c) Evolution of clusters at *k = 3, 4, 5*, and *7*; (d) Evolution of PDF over data within tumor region and outside tumor region where numbers indicate iteration; (e) PDF over data within clusters *c<sub>2</sub>*, and (f) clusters *c<sub>3</sub>* (blue line) to *c<sub>7</sub>* (black line). Cluster c_2 corresponds to fatty tissue, *c<sub>3</sub>*-*c<sub>4</sub>* corresponds to transition tissue, *c<sub>5</sub>* - *c<sub>6</sub>* fibroglandular tissues, and *c<sub>7</sub>* corresponds to malignant tissue, which are mapped to segmentation masks leading to segmented image (b).

![](https://github.com/djkurran/Segmentation-unsupervised-machine-learning/blob/master/Figure%20S4%20Case%203.1a%20Segmentation%20results%20of%20reconstruction%20derived%20from%20detailed%20internal%20structure%20prior-Magnitude.png)
4. Figure S4 Case 3.1a Segmentation results of reconstruction derived from detailed internal structure prior-Magnitude. (a) Region R extracted from Magnitude; (c) Evolution of clusters at *k = 3, 5, 7*, and *9*; (d) Evolution of PDF over data within tumor region and outside tumor region where numbers indicate iteration; (e) PDF over data within clusters *c<sub>2</sub>*, and (f) clusters *c<sub>3</sub>* (blue line) to *c<sub>9</sub>* (black line). Cluster *c<sub>2</sub>* corresponds to fatty tissue, *c<sub>3</sub>*-*c<sub>4</sub>* corresponds to transition tissue, *c<sub>5</sub>*-*c<sub>8</sub>* fibroglandular tissues, and *c<sub>9</sub>* corresponds to malignant tissue, which are mapped to segmentation masks leading to segmented image (b).

![](https://github.com/djkurran/Segmentation-unsupervised-machine-learning/blob/master/Figure%20S5%20Case%203.1b%20Segmentation%20results%20of%20reconstruction%20derived%20from%20regional%20internal%20structure%20prior-Real%20component.png)
5. Figure S5: Case 3.1b Segmentation results of reconstruction derived from regional internal structure prior-Real component. (a) Region R extracted from Real component; (c) Evolution of clusters at *k = 3, 5, 7*, and *9*; (d) Evolution of PDF over data within tumor region and outside tumor region where numbers indicate iteration; (e) PDF over data within clusters *c<sub>2</sub>*, and (f) clusters *c<sub>3</sub>* (blue line) to *c<sub>9</sub>* (black line). Cluster *c<sub>2</sub>* corresponds to fatty tissue, *c<sub>3</sub>*-*c<sub>4</sub>* corresponds to transition tissue, *c<sub>5</sub>*-*c<sub>8</sub>* fibroglandular tissues, and *c<sub>9</sub>* corresponds to malignant tissue, which are mapped to segmentation masks leading to segmented image (b).

![](https://github.com/djkurran/Segmentation-unsupervised-machine-learning/blob/master/Figure%20S6%20Case%203.1b%20Segmentation%20results%20of%20reconstruction%20derived%20from%20regional%20internal%20structure%20prior-Imaginary%20component.png)
6. Figure S6 Case 3.1b Segmentation results of reconstruction derived from regional internal structure prior-Imaginary component. (a) Region R extracted from Imaginary component; (c) Evolution of clusters at *k = 3, 6, 10*, and *12*; (d) Evolution of PDF over data within tumor region and outside tumor region where numbers indicate iteration; (e) PDF over data within clusters *c<sub>2</sub>*, and (f) clusters *c<sub>3</sub>* (blue line) to *c<sub>12</sub>* (black line). Cluster *c<sub>2</sub>* corresponds to fatty tissue, *c<sub>3</sub>*-*c<sub>4</sub>* corresponds to transition tissue, *c<sub>5</sub>*-*c<sub>11</sub>* fibroglandular tissues, and *c<sub>12</sub>* corresponds to malignant tissue, which are mapped to segmentation masks leading to segmented image (b).

![](https://github.com/djkurran/Segmentation-unsupervised-machine-learning/blob/master/Figure%20S7%20Case%203.1b%20Segmentation%20results%20of%20reconstruction%20derived%20from%20regional%20internal%20structure%20prior-Magnitude.png)
7. Figure S7 Case 3.1b Segmentation results of reconstruction derived from regional internal structure prior-Magnitude. (a) Region R extracted from Magnitude; (c) Evolution of clusters at *k = 3, 5, 7*, and *10*; (d) Evolution of PDF over data within tumor region and outside tumor region where numbers indicate iteration; (e) PDF over data within clusters *c<sub>2</sub>*, and (f) clusters *c<sub>3</sub>* (blue line) to *c<sub>10</sub>* (black line). Cluster *c<sub>2</sub>* corresponds to fatty tissue, *c<sub>3</sub>*-*c<sub>4</sub>* corresponds to transition tissue, *c<sub>5</sub>*-*c<sub>9</sub>* fibroglandular tissues, and *c<sub>10</sub>* corresponds to malignant tissue, which are mapped to segmentation masks leading to segmented image (b).

![](https://github.com/djkurran/Segmentation-unsupervised-machine-learning/blob/master/Figure%20S8%20Case%203.1c%20Segmentation%20results%20of%20reconstruction%20derived%20from%20skin%20region%20prior-Real%20component.png)
8. Figure S8: Case 3.1c Segmentation results of reconstruction derived from skin region prior-Real component. (a) Region R extracted from Real component; (c) Evolution of clusters at *k = 3, 6, 8*, and *10*; (d) Evolution of PDF over data within tumor region and outside tumor region where numbers indicate iteration; (e) PDF over data within clusters *c<sub>2</sub>*, and (bottom-left) clusters *c<sub>3</sub>* (blue line) to *c<sub>10</sub>* (black line). Cluster *c<sub>2</sub>* corresponds to fatty tissue, *c<sub>3</sub>*-*c<sub>4</sub>* corresponds to transition tissue, *c<sub>5</sub>*-*c<sub>9</sub>* fibroglandular tissues, and *c<sub>10</sub>* corresponds to malignant tissue, which are mapped to segmentation masks leading to segmented image (b).

![](https://github.com/djkurran/Segmentation-unsupervised-machine-learning/blob/master/Figure%20S9%20Case%203.1c%20Segmentation%20results%20of%20reconstruction%20derived%20from%20skin%20region%20prior-Imaginary%20component.png)
9. Figure S9 Case 3.1c Segmentation results of reconstruction derived from skin region prior-Imaginary component. (a) Region R extracted from Imaginary component; (c) Evolution of clusters at *k = 3, 5, 8*, and *10*; (d) Evolution of PDF over data within tumor region and outside tumor region where numbers indicate iteration; (e) PDF over data within clusters *c<sub>2</sub>*, and (bottom-left) clusters *c<sub>3</sub>* (blue line) to *c<sub>10</sub>* (black line). Cluster *c<sub>2</sub>* corresponds to fatty tissue, *c<sub>3</sub>*-*c<sub>4</sub>* corresponds to transition tissue, *c<sub>5</sub>*-*c<sub>9</sub>* fibroglandular tissues, and *c<sub>10</sub>* corresponds to malignant tissue, which are mapped to segmentation masks leading to segmented image (b).

![](https://github.com/djkurran/Segmentation-unsupervised-machine-learning/blob/master/Figure%20S10%20Case%203.1c%20Segmentation%20results%20of%20reconstruction%20derived%20from%20skin%20region%20prior-Magnitude.png)
10. Figure S10 Case 3.1c Segmentation results of reconstruction derived from skin region prior-Magnitude. (a) Region R extracted from Magnitude; (c) Evolution of clusters at *k = 3, 5, 6*, and *8*; (d) Evolution of PDF over data within tumor region and outside tumor region where numbers indicate iteration; (e) PDF over data within clusters *c<sub>2</sub>*, and (bottom-left) clusters *c<sub>3</sub>* (blue line) to *c<sub>8</sub>* (black line). Cluster *c<sub>2</sub>* corresponds to fatty tissue, *c<sub>3</sub>*-*c<sub>4</sub>* corresponds to transition tissue, *c<sub>5</sub>*-*c<sub>7</sub>* fibroglandular tissues, and *c<sub>8</sub>* corresponds to malignant tissue, which are mapped to segmentation masks leading to segmented image (b).

***

### Video demonstrations

***

### Demonstration 1 - *Extremely dense* breast - detailed demonstration of iterative unsupervised machine learning segmentation technique

This video examines the iterative unsupervised machine learning approach used to refine the number of clusters to segment the interior of an *Extremely Dense* breast so that with each iteration, the number of clusters used in the *k*-means clustering algorithm is incremented by one. The basis of the method is that after each iteration, the probability distribution of the dielectric properties within the largest valued cluster of the present iteration is compared with the probability distribution of the dielectric properties over the largest valued cluster of the previous iteration. Likewise, the probability distribution of dielectric properties outside the largest valued cluster of the present iteration is compared with the probability distribution of dielectric properties outside the largest valued cluster of the previous iteration. The algorithm terminates when the Kolmogorov-Smirnov two sample hypothesis test infers that the distribution over each of the groups of clusters has not significantly changed (statistically) after an iteration of the algorithm. 

The video also demonstrates how the clusters are mapped to tissue masks, and how the tissue masks are mapped to tissue types. The tissue types combine to form a tissue type image that serves as a qualitative tool to assist with the interpretation of the reconstructed image. The tissue masks are used to form a quantitative framework for the geometric and dielectric property analysis of the reconstructed regions.

[![Extremely Dense breast detailed demonstration of iterative unsupervised machine learning segmentation technique](https://img.youtube.com/vi/OzRo-AVjFVs/0.jpg)](https://youtu.be/OzRo-AVjFVs)

***

### Demonstration 2 - *Scattered Density* breast - detailed demonstration of iterative unsupervised machine learning segmentation technique

This video is similar to *Video Demonstration 2* in that it examines the iterative unsupervised machine learning approach used to refine the number of clusters to segment the interior of a reconstructed image. The video differs from *Video 2* in that the reconstructed image is generated from data from a forward model of an electromagnetic model of a *Scattered Density* breast, instead of an *Extremely Dense* breast. Like *Video Demonstration 6*, the probability density distribution of the dielectric properties within the largest valued cluster and the probability density distribution of the dielectric properties outside the largest valued cluster are examined to see how they change with each iteration of the algorithm. 

The video also demonstrates how the clusters are mapped to tissue masks, and how the tissue masks are mapped to tissue types. The tissue types combine to form a tissue type image that serves as a qualitative tool to assist with the interpretation of the reconstructed image. The tissue masks are used to form a quantitative framework for the geometric and dielectric property analysis of the reconstructed regions.

[![Scattered Density breast detailed demonstration of iterative unsupervised machine learning segmentation technique](https://img.youtube.com/vi/03iC7axB1Is/0.jpg)](https://youtu.be/03iC7axB1Is)

***

### Demonstration 3 - *Heterogeneously Dense * breast - detailed demonstration of iterative unsupervised machine learning segmentation technique

This video is similar to *Video Demonstration 2* in that it examines the iterative unsupervised machine learning approach used to refine the number of clusters to segment the interior of a reconstructed image. The video differs from *Video 2* in that the reconstructed image is generated from data from a forward model of an electromagnetic model of an *Heterogeneously Dense* breast, instead of an *Extremely Dense* breast. Like Video Demonstration 6, the probability density distribution of the dielectric properties within the largest valued cluster and the probability density distribution of the dielectric properties outside the largest valued cluster are examined to see how they change with each iteration of the algorithm. 

The video also demonstrates how the clusters are mapped to tissue masks, and how the tissue masks are mapped to tissue types. The tissue types combine to form a tissue type image that serves as a qualitative tool to assist with the interpretation of the reconstructed image. The tissue masks are used to form a quantitative framework for the geometric and dielectric property analysis of the reconstructed regions.

[![Heterogeneously Dense breast detailed demonstration of iterative unsupervised machine learning segmentation technique](https://img.youtube.com/vi/07fP5JFO8JE/0.jpg)](https://youtu.be/07fP5JFO8JE)



