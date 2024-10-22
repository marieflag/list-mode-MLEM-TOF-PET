# list-mode-MLEM-TOF-PET

/* Description */

List mode MLEM reconstruction for LAT-PET system developped in MGH&HMS. Sajedi, S., et al. "Limited-angle TOF-PET for intraoperative surgical applications: proof of concept and first experimental data." Journal of Instrumentation 17.01 (2022): T01002.

The code is parallelized with OpenMP for CPUs. The input data should be a txt file converted from root data. The link below shows how to convert the root data to a text file: https://root-forum.cern.ch/t/how-to-extract-a-data-from-dna-root-file/16182

/* Getting started */

//Dependencies cmake_minimum_required(VERSION 2.8) OpenMP

//Installing and excutating cmake CMakeList.txt make ./PET PET_head_Z7Y7X7_test.m By executing the project, users will obtain binary files containing raw images after each iteration, as well as a text file containing events used in the reconstruction.
