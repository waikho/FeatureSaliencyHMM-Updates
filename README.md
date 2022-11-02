# FeatureSaliencyHMM-Updates
This is an attempt to update the codes from <a href="https://github.com/elifons/FeatureSaliencyHMM" rel="nofollow">the Implementation of Feature Saliency Hidden Markov Model (Adams, et al, 2016).</a>

The modifications to the original code are marked by "*** NEW ***".

Import the script FSHMM.py

Make sure <a href="https://hmmlearn.readthedocs.io/en/latest/" rel="nofollow">the hmmlearn library.</a> has been installed and imported too.

The modifications were only made on the GaussianHMM model. Below is an example of how to instantiate:

                  model = FSHMM.GaussianHMM(n_components = n_components, 

                          covariance_type = "diag", 
                          
                          n_iter = 10000, random_state = 42,
                          
                          k=k)   #k is the cost
