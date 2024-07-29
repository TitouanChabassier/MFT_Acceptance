# MFT_Acceptance

<a name="readme-top"></a>

## About The Project
This project has been developed as part of an internship in the Muon Forward Tracker team of the ALICE collaboration. The goal is to compute with independant tools the geometrical acceptance of the MFT. The repositery contains a dataframe directory, where computed acceptance values are stored and a "Results" directory where conclusion plots are saved. The code used to obtain these results is also given. It is written in Python using Jupyter Notebooks. 

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started
Because some of the code uses ROOT, the project was mainly worked on through a virtual machine (VM) simulating an Ubuntu environement. The software used to manipulate the VM is VMware Workstation. For conveniance, the VM can be shared as all the code runs succefully on it.

### Prerequisites
The libraries used in this project are listed in this section. Python3 comes with many libraries pre-installed such as numpy and pandas. To install a librairy, make sure Python3 is installed and then use pip through a terminal.
```
pip install <librairy>
```
* numpy
* pandas
* matplotlib.pyplot
* matplotlib.pylab
* math
* time
* os
* combinations from itertools
* re
* Counter from collections
* Github from github
* get_colors from distinctipy
* base64

ROOT was installed following the official CERN guide with conda on an Ubuntu VM.

<!-- USAGE EXAMPLES -->
## Usage


<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ROADMAP -->
## Roadmap

- [x] Upload main MFT acceptance functions as seperate files
- [x] Upload personal library
- [ ] Upload all computed dataframes
- [ ] Compare C' condition with static dead map results
- [ ] Compute individual chip weights
- [ ] Make table to summarize chip weights in phi distributions

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTACT -->
## Contact

Chabassier Titouan - titouan.chabassier@laposte.net

Project Link: [https://github.com/TitouanChabassier/MFT_Acceptance]

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge
