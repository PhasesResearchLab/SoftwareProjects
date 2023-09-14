# Phases Research Lab Software Projects
This repository serves as a meta-index of all software projects our group members are working on, from small private to large and open-source ones, emphasizing the latter.

**Contents:**
[**Active Development**](#Active-Development)  |  [**Active Contributions**](#Active-Contributions)  |  [**Maintained**](#Maintained)  |  [**Legacy**](#Legacy)  |  [**Other**](#Other)  |  [**Alumni Work**](#Alumni-Work)


**Active Members:**
|||||
|:---:|:---:|:---:|:---:|
|[Adam M. Krajewski <img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="16" height="16">](https://github.com/amkrajewski) [![orcidlogo](https://info.orcid.org/wp-content/uploads/2019/11/orcid_16x16.png)](https://orcid.org/0000-0002-2266-0099)      |    [Shuang Lin <img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="16" height="16">](https://github.com/ShuangLin212) [![orcidlogo](https://info.orcid.org/wp-content/uploads/2019/11/orcid_16x16.png)](https://orcid.org/<fill this out!>)     |    [Hui Sun <img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="16" height="16">](https://github.com/HUISUN24) [![orcidlogo](https://info.orcid.org/wp-content/uploads/2019/11/orcid_16x16.png)](https://orcid.org/<0009-0000-3667-2165>)    |  [Rushi Gong <img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="16" height="16">](https://github.com/RushiGong) [![orcidlogo](https://info.orcid.org/wp-content/uploads/2019/11/orcid_16x16.png)](https://orcid.org/<fill this out!>)  |  
[Alexander Richter <img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="16" height="16">](https://github.com/amr8004) [![orcidlogo](https://info.orcid.org/wp-content/uploads/2019/11/orcid_16x16.png)](https://orcid.org/<fill this out!>)  |  [John Shimanek <img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="16" height="16">](https://github.com/shimanek) [![orcidlogo](https://info.orcid.org/wp-content/uploads/2019/11/orcid_16x16.png)](https://orcid.org/0000-0002-2775-8466)  |  [Luke A. Myers <img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="16" height="16">](https://github.com/lukeamyers) [![orcidlogo](https://info.orcid.org/wp-content/uploads/2019/11/orcid_16x16.png)](https://orcid.org/0009-0003-0823-0871)  |  [Lucie Farrell <img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="16" height="16">](https://github.com/lucie-farrell) [![orcidlogo](https://info.orcid.org/wp-content/uploads/2019/11/orcid_16x16.png)](https://orcid.org/<fill this out!>)|
|[Prof. Zi-Kui Liu <img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="16" height="16">](https://github.com/zikuiliu) [![orcidlogo](https://info.orcid.org/wp-content/uploads/2019/11/orcid_16x16.png)](https://orcid.org/0000-0003-3346-3696)   |   [Prof. ShunLi Shang <img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="16" height="16">](https://github.com/shunlishang) [![orcidlogo](https://info.orcid.org/wp-content/uploads/2019/11/orcid_16x16.png)](https://orcid.org/0000-0002-6524-8897)  |  [Dr. Nigel Hew <img src="https://raw.githubusercontent.com/FortAwesome/Font-Awesome/6.x/svgs/brands/github.svg" width="16" height="16">](https://github.com/nhew1994) [![orcidlogo](https://info.orcid.org/wp-content/uploads/2019/11/orcid_16x16.png)](https://orcid.org/0000-0003-1374-4589)


**Legend:**
- 🟢 Open Source / 🟠 Release Soon / 🔴 Internal or Private
- ✅ User-Ready / 🔬 Research-Ready / 🏗 Under Construction and Experimental / 💤 Not-Supported
- 🤏 Small Ones

## Active Development

_Ordered open-to-internal, ready-to-experimental, and large-to-small._

### Open 🟢

- 🟢 ✅ [**pycalphad**](https://github.com/pycalphad/pycalphad) - is a free and open-source Python library for designing thermodynamic models, calculating phase diagrams and investigating phase equilibria within the CALPHAD method. It provides routines for reading Thermo-Calc TDB files and for solving the multi-component, multi-phase Gibbs energy minimization problem.

  [![GitHub last commit (by committer)](https://img.shields.io/github/last-commit/pycalphad/pycalphad?label=Last%20Commit)](https://github.com/pycalphad/pycalphad)
  [![latest](https://img.shields.io/badge/Read%20The%20Docs-Latest-green)](https://pycalphad.org/docs/latest/)
  [![codecov](https://codecov.io/gh/pycalphad/pycalphad/branch/develop/graph/badge.svg?token=Fu7FJZeJu0)](https://codecov.io/gh/pycalphad/pycalphad)
  [![PyPI version](https://badge.fury.io/py/pycalphad.svg)](https://pypi.org/project/pycalphad)

- 🟢 ✅ [**ESPEI**](https://github.com/PhasesResearchLab/ESPEI) - **E**xtensible **S**elf-optimizing **P**hase **E**quilibria **I**nfrastructure, is a tool for creating CALPHAD databases and evaluating the uncertanity of CALPHAD models. The purpose of ESPEI is to be both a user tool for fitting state-of-the-art CALPHAD-type models and to be a research platform for developing methods for fitting and uncertainty quantification.

  [![GitHub last commit (by committer)](https://img.shields.io/github/last-commit/PhasesResearchLab/ESPEI?label=Last%20Commit)](https://github.com/PhasesResearchLab/ESPEI)
  [![latest](https://img.shields.io/badge/Read%20The%20Docs-Latest-green)](https://espei.org/en/latest/)
  [![PyPI version](https://badge.fury.io/py/espei.svg)](https://pypi.org/project/espei)

- 🟢 ✅ [**pySIPFENN**](https://github.com/PhasesResearchLab/pySIPFENN) - py(**S**tructure-**I**nformed **P**rediction of **F**ormation **E**nergy using **N**eural **N**etworks) allows for easy prediction of formation energy out-of-the-box (🟢✅) and using small-dataset ML through transfer learning-based adjustment of models to new materials (🟠) and properties (🔴).

  [![GitHub last commit (by committer)](https://img.shields.io/github/last-commit/PhasesResearchLab/pysipfenn?label=Last%20Commit)](https://github.com/PhasesResearchLab/pySIPFENN)
  [![latest](https://img.shields.io/badge/Read%20The%20Docs-Latest-green)](https://pysipfenn.readthedocs.io/en/latest/)
  [![codecov](https://codecov.io/gh/PhasesResearchLab/pySIPFENN/branch/main/graph/badge.svg?token=S2J0KR0WKQ)](https://codecov.io/gh/PhasesResearchLab/pySIPFENN)
  [![PyPI version](https://badge.fury.io/py/pysipfenn.svg)](https://pypi.org/project/pysipfenn)


- 🟢 ✅ [**ULTERA-contribute**](https://github.com/PhasesResearchLab/ULTERA-contribute)
- 🟢 🔬 [**fmat**](https://github.com/HUISUN24/feasibility_map) - Uses equilibrium and Scheil simulations to allow material design with properties.

  <!-- [![GitHub last commit (by committer)](https://img.shields.io/github/last-commit/PhasesResearchLab/pysipfenn?label=Last%20Commit)](https://github.com/HUISUN24/feasibility_map)
  [![latest](https://img.shields.io/badge/Read%20The%20Docs-Latest-green)](https://github.com/HUISUN24/feasibility_map)
  [![codecov](https://codecov.io/gh/PhasesResearchLab/pySIPFENN/branch/main/graph/badge.svg?token=S2J0KR0WKQ)](https://github.com/HUISUN24/feasibility_map) -->

- 🤏 🟢 ✅ [**pqam-dparamhu2021**](https://github.com/amkrajewski/pqam-dparamhu2021) - **P**y**QA**lloy-compatible **M**odel for alloy **D** **Param**eter prediction based on Yong-Jie **Hu**'s **2021** literature model (in R) which has been optimized for high-throughput and wrapped in Python.

  [![GitHub last commit (by committer)](https://img.shields.io/github/last-commit/amkrajewski/pqam-dparamhu2021?label=Last%20Commit)](https://github.com/amkrajewski/pqam-dparamhu2021)
  [![PyPI version](https://badge.fury.io/py/pqam-dparamhu2021.svg)](https://pypi.org/project/pqam-dparamhu2021)

- 🤏 🟢 ✅ [**pqam_RMSADTandoc2023**](https://github.com/amkrajewski/pqam-dparamhu2021) - **P**y**QA**lloy-compatible **M**odel for alloy **R**oot **M**ean **S**quared **A**tomic **D**isplacement prediction is a lightweight fork of Christopher **Tandoc**'s **2023** literature model.

  [![GitHub last commit (by committer)](https://img.shields.io/github/last-commit/amkrajewski/pqam_RMSADTandoc2023?label=Last%20Commit)](https://github.com/amkrajewski/pqam_RMSADTandoc2023)
  [![PyPI version](https://badge.fury.io/py/pqam_RMSADTandoc2023.svg)](https://pypi.org/project/pqam_RMSADTandoc2023)

- 🟢 🔬 [**PyQAlloy**](https://github.com/PhasesResearchLab/PyQAlloy)

- 🤏 🟢 🔬 [**optimade-python-tools-mpdd**](https://github.com/PhasesResearchLab/optimade-python-tools-mpdd)

- 🟢 🏗 [**heaGAN**](https://github.com/amkrajewski/cGAN_demo)

### Staging 🟠

- 🟠 🔬 [**nimplex**](https://github.com/amkrajewski/nimplex)

- 🟠 🔬 [**nimcso**](https://github.com/amkrajewski/nimcso)

- 🟠 🏗 [**pqam-dparamkrajewski2023**](https://github.com/amkrajewski/pqam-dparamkrajewski2023)

- 🟠/🟢 ✅ **MPDD** ([**server**](https://github.com/PhasesResearchLab/MPDD-server) | [**tools**](https://github.com/PhasesResearchLab/MPDD-OPTIMADE)) - **M**aterial-**P**roperty-**D**escriptor **D**atabase is an atomistic data processing infrastructure allowing decentralized featurization (calculation of descriptors) and rapid machine learning model deployment on millions of DFT-relaxed configurations. Data is openly served through [**OPTIMADE**](https://github.com/Materials-Consortia/OPTIMADE) API at [mpddoptimade.phaseslab.com](http://mpddoptimade.phaseslab.com/) (🟢), but the high-throughput API and source code for server and client are kept internal for now (🟠). 

### Internal 🔴

- 🔴 ✅ **crystALL**

- 🔴 🔬 [**ULTERA**](https://github.com/PhasesResearchLab/ULTERA) - _Internal_ set of software tools developed within ULTERA projects, which will be individually released or kept internal.

- 🔴 🏗 **matmdl** - Tooling for gradient-free material model optimizations and interoperability between Abaqus finite elements and crystal plasticity subroutines.


## Active Contributions

- 🟢 [**pymatgen**](https://github.com/amkrajewski/pymatgen)

- 


## Maintained

- 🟢 ✅ [**DFTTK**](https://github.com/PhasesResearchLab/dfttk)

- 


## Legacy

- 🟢 💤 [**nanograin**](https://github.com/PhasesResearchLab/nanograin)

- 🟢 💤 [**prlworkflows**](https://github.com/PhasesResearchLab/prlworkflows)

- 🟢 💤 [**popparsing**](https://github.com/PhasesResearchLab/popparsing)

- 



## Other

-



## Alumni Work

- 🟢 ✅ [**kawin**](https://github.com/materialsgenomefoundation/kawin) - Python implementation of the Kampmann-Wagner Numerical (KWN) model to predict precipitate nucleation and growth behavior. This package couples with pycalphad to perform thermodynamic and kinetic calculations. [**See the Docs**](https://kawin.org/)

  [![GitHub last commit (by committer)](https://img.shields.io/github/last-commit/materialsgenomefoundation/kawin?label=Last%20Commit)](https://github.com/materialsgenomefoundation/kawin)
  [![PyPI version](https://badge.fury.io/py/kawin.svg)](https://pypi.org/project/kawin)

- 

## Contributions

- Please limit the description to 3 lines of text and up to 1 of badges.
- Make sure to include links to source code if the project is open-source.
- If you are an **active PRL member** you should have write access to this repository by default, and you are allowed to make changes directly.
- If you are a **past PRL member**, you are welcome to contribute (1) the code you worked on while active to the appropriate category (please use `Legacy` if you no longer actively maintain it), as well as (2) code you created after leaving the group under `Alumni Work`. You can contribute by forking the repository and opening a pull request.
- The easiest way to contribute is to open GitHub dev environment in your browser by simply clicking `.` key. It will work on any device with a keyboard (even an iPad!). With it, **you can make a simple contribution in under a minute without any knowledge of git!**. Simply (1) edit the text in the README file, which will open automatically, (2) click on the _Source Control_ icon on the left panel (third from top), (3) write a short message about what you did, and (4) click _Commit&Push_. Done!
