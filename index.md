---
layout: default
---

```text
We are a computational group based in Uppsala,  
working on "The physical chemistry of ionically  
conducting solutions" and "The physical chemistry  
of electrically charged interfaces" for energy  
storage and conversion.
```

![group_photo](/assets/img/Group_photo_June_2021.jpg)

(From left to right: Yunqi, Lisanne, Linnéa, Omar, Yong and Chao)
# People :cn: :india: :netherlands: :sweden: :fr:

|Name             |  Role  |  Email | Note
|:-------------|:------------------|:------|
|[Chao Zhang ](https://katalog.uu.se/profile/?id=N17-1304)  |  PI  | chao.zhang@TeC | 
|[Yunqi Shao ](https://katalog.uu.se/profile/?id=N18-2059) | PhD student | yunqi.shao@TeC | Liquid and polymer electrolyte |
|[Harish Gudla](https://katalog.uu.se/profile/?id=N18-2177) | PhD student | harish.gudla@TeC | Polymer electrolyte (with Daniel Brandell)|
|[Lisanne Knijff](https://katalog.uu.se/profile/?id=N19-1351) | PhD student | lisanne.knijff@TeC | oxide/electrolyte interface |
|[Linnéa Andersson](https://katalog.uu.se/empinfo/?id=N21-323)| PhD student | linnea.andersson@TeC | metal/electrolyte interface |
|[Thomas Dufils](https://katalog.uu.se/profile/?id=N21-1716) | Postdoc | thomas.dufils@TeC | graphene/electrolyte interface |
|[Albert Pettersson](https://katalog.uu.se/profile/?id=N22-270) | Master student | albert.pettersson@TeC | graphene/electrolyte interface |

:warning:  Replace "TeC" with "kemi.uu.se"

# Research directions

## :bulb:  Modeling electrochemical interfaces with finite field MD

A realistic representation of an electrochemical interface requires
treating electronic, structural, and dynamic properties on an equal
footing. Density-functional theory-based molecular dynamics (DFTMD) method is perhaps the only approach that can provide a consistent atomistic description. However, the challenge for DFTMD modeling of material’s interfacial dielectrics is the slow convergence of the polarization P, where P is a central quantity to connect all dielectric properties of an interface.

Our contribution in this area is the development of finite field MD simulation techniques for computing electrical properties (such as the dielectric constant of polar liquids and the Helmholtz capacitance of solid-electrolyte interfaces) [1-3]. Its DFTMD implementation is available in one of our community codes CP2K ([www.cp2k.org](https://www.cp2k.org)).

## :bulb:  Simulating charge transport in battery electrolytes

Lithium batteries are electrochemical devices that involve multiple time-scale and length-scale to achieve their optimal performance and safety requirement. In terms of the electrolyte which serves as the ionic conductor, a molecular-level understanding of the corresponding transport phenomenon is crucial for rational design.

Currently, we are working on MD simulations of ionic conductivity and other transport coefficients, e.g. transference number, in different types of electrolytes from aqueous electrolytes to polymer electrolytes (with Daniel Brandell) which are relevant to battery applications [4-6].

## :bulb:  Developing atomistic machine learning for electrochemistry

Machine learning (ML) is becoming increasingly important in computational chemistry and materials discovery. Atomic neural networks (ANN), which constitute a class of ML methods, have been very successful in predicting physicochemical properties and approximating potential energy surfaces.



Recently, we have taken the initiative and developed an open-source
Python library named PiNN
([https://github.com/Teoroo-CMC/PiNN/](https://github.com/Teoroo-CMC/PiNN/)),
allowing researchers to easily develop and train state-of-the-art ANN
architectures specifically for making chemical predictions. In
particular, we have designed and implemented an interpretable and
high-performing graph convolutional neural network architecture PiNet
for predicting potential energy surface, polarization, and response
charge (to the external bias) [7-10], and demonstrate how the chemical
insight “learned” by such a network can be extracted. <img align="right" width="155" height="45" src="/assets/img/PiNN_logo.png"> This will allow
us to carry out the atomistic simulation of electrochemical systems
powered by ML models. 

# Recent publications

[1] Zhang<sup>*</sup>, C., Sayer. T., Hutter, J. and Sprik, M. _J. Phys.: Energy_, **2020**, 2: 032005, [DOI:10.1088/2515-7655/ab9d8c](https://doi.org/10.1088/2515-7655/ab9d8c) (Topical Review)

[2] Jia, M., Zhang<sup>*</sup>, C. and Cheng<sup>*</sup>, J. _J. Phys. Chem. Lett._, **2021**, 12: 4616, [DOI: 10.1021/acs.jpclett.1c00775](https://doi.org/10.1021/acs.jpclett.1c00775)

[3] Knijff, L., Jia, M. and Zhang<sup>*</sup>, C. **2022**, arXiv:2203.05486, [DOI: 10.48550/arXiv.2203.05486](https://doi.org/10.48550/arXiv.2203.05486)

[4] Gudla, H., Zhang<sup>*</sup>, C. and Brandell, D. _J. Phys. Chem. B_, **2020**, 124: 8124, [DOI: 10.1021/acs.jpcb.0c05108](https://doi.org/10.1021/acs.jpcb.0c05108)

[5] Gudla, H., Shao, Y., Phunnarungsi, S., Brandell, D. and Zhang<sup>*</sup>, C. _J. Phys. Chem. Lett._, **2021**, 12: 8460, [DOI: 10.1021/acs.jpclett.1c02474](https://doi.org/10.1021/acs.jpclett.1c02474)

[6] Shao, Y., Gudla, H., Brandell, D. and Zhang<sup>*</sup>, C. _J. Am. Chem. Soc._, **2022**, 144: 7583, [DOI: 10.1021/jacs.2c02389](https://doi.org/10.1021/jacs.2c02389)

[7] Shao, Y., Knijff, L., Dietrich, F. M., Hermansson, K. and Zhang<sup>*</sup>, C. _Batter. Supercaps_, **2021**, 4: 585, [DOI:10.1002/batt.202000262](https://doi.org/10.1002/batt.202000262) (Minireview)

[8] Shao, Y., Hellström<sup>*</sup>, M., Mitev, P. D., Knijff, L. and Zhang<sup>*</sup>, C. _J. Chem. Inf. Model._, **2020**, 60: 1184, [DOI: 10.1021/acs.jcim.9b00994](https://doi.org/10.1021/acs.jcim.9b00994)

[9] Knijff, L. and Zhang<sup>*</sup>, C. _Mach. Learn.: Sci. Technol._, 2021, 2: 03LT03, [DOI: 10.1088/2632-2153/ac0123](https://doi.org/10.1088/2632-2153/ac0123) (Letter)

[10] Shao<sup>†</sup>, Y., Andersson<sup>†</sup>, L., Knijff, L. and Zhang<sup>*</sup>,
C. _Electron. Struct._, **2022**, 4: 014012, [DOI:10.1088/2516-1075/ac59ca](https://doi.org/10.1088/2516-1075/ac59ca)
(Invited paper)

# Alumni

|Name             |  Country | Role  |  Current Position/Location |
|:-------------|:------------------|
|Yong Li  |  :cn: | Postdoc  | Postdoc@UU (Sweden)|
|Omar Malik | :united_arab_emirates:| Summer intern | Master student@UU (Sweden) |
|Linnéa Andersson | :sweden: | Research assistant | PhD student@UU (Sweden) |
|Florian Dietrich | :de: | Master student | PhD student@UCL (UK)|
|Mei Jia | :cn: | Visiting PhD student | Lecturer@SQNU (China) |
|Lisanne Knijff | :netherlands: | Master student | PhD student@UU (Sweden)|
|Supho Phunnarungsi | :thailand: | Summer intern | Bangkok (Thailand) |
|Shuang Han |:cn:| Master student | PhD student@DTU (Denmark)|
|Are Yllö | :sweden: |  Master student | Research Engineer@Sandvik Coromant (Sweden)|
|Thomas Sayer| :uk: | Visiting PhD student | Postdoc@CUBoulder (US) |

# Acknowledgement

We thank the financial supports from **Vetenskapsrådet (VR)**, **the
European Research Council (ERC)** and **Uppsala University (UU)**.


![Funding](/assets/img/Logo_banner.png)

