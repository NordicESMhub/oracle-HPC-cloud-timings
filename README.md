# oracle-HPC-cloud-timings

This repository contains a summary of the work done using the Oracle Cloud Infrastructure (OCI) from 20 to 28 May 2021.

- Container recipes used to run on the Oracle Cloud Infrastructure are available on [Github](https://github.com/NordicESMhub/container-noresm). This also applies when running with ARMs.

- Timings (NF2000Climo with f19_f19_mg17 resolution) are contained in `noresm-timings` folders. They were obtained on 2 different OCI platform:

    - arm-1x80-gnu-mpich-container (ARMs one Virtual Machine with 80 ARM processors)
    - oracle-intel-mpich-container (Oracle HPC cloud with 18 nodes of 36 intel processors and Beegfs)

For comparing with Betzy (largest Norwegian HPC), we have added timings for Betzy in `betzy-intel-mpich-container` folder.

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/NordicESMhub/oracle-HPC-cloud-timings/HEAD)


<img src="noresm-nf2000climo-arm-1VMx80.gif" width="80%" />


This work was produced for the [NICEST2](https://neic.no/nicest2/) project, that is supported by the Nordic e-Infrastructure Collaboration (NeIC), which is part of NordForsk.
