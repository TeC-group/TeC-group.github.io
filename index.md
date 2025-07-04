---
layout: default
---

```text
We are a computational group based in Uppsala,  
working on "The physical chemistry of ionically  
conducting solutions" and "The physical chemistry  
of electrically charged interfaces" for energy  
storage applications.
```

![group_photo](/assets/img/TeC_Jun_2024.jpg)

(From left to right: Zhan-Yun, Aishwarya, Emily, Alicia, Lisanne, Aniello, Linnéa, and Jichen)
# People :cn: :india: :netherlands: :sweden: :iceland: :estonia: 

|Name             |  Role  |  Email | Note
|:-------------|:------------------|:------|
|[Chao Zhang](https://katalog.uu.se/profile/?id=N17-1304)  |  PI  | chao.zhang@TeC | [Biosketch](https://yacadeuro.org/zhang/) |
|[Lisanne Knijff](https://katalog.uu.se/profile/?id=N19-1351) | PhD student | lisanne.knijff@TeC | ML-accelerated simulations |
|[Linnéa Andersson](https://katalog.uu.se/profile/?id=N21-323)| PhD student | linnea.andersson@TeC | Metal/electrolyte interfaces |
|[Aishwarya Sudhama](https://www.katalog.uu.se/profile/?id=N22-2260) | PhD student | aishwarya.sudhama@TeC | Oxide/electrolyte interfaces |
|[Alicia van Hees](https://www.katalog.uu.se/empinfo/?id=N22-264) | PhD student | alicia.van-hees@TeC | Interfacial PCET | 
|[Jichen Li](https://www.katalog.uu.se/empinfo/?id=N23-1517) | PhD student | jichen.li@TeC | Polymer electrolytes (with Daniel Brandell) |
|[Zhan-Yun Zhang](https://www.katalog.uu.se/empinfo/?id=N23-2102) | Postdoc | zhan-yun.zhang@TeC | WISE-ap1 |
|[Movaffaq Kateb](https://www.uu.se/kontakt-och-organisation/personal?query=N24-2523) | Senior postdoc | movaffaq.kateb@TeC  | Self-healing polymers (with Kristina Edström) |
| [Floor de Vries](https://www.uu.se/kontakt-och-organisation/personal?query=N25-516) | Master student | N/A | Research training | 
| [Kadri Muuga](https://www.uu.se/kontakt-och-organisation/personal?query=N25-329) | Master student | N/A | Thesis work |

:warning:  Replace "TeC" with "kemi.uu.se"

# Research directions

## :dart:  Modeling electrochemical interfaces with finite field MD

A realistic representation of an electrochemical interface requires
treating electronic, structural, and dynamic properties on an equal
footing. Density-functional theory-based molecular dynamics (DFTMD) method is perhaps the only approach that can provide a consistent atomistic description. However, the challenge for DFTMD modeling of material’s interfacial dielectrics is the slow convergence of the polarization P, where P is a central quantity to connect all dielectric properties of an interface.

Our contribution in this area is the development of finite field MD simulation techniques for computing electrical properties (such as the dielectric constant of polar liquids and the Helmholtz capacitance of solid-electrolyte interfaces) [1-3]. Its DFTMD implementation is available in one of our community codes CP2K ([www.cp2k.org](https://www.cp2k.org)).

## :dart:  Simulating charge transport in battery electrolytes

Lithium batteries are electrochemical devices that involve multiple time-scale and length-scale to achieve their optimal performance and safety requirement. In terms of the electrolyte which serves as the ionic conductor, a molecular-level understanding of the corresponding transport phenomenon is crucial for rational design.

Currently, we are working on MD simulations of ionic conductivity and other transport coefficients, e.g. transference number, in different types of electrolytes from aqueous electrolytes to polymer electrolytes (with Daniel Brandell) which are relevant to battery applications [4-6].

## :dart:  Developing atomistic machine learning for electrochemistry

Machine learning (ML) is becoming increasingly important in computational chemistry and materials discovery. Atomic neural networks (ANN), which constitute a class of ML methods, have been very successful in predicting physicochemical properties and approximating potential energy surfaces.

Recently, we have taken the initiative and developed a pair-wise interaction neural network
Python library named PiNN [https://github.com/Teoroo-CMC/PiNN/](https://github.com/Teoroo-CMC/PiNN/),
allowing researchers to easily develop and train state-of-the-art ANN
architectures specifically for making chemical predictions. In
particular, we have designed and implemented an equivariant and
high-performing graph convolutional neural network architecture PiNet2
for predicting potential energy surface, polarization, and response
charge (to the voltage bias) [7-9]. <img align="right" width="118" height="50" src="/assets/img/PiNN_logo.png"> This allows
us to carry out the atomistic simulation of electrochemical systems
powered by ML models [10].

# Recent publications

[1] Andersson, L. and Zhang<sup>*</sup>, C. _Curr. Opin. Electrochem._, **2023**, 42: 101407, [DOI: doi.org/10.1016/j.coelec.2023.101407](https://doi.org/10.1016/j.coelec.2023.101407)

[2] Knijff, L., Jia, M. and Zhang<sup>*</sup>, C. _Encyclopedia of Solid-Liquid Interfaces_, **2024**, 2: 567, [DOI: 10.1016/B978-0-323-85669-0.00012-X](https://doi.org/10.1016/B978-0-323-85669-0.00012-X)

[3] Andersson, L., Sprik, M., Hutter, J. and Zhang<sup>*</sup>, C. _Angew. Chem. Int. Ed._, **2025**, 64: e202413614, [DOI: 10.1002/anie.202413614](https://doi.org/10.1002/anie.202413614)

[4] Gudla, H., Shao, Y., Phunnarungsi, S., Brandell, D. and Zhang<sup>*</sup>, C. _J. Phys. Chem. Lett._, **2021**, 12: 8460, [DOI: 10.1021/acs.jpclett.1c02474](https://doi.org/10.1021/acs.jpclett.1c02474)

[5] Shao, Y., Gudla, H., Brandell, D. and Zhang<sup>*</sup>, C. _J. Am. Chem. Soc._, **2022**, 144: 7583, [DOI: 10.1021/jacs.2c02389](https://doi.org/10.1021/jacs.2c02389)

[6] Gudla, H., Edström, K. and Zhang<sup>*</sup>, C.  _ACS Mater. Au_, **2024**, 4: 300 [DOI: 10.1021/acsmaterialsau.3c00098](https://doi.org/10.1021/acsmaterialsau.3c00098)

[7] Knijff, L. and Zhang<sup>*</sup>, C. _Mach. Learn.: Sci. Technol._, **2021**, 2: 03LT03, [DOI: 10.1088/2632-2153/ac0123](https://doi.org/10.1088/2632-2153/ac0123) (Letter)

[8] Shao<sup>†</sup>, Y., Andersson<sup>†</sup>, L., Knijff, L. and Zhang<sup>*</sup>,
C. _Electron. Struct._, **2022**, 4: 014012, [DOI:10.1088/2516-1075/ac59ca](https://doi.org/10.1088/2516-1075/ac59ca)
(Invited paper)

[9] Dufils, T., Knjiff, L., Shao, Y. and Zhang<sup>*</sup>, C. _J. Chem. Theory Comput._, **2023**, 19: 5199, [DOI: 10.1021/acs.jctc.3c00359](https://doi.org/10.1021/acs.jctc.3c00359)

[10] Li<sup>†</sup>, J.,  Knijff<sup>†</sup>, L., Zhang, Z.-Y., Andersson, L. and Zhang<sup>*</sup>, C. _J. Chem. Theory Comput._, **2025**, 21: 1382, [DOI: 10.1021/acs.jctc.4c01570](https://doi.org/10.1021/acs.jctc.4c01570)


# Alumni

|Name             |  Country | Role  |  Current Position/Location |
|:-------------|:------------------|
|Aniello  Langella |  :it: | Visiting PhD student (with Daniel Brandell)  | PhD student@UniNa (Italy)|
|Harish Gudla  |  :india: | Postdoc (with Kristina Edström)  | Computational materials scientist@Compular (Sweden)|
|Emily Azzopardi | :malta: | Master student | Uppsala (Sweden) |
|Yunqi Shao | :cn: | PhD student | Research engineer@Chalmers (Sweden) |
|Thomas Dufils | :fr: | Postdoc | Teacher@Lycée Albert Einstein (France) |
|Matthew Chagnot | :us: | Visiting PhD student | PhD student@NCSU (US) |
|Sheng Bi | :cn: | Visiting postdoc | Associate professor@XMU (China) |
|Alicia van Hees | :sweden: | Master student | PhD student@UU (Sweden)|
|Harish Gudla  |  :india: | PhD student (with Daniel Brandell)  | Postdoc@UU (Sweden)|
|Alexandros Zantis | :cyprus: | Summer intern | Master student@UU (Sweden) |
|Albert Pettersson | :sweden: | Master student | Chemical engineer@Sandvik Materials Technology (Sweden) |
|Yong Li  |  :cn: | Postdoc  | Assistant professor@CQU (China)|
|Majid Shahbabaei | :iran: | Postdoc | Assistant professor@BNUT (Iran) | 
|Omar Malik | :united_arab_emirates:| Summer intern | Master student@UU (Sweden) |
|Linnéa Andersson | :sweden: | Research assistant | PhD student@UU (Sweden) |
|Florian Dietrich | :de: | Master student | PhD student@UCL (UK)|
|Mei Jia | :cn: | Visiting PhD student | Lecturer@SQNU (China) |
|Lisanne Knijff | :netherlands: | Master student | PhD student@UU (Sweden)|
|Supho Phunnarungsi | :thailand: | Summer intern | Bangkok (Thailand) |
|Shuang Han |:cn:| Master student | Research scientist@BASF (Germany)|
|Are Yllö | :sweden: |  Master student | Research engineer@Sandvik Coromant (Sweden)|
|Thomas Sayer| :uk: | Visiting PhD student | Leverhulme fellow@Durham (UK) |

# Acknowledgement

We thank the financial supports from **Vetenskapsrådet (VR)**, **the
European Research Council (ERC)** [DeepProton project](https://cordis.europa.eu/project/id/949012) and **the Wallenberg Initiative Materials Science for Sustainability (WISE)**.

We are also part of the materials modelling community [TEOROO](https://github.com/Teoroo-CMC) based at Kemi-Ångström.


![Funding](/assets/img/Logo_banner.png)

```text
"The drive for excellence relies on both competitive 
energy and collaborative partnership."
```
