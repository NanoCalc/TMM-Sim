**TMM Simulator** is a user-friendly software for optical simulation of thin film solar cells. By utilizing the Transfer Matrix Method (TMM), it is possible to obtain crucial information of the device such as the optical electric field profile ($|E(x)|^2$), exciton generation profile $(Q(x))$, fraction of light absorbed per layer $(A(x))$, photocurrent ($J_{photo}$), external quantum efficiency ($EQE$, also know as $IPCE$, incident photon to current collection efficiency), internal quantum efficiency ($IQE$) and the parasitic losses.

The simulation tool is specifically designed to model devices that feature up to 10 stacked layers. Moreover, it offers the capability to simulate two distinct device structures: the bilayer and bulk heterojunction (BHJ) structures. In the bilayer structure, the active layer consist of stacked electron donor and electron acceptor materials. Conversely, the binary BHJ structure features two active layer materials that are blended throughout the film thickness. Ternary BHJ structures involve the use of three materials mixed in the active layer.

To use the TMM-Sim, one first specifies the wavelength ($\lambda$) dependent complex refractive index $\eta(\lambda)$ (optical constants) and thickness of each layer in the system. The TMM-Sim is a simple and powerful tool providing a graphical interface to facilitate its use.

![FIG-1](https://github.com/NanoCalc/TMM-Sim/assets/129612477/f0c6cade-75dd-45d2-a008-fc769eb546fd)

The program interface clearer requests to the user a input.xlsx file. All the information about the device can be easily filled in this file, as can be seen below for a device with the BHJ structure.

![FIG-2](https://github.com/NanoCalc/TMM-Sim/assets/129612477/2a908e2a-3467-44d8-ae01-d3bdaa3a511d)

**Software binaries along with example spectral data can be downloaded for the following operating systems:**  [*Unix-like systems (Linux)*](https://github.com/NanoCalc/TMM-Sim/releases/download/v1.0/TMM-Sim-Unix.zip), [*Windows*](https://github.com/NanoCalc/TMM-Sim/releases/download/v1.0/TMM-Sim-Windows.zip) and [*macOS*](https://github.com/NanoCalc/TMM-Sim/releases/download/v1.0/TMM-Sim-MacOS.zip).

`TMM-Sim` can also be used online on our website [nanocalc.org](https://nanocalc.org).

Remark: The calculation of photocurrent versus active layer thickness is not implemented on the website due to processing limitations.

# Authors
* [Leandro Benatto](https://orcid.org/0000-0001-9976-3574)<sup>a,b</sup>
* [Graziâni Candiotto](https://orcid.org/0000-0001-6755-660X)<sup>a</sup>
* [Omar Mesquita](https://orcid.org/0000-0002-6656-5683)<sup>a</sup>
* [Lucimara S. Roman](https://orcid.org/0000-0001-6567-5920)<sup>b</sup>
* [Rodrigo B. Capaz](https://orcid.org/0000-0001-5770-5026)<sup>a,c</sup>
* [Marlus Koehler](https://orcid.org/0000-0001-9935-5060)<sup>b</sup>

# Institutions
<sup>a</sup>Institute of  Physics, Federal University of Rio de Janeiro, 21941-909, Rio de Janeiro-RJ, Brazil.<br> [UFRJ](https://pos.if.ufrj.br/pt/)

<sup>b</sup>Department of Physics, Federal University of Paraná, 81531-980, Curitiba-PR, Brazil.<br> [UFPR](http://fisica.ufpr.br/posgrad/)

<sup>c</sup>Brazilian Nanotechnology National Laboratory (LNNano), Brazilian Center for Research in Energy and Materials (CNPEM), 13083-100, Campinas- SP, Brazil.<br/> [LNNano](https://lnnano.cnpem.br/en/home-en/)

# Developers
* [Leandro Benatto](https://github.com/LeandroBenatto)
* [Omar Mesquita](https://github.com/OmarMesqq)
* [Graziâni Candiotto](https://github.com/gcandiotto)

# Acknowledgments
The authors acknowledge financial support from LCNano/SisNANO 2.0 (grant 442591/2019-5), INCT - Carbon Nanomaterials and INCT - Materials Informatics. L.B. (grant E-26/202.091/2022 process 277806), O.M. (grant E-26/200.729/2023 process 285493) and G.C. (grant E-26/200.627/2022 and E-26/210.391/2022 process 271814) are greatfully for financial support from FAPERJ. The authors also acknowledge the computational support of Núcleo Avançado de Computação de Alto Desempenho (NACAD/COPPE/UFRJ), Sistema Nacional de Processamento de Alto Desempenho (SINAPAD) and Centro Nacional de Processamento de Alto Desempenho em São Paulo (CENAPAD-SP) and technical support of SMMOL - solutions in functionalyzed materials.

# Cited by

Papers that recently cited `TMM-Sim` are shown below.
<!-- [![DOI:<your number>](http://img.shields.io/badge/DOI-<your number>-<colour hexcode>.svg)](<doi link>) -->
<!-- exemplo [![DOI:10.1101/2021.01.08.425840](http://img.shields.io/badge/DOI-10.1101/2021.01.08.425840-B31B1B.svg)](https://doi.org/10.1101/2021.01.08.425840) -->
