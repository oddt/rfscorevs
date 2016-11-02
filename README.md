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

## References:

* Wójcikowski M, Ballester P.J, Siedlecki P. Performance of machine-learning scoring functions in structure-based virtual screening. article submitted

* Wójcikowski M, Zielenkiewicz P, Siedlecki P. Open Drug Discovery Toolkit (ODDT): a new open-source player in the drug discovery field. J Cheminform. 2015;7: 5317. [doi:10.1186/s13321-015-0078-2](https://dx.doi.org/10.1186/s13321-015-0078-2)

* Ballester PJ, Mitchell JBO. A machine learning approach to predicting protein-ligand binding affinity with applications to molecular docking. Bioinformatics. 2010;26: 1169–1175. [doi:10.1093/bioinformatics/btq112](https://dx.doi.org/10.1093/bioinformatics/btq112)

* Ballester PJ, Schreyer A, Blundell TL. Does a more precise chemical description of protein-ligand complexes lead to more accurate prediction of binding affinity? J Chem Inf Model. 2014;54: 944–955. [doi:10.1021/ci500091r](https://dx.doi.org/10.1021/ci500091r)

* Li H, Leung K-S, Wong M-H, Ballester PJ. Improving AutoDock Vina Using Random Forest: The Growing Accuracy of Binding Affinity Prediction by the Effective Exploitation of Larger Data Sets. Mol Inform. WILEY-VCH Verlag; 2015;34: 115–126. [doi:10.1002/minf.201400132](https://dx.doi.org/10.1002/minf.201400132)
