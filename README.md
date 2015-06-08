# Revealing mesocale structures of time-varying networks through non-negative tensor factorization

This is the repository for the notebooks were we show how the method presented in [1] can be applied to data about face-to-face proximity relations collected in a school.

The notebook with steps to load the data and apply non-negative tensor factorization is [ntf_school.ipynb](ntf_school.ipynb).

The data with class mapping and time-varying proximity interactions are available in the `/data` folder. This is pre-processed data (with the nights removed) in csv (comma-separated values) format. The detailed description of the data can be found in [2]. The original data (without any filtering) can be found in [3].

Contributing
------------
You can contribute to this repository with comments and changes.
If you have a Github account, please fork the repository,
create a topic branch, and commit your changes.
Then submit a pull request from that branch.
You can also discuss other issues through the Github Issue tracking system.

References
----------

[1] L. Gauvin, A. Panisson, C. Cattuto. [Detecting the Community Structure and Activity Patterns of Temporal Networks: A Non-Negative Tensor Factorization Approach](http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0086028#pone-0086028-g001) PLOS ONE 9.1 (2014): e86028.

[2] Stehlé, J., Voirin, N., Barrat, A., Cattuto, C., Isella, L., Pinton, J. F., ... & Vanhems, P. "High-resolution measurements of face-to-face contact patterns in a primary school." PLoS ONE 2011, 6(8):23176.

[3] Gemmetto, V., Barrat, A., & Cattuto, C. "Mitigation of infectious disease at school: targeted class closure vs school closure." BMC infectious diseases 14.1 (2014): 695.
