**TMM Simulator** is a user-friendly software for optical simulation of thin film solar cells. By utilizing the Transfer Matrix Method (TMM), it is possible to obtain crucial information of the device such as the optical electric field profile ($|E(x)|^2$), exciton generation profile $(Q(x))$, fraction of light absorbed per layer $(A(x))$, photocurrent ($J_{photo}$), external quantum efficiency ($EQE$, also know as $IPCE$, incident photon to current collection efficiency), internal quantum efficiency ($IQE$) and the parasitic losses.

The simulation tool is specifically designed to model devices that feature up to 10 stacked layers. Moreover, it offers the capability to simulate two distinct device structures: the bilayer and bulk heterojunction (BHJ) structures. In the bilayer structure, the active layer consist of stacked electron donor and electron acceptor materials. Conversely, the binary BHJ structure features two active layer materials that are blended throughout the film thickness. Ternary BHJ structures involve the use of three materials mixed in the active layer.

To use the TMM-Sim, one first specifies the wavelength ($\lambda$) dependent complex refractive index $\eta(\lambda)$ (optical constants) and thickness of each layer in the system. The TMM-Sim is a simple and powerful tool providing a graphical interface to facilitate its use.

![FIG-1](https://github.com/NanoCalc/TMM-Sim/assets/102557510/e73db4fb-d698-490f-b0be-0291b9bf78f4)

The program interface clearer requests to the user a input.xlsx file. All the information about the device can be easily filled in this file, as can be seen below for a device with the BHJ structure.

![FIG-2](https://github.com/NanoCalc/TMM-Sim/assets/102557510/724f54fb-1297-4365-841d-0dda02ec5527)

**Software binaries along with example spectral data can be downloaded for the following operating systems:**  [*Unix-like systems (Linux)*](https://github.com/NanoCalc/TMM-Sim/releases/download/v1.0/TMM-Sim-Unix.zip), [*Windows*](https://github.com/NanoCalc/TMM-Sim/releases/download/v1.0/TMM-Sim-Windows.zip) and [*macOS*](https://github.com/NanoCalc/TMM-Sim/releases/download/v1.0/TMM-Sim-MacOS.zip).

`TMM-Sim` can also be used online on our website [nanocalc.org](https://nanocalc.org).

Remark: The calculation of photocurrent versus active layer thickness is not implemented on the website due to processing limitations.

# Institutions
<sup>a</sup>Institute of  Physics, Federal University of Rio de Janeiro, 21941-909, Rio de Janeiro-RJ, Brazil.<br>
<sup>b</sup>Department of Physics, Federal University of Paraná, 81531-980, Curitiba-PR, Brazil.<br>
<sup>c</sup>Brazilian Nanotechnology National Laboratory (LNNano), Brazilian Center for Research in Energy and Materials (CNPEM), 13083-100, Campinas- SP, Brazil.<br/>

# Acknowledgments
The authors acknowledge financial support from LCNano/SisNANO 2.0 (grant 442591/2019-5), INCT - Carbon Nanomaterials and INCT - Materials Informatics. L.B. (grant E-26/202.091/2022 process 277806), O.M. (grant E-26/200.729/2023 process 285493) and G.C. (grant E-26/200.627/2022 and E-26/210.391/2022 process 271814) are greatfully for financial support from FAPERJ. The authors also acknowledge the computational support of Núcleo Avançado de Computação de Alto Desempenho (NACAD/COPPE/UFRJ), Sistema Nacional de Processamento de Alto Desempenho (SINAPAD) and Centro Nacional de Processamento de Alto Desempenho em São Paulo (CENAPAD-SP) and technical support of SMMOL - solutions in functionalyzed materials.

# Cited by

Papers that recently cited `TMM-Sim` are shown below.
<!-- [![DOI:<your number>](http://img.shields.io/badge/DOI-<your number>-<colour hexcode>.svg)](<doi link>) -->
<!-- exemplo [![DOI:10.1101/2021.01.08.425840](http://img.shields.io/badge/DOI-10.1101/2021.01.08.425840-B31B1B.svg)](https://doi.org/10.1101/2021.01.08.425840) -->
