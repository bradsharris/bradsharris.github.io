---
title: "GenEvaPa: A generic evaporation package for modeling evaporation in molecular dynamics simulations"
date: 2023-01-01
publishDate: 2023-01-01
authors: ["Bradley Harris", "Gang-yu Liu", "Roland Faller"]
publication_types: ["2"]
abstract: "This work presents a novel general tool for modeling the process of evaporation without the need for modifying existing software using Python. The tool was developed based on the MDAnalysis package, which is used to import a Molecular Dynamics trajectory. The tool then removes solvent molecules and outputs a new structure file to be used for further simulation and analysis. This process is designed to be iterated by using the resulting dynamic simulation trajectory as the input file. The evaporation is designed to randomly delete solvent molecules while preserving solvation shells around solutes. The evaporation rate can be controlled by the length of the MD simulations and the number of particles removed between dynamic simulations. Validity of the tool was tested extensively using the Gromacs suite. Advantages of this tool include its genericness, simplicity and user friendliness, as no significant modification …"
featured: true
publication: "Computer Physics Communications 2023 282 "
links:
  - icon_pack: fas
    icon: scroll
    name: Link
    url: 'https://www.sciencedirect.com/science/article/pii/S0010465522002582'
---
