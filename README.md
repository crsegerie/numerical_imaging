# SinGAN analysis with PatchMatch algotithm.

This repository contains a study of the creative capabilities of the SinGAN network.
We propose a rigorous method to evaluate the image creation capabilities of a GAN using the PatchMatch algorithm.

The method is described in our report. In short, we define the originality of an image with respect to a reference image by computing different metrics from the vector field generated by PatchMatch.

![main results](images/main_results.PNG)
We can see on the above image that the originality of an image created by SinGAN is much higher than that of an image using a simple copy-paste. The entropy of the histograms and the correlation of the different directions of the vector field allow to formalize this intuition.

A video available above presents our results in detail.

An implementation of the PatchMatch algorithm can be found in the PatchMatch.ipynb file, which allows to reconstitute the analysis contained in the report.

Charbel-Raphaël Segerie, Hugo Laurençon.
