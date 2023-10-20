# inpta_tasks_vinay
List of tasks completed by Vinay Bharambe for InPTA coding test


Here  is the first task
1. Download the eccentricity distribution of exoplanets from the exoplanet catalog http://exoplanet.eu/catalog/. Look for the column titled e, which denotes eccentricity. Draw the histogram of this distribution. Then redraw the same histogram after Gaussianization of  the distribution using Box-transformation either using scipy.stats.boxcox or from first principles using the equations  in arXiv:1508.00931. Note that exoplanets without eccentricity data can be ignored.
After Box-cox transformation you should get a plot similar to the right side of figure 1 in arXiv:1508.00931.

2. Ok, here is the second task
 Try to reproduce the results in Table  A1 (first row) 
of https://www.aanda.org/articles/aa/pdf/2011/01/aa13999-10.pdf
The relevant equations are A.1 and Equation 3 of this paper
You can try to reproduce the results for n=2 and n=3.

3. Ok, here is the third task

 Download the SPT fgas data from https://iith.ac.in/~shantanud/fgas_spt.txt  Fit the data to f0(1 + f1z) where f0 and f1 are unknown constants. Determine the best fit values of f0 and f1 including 68% and 90% credible intervals using emcee and corner.py . The priors on f0 and f1 should be 0<f0 <0.5 and −0.5<f1 <0.5.  Use same likelihood as in Equation 6 of https://arxiv.org/pdf/2001.08340.pdf use the same priors on sigma_int as those specified in https://arxiv.org/pdf/2001.08340.pdf



(Hint : download emcee and python corner module and look up 

https://emcee.readthedocs.io/en/stable/tutorials/line/ which shows how to fit a model to a straight line)

If you need more hints let me know.)
