# RF-Score-VS 1.0

RF-Score-VS is a novel Random Forest-based scoring function for Virtual Screening which predicts binding affinity.
Its descriptors are based on RF-Score developed by Pedro Ballester et. al.
Presented binary implements RF-Score-VS v2, meaning, it counts atoms of certain types within a 12A radius, divided into 2A bins.

Presented repository contains scripts required to reproduce results included in publication introducing RF-Score-VS **[article submitted]**

## Standalone scoring function

The RF-Score-VS is available as a standalone scoring function with no dependencies required.
Usage instructions and detailed information about the binary are available in README.md file alongside binaries and in [separate repository](https://github.com/oddt/rfscorevs_binary).

Download RF-Score-VS for your platform:

* [Linux 64-bit](http://wojcikowski.pl/travis/rf-score-vs_v1.0_linux_2.7.zip)
* [Windows 64-bit](http://wojcikowski.pl/travis/rf-score-vs_v1.0_win_2.7.zip)
* [MacOS 64-bit](http://wojcikowski.pl/travis/rf-score-vs_v1.0_macos_2.7.zip)

## Requirements for running iPython Notebooks

Required software:
* Python 2.7
* ODDT 0.2+
* OpenBabel 2.4.1+
* Scikit-Learn 0.17+

Additional software:
* sklearn-compiledtrees 1.3+ (compiling RFs for final scoring function)
* dask / ipyparallel (parallel computations on cluster)
