# rtt-privacy-paper

This repository contains *Revisiting the Privacy Implications of Two-Way Internet Latency Data* by Brian Trammell and Mirja Kühlewind, to appear in the proceedings of the 2018 Passsive and Active Measurement Conference, along with associated Jupyter notebooks.

The [Jupyter notebooks](https://github.com/mami-project/rtt-privacy-paper/tree/master/notebooks) contain all the code used to analyze measurements used in this paper; change to the `notebooks` directory in a working copy and run `jupyter notebook`. 

- The [Atlas dataprep](https://github.com/mami-project/rtt-privacy-paper/blob/master/notebooks/atlas_dataprep.ipynb)
  notebook will download measurements from RIPE Atlas, and can be configured
  to look at dates other than those we considered. 

- The [Linear modeling](https://github.com/mami-project/rtt-privacy-paper/blob/master/notebooks/linear_modeling.ipynb)
  notebook can be used to derive the linear distance models we used; however, the MONROE data is not included in the repository as we do not yet have permission to redistribute it.

- [Exclusion](https://github.com/mami-project/rtt-privacy-paper/blob/master/notebooks/exclusion_geoloc.ipynb)
  generates the plots of exclusion circles for each anchor.

- The detailed ping experiment on the author's network in Section 4 appears in
  [PingMe](https://github.com/mami-project/rtt-privacy-paper/blob/master/notebooks/pingme.ipynb),
  and analysis of the RIPE second hop data appears in [Atlas Second
  Hop](https://github.com/mami-project/rtt-privacy-paper/blob/master/notebooks/atlas_second_hop.ipynb)

- Analysis of initial data from the
  [PingMe](https://pingme.pto.mami-project.eu) online application appears in
  the [PingMe PTO](https://github.com/mami-project/rtt-privacy-paper/blob/master/notebooks/pingme_pto.ipynb)
  notebook; the raw data it uses is not included in the repository, as it
  includes the IP addresses of people who provided us data by using the tool.
