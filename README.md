# FeatureSaliencyHMM-Updates
This is an attempt to update the codes from <a href="https://github.com/elifons/FeatureSaliencyHMM" rel="nofollow">the Implementation of Feature Saliency Hidden Markov Model (Adams, et al, 2016).</a>

Import the script FSHMM.py

Make sure <a href="https://hmmlearn.readthedocs.io/en/latest/" rel="nofollow">the hmmlearn library.</a> has been installed and imported too.

An example of how to instantiate a model:

                  model = FSHMM.GaussianHMM(n_components = n_components, 

                          covariance_type = "diag", 
                          
                          n_iter = 10000, random_state = 42,
                          
                          k=k)   #k is the cost
