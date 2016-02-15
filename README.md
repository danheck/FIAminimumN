# FIAminimumN

Lower-bound N for MPT model selection using FIA (based on multiTree output)


## MPT Model Selection Using Minimum Description Length (MDL / FIA)

Multinomial processing tree (MPT) models are often used in psychology to disentangle latent cognitive processes resulting in categorical responses. Statistical model selection of competing MPT models is often used to test psychological theories.

The MPT software multiTree (Moshagen, 2010) allows to compute the Fisher information approximation (FIA), a model selection criterion based on the minimum description length principle similar to AIC or BIC. Essentially, FIA allows to make a trade-off between the fit and complexity of the models under consideration. FIA has the advantage that it takes the functional complexity of the models into account (e.g., how the parameters in the MPT model are connected and whether order constraints such as Do>Dn are included).

However, FIA is only an approximation that can fail if the number of observations is too small, leading to severely biased model selection. As a remedy, it should only be used if the total number of observations (usually the numer of responses times the number of participants) exceeds a lower bound (Heck, Moshagen, & Erdfelder, 2014). 

The Excel/LibreOffice sheets available in `FIAminimumN` allow to compute this lower-bound sample size for FIA:

* Excel spreadsheet: https://github.com/danheck/FIAminimumN/blob/master/FIA_lower_bound_N_multiTree.xlsx
* LibreOffice spreadsheet: https://github.com/danheck/FIAminimumN/blob/master/FIA_lower_bound_N_multiTree.ods

The remaining files (.mdt) are the corresponding multiTree files containing the competing MPT models that are used as an example.


## References

* Heck, D. W., Moshagen, M., & Erdfelder, E. (2014). Model selection by minimum description length: Lower-bound sample sizes for the Fisher information approximation. Journal of Mathematical Psychology, 60, 29-34. http://dx.doi.org/10.1016/j.jmp.2014.06.002

* Moshagen, M. (2010). multiTree: A computer program for the analysis of multinomial processing tree models. Behavior Research Methods, 42, 42-54.
    * Download multiTree: http://psycho3.uni-mannheim.de/Home/Research/Software/multiTree/




