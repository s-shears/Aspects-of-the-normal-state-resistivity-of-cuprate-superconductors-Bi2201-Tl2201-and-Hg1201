# Aspects-of-the-normal-state-resistivity-of-cuprate-superconductors-Bi2201-Tl2201-and-Hg1201
Supplemental material for "Aspects of the normal state resistivity of cuprate superconductors Bi2201, Tl2201 and Hg1201". See Zenodo for the official publication: https://doi.org/10.5281/zenodo.15306959

### Content

#### Python



This is supplemental material for our recent paper "Aspects of the normal state resistivity of cuprate superconductors Bi2201, Tl2201 and Hg1201", along with some results for systems from the older paper "Aspects of the normal state resistivity of cuprate superconductors". It includes data (stored as polynomial coefficients) and six Jupyter notebooks (the .ipynb files) to read the data for Tl2201 Model A, Tl2201 Model B, Bi2201, Hg1201, LSCO and BSLCO. 



You may find the data files for each system in the following zip folders:



Tl2201 and Bi2201 data is located in data.zip



BSLCO and LSCO data is located in oldpaperdata.zip



Hg1201 data is located in Hg1201data.zip



Place the relevant data files in the same folder as their Jupyter notebooks for import. **These notebooks are designed to be very easy to use even if you do not read Python.** Simply open up the notebook, press run, wait 10 minutes or so and scroll to the bottom where it says "SKIP HERE FOR RESULTS". We provide spectral functions, the imaginary part of the Dyson self energy, and resistivities. There is also an interpolation tool at the very bottom for estimating resistivities at different densities than those provided.



#### Mathematica



In addition to our Python programs, the resistivity data from larger system sizes as it appears in the paper is available in the Mathematica notebooks (with t=1, which you can adjust as you desire). You may also find the program that generated all of our data on GitHub here: https://github.com/marcinia-sudo/2DECFL2ndOrder



### Details



The frequency we used to make the data accessed by the Python files ranges 2^12 points across a relatively wide domain, omega=+-50. This is necessary for convergence. However, the bulk of the spectral weight is concentrated in a relatively small region. We provide data that was fitted across the 43 points in the range omega=+-0.5127. Though this may seem too small, you can see in the provided notebooks that this still retrieves a resistivity value very similar to the results in the paper. 



The larger resistivity calculations shown in the Mathematica files and in the paper use omega=+-20, other computational details can be found in the paper.





### Papers:



https://doi.org/10.48550/arXiv.2502.00293



https://doi.org/10.48550/arXiv.1911.09119



