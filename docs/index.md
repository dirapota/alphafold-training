# Home

## Authors

- Diana Rapota [![ORCID](https://info.orcid.org/wp-content/uploads/2019/11/orcid_16x16.png)](https://orcid.org/0009-0004-0894-9816)
- Rok Breznikar [![ORCID](https://info.orcid.org/wp-content/uploads/2019/11/orcid_16x16.png)](https://orcid.org/0009-0002-5364-6879)
- Janani (Jay) Durairaj [![ORCID](https://info.orcid.org/wp-content/uploads/2019/11/orcid_16x16.png)](https://orcid.org/0000-0002-1698-4556)

## License & copyright

**License:** [CC BY-SA 4.0](https://creativecommons.org/licenses/by/4.0/deed.en)

**Copyright:** [SIB Swiss Institute of Bioinformatics](https://www.sib.swiss/)

## Overview

This two-day, hands-on course introduces protein structure prediction with AlphaFold2 and AlphaFold3. Although AlphaFold2 has made structure prediction routine, assessing when a prediction is reliable still requires practice. Participants will learn how to run predictions, interpret and validate results, and critically evaluate model quality. The course combines lectures with practical tutorials.

## Topics Covered

**Day 1: AlphaFold2 and ColabFold**

- Introduction to protein structure and the principles underlying AlphaFold2
- Running structure predictions with ColabFold (AlphaFold2 via Google Colab)
- Understanding the role of multiple sequence alignments (MSAs) for structure prediction
- AlphaFold-Multimer and protein complex prediction
- Sampling alternative conformations using advanced options of ColabFold
- Structure visualization and analysis with Mol*
- Complementary tools: Foldseek for structure-based template search, SWISS-MODEL Repository for sequence-based template search

**Day 2: AlphaFold3, Confidence Metrics, and Beyond**

- Confidence metrics in depth: pLDDT, PAE, ipTM, ipSAE, LIS, cLIS, iLIS and what they do (and do not) tell you
- AlphaFold3 changes compared to AlphaFold2
- Practical use of the AlphaFold Server: modeling proteins, ions, ligands, and post-translational modifications
- Modeling protein–ligand complexes with Boltz-2 (an AF3-class model) using SMILES inputs
- Complementary tools: LIVIA and PAE Viewer for advanced analysis
- A look towards alternative structure prediction methods: ESMFold2 and BioEmu

## Content

- Lecture slides (PDF) for every session: [Slides Day 1](day1/slides.md), [Slides Day 2](day2/slides.md)
- Practical tutorial with solutions: [ColabFold Tutorial](day1/colabfold_tutorial.md), [AlphaFold Server + Boltz-2 Tutorial](day2/alphafold_server_tutorial.md)
- Input and output data: [Data Day 1](day1/data.md), [Data Day 2](day2/data.md)

## Learning outcomes

By the end of this course, participants will be able to:

- Run AlphaFold2 predictions independently using ColabFold, including advanced options such as custom MSAs, multimer mode, and conformation sampling
- Use the AlphaFold Server to model diverse molecular assemblies (proteins, small molecules, metal ions)
- Interpret confidence metrics and critically assess whether a prediction is biologically meaningful
- Validate predicted models against experimental data and structural databases
- Apply complementary tools (Mol*, Foldseek, SWISS-MODEL) as part of a complete structure prediction workflow

## Format

Lectures, hands-on computational tutorials, and group discussion. No GPU or local installation required. All exercises run in Google Colab and publicly accessible web servers.

## Target audience

Life scientists with a basic background in molecular biology or biochemistry who want to incorporate deep learning-based protein structure prediction into their research. Prior programming experience is not required.

## Learning experiences

To reach the learning outcomes we will use lectures, exercises, polls and group work. During exercises, you are free to discuss with other participants. During lectures, focus on the lecture only.
