# YAC Tutorial

This repo contains the prototypical stand-alone input server for MESSy (). It is written in Fortran and is based on the usage of
Yet Another Coupler [YAC](https://dkrz-sw.gitlab-pages.dkrz.de/yac/). This repo builds upon the repository of the YAC tutorial
(see https://gitlab.dkrz.de/YAC/2407_tutorial) which was written by Moritz Hanke (DKRZ, Hamburg).

# Instructions
To compile and run the following steps have to be done (only tested on Levante (DKRZ)):
- Compile toy models:
  - source ./activate_levante_env
  - make
- Run job
  - adapt run script job_run.sbatch
  - sbatch job_run.sbatch

