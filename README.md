# MESSy input server 

This repository contains the prototype of the stand-alone input server for MESSy (Modular Earth Submodel System). It is written in Fortran 90
and is based on the usage of Yet Another Coupler [YAC](https://dkrz-sw.gitlab-pages.dkrz.de/yac/). The work in this repository builds upon the
repository of the YAC tutorial (see https://gitlab.dkrz.de/YAC/2407_tutorial) which main author is Moritz Hanke (DKRZ, Hamburg). See also the list of authors
of YAC (AUTHORS.txt).

# Instructions
To compile and run the following steps have to be done (only tested on Levante (DKRZ)):
- Compile toy models:
  - source ./activate_levante_env
  - make
- Run job
  - adapt run script job_run.sbatch
  - sbatch job_run.sbatch

