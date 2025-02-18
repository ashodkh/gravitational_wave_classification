# gravitational_wave_classification
Self-supervised model to classify gravitational wave signals and noise. 

I used a normalizing flow model ([masked autoregressive flow](https://arxiv.org/abs/1705.07057)) to parameterize the distribution of noise cross-spectra between two detectors. Once the distribution is learned, it can be used for hypothesis testing. I achieved a 92% AUC for low-frequency sin Gaussian signals and 89% for binary black hole merger signals. 
