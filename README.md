📖 **Table of contents**
* [Structure design](#structdes)
* [Sequence design](#seqdes)
* [Structure reconstruction](#structrec)
* [Sequence reconstruction](#seqrec)
* [Binding prediction](#bindpos)
* [Binder generation](#bindgen)
* [Molecule generation](#molgen)


💡 **Notes**
- The following lists are curated by humans, as such may be incomplete
- We do not wish to advertize one tool over any other, but simply list the tools we are aware of in a random order
- Any suggestions for improvements and additions are welcome as issues or pull requests
- Projects we identify as discontinued are marked with 💀 and in a section at the end
- If you wish to include this list in a publication do so by using the link "https://github.com/biolists/biodiffusion"

⚡️ **Brought to you by:** 
- [@sacdallago](https://twitter.com/sacdallago)
- [@MoreheadAlex](https://twitter.com/MoreheadAlex) 

----

<a name="structdes"></a>
### Structure Design
Methods that from noise sample protein structures, e.g. backbones.

  - RFDiffusion
  [![](https://img.shields.io/badge/repo-PyTorch-yellowgreen)](https://github.com/RosettaCommons/RFdiffusion)
  [![](https://img.shields.io/badge/DOI-10.1038%2Fs41586--023--06415--8-lightgrey)](https://doi.org/10.1038/s41586-023-06415-8)
    - Backbone diffusion
  - Chroma
  [![](https://img.shields.io/badge/DOI-10.1101%2F2022.12.01.518682-lightgrey)](https://doi.org/10.1101/2022.12.01.518682)
    - Backbone diffusion
  - FoldingDiff
  [![](https://img.shields.io/badge/repo-PyTorch-yellowgreen)](https://github.com/microsoft/foldingdiff)
  [![](https://img.shields.io/badge/arxiv-2209.15611-lightgrey)](https://arxiv.org/abs/2209.15611)
    - Torsion angle diffusion
  - FrameDiff
  [![](https://img.shields.io/badge/repo-PyTorch-yellowgreen)](https://github.com/jasonkyuyim/se3_diffusion)
  [![](https://img.shields.io/badge/arxiv-2302.02277-lightgrey)](https://arxiv.org/abs/2302.02277)
    - Backbone diffusion
  - Genie
  [![](https://img.shields.io/badge/repo-PyTorch-yellowgreen)](https://github.com/aqlaboratory/genie)
  [![](https://img.shields.io/badge/arxiv-2301.12485-lightgrey)](https://arxiv.org/abs/2301.12485)
    - Backbone diffusion
  - Anand/Achim
  [![](https://img.shields.io/badge/arxiv-2205.15019-lightgrey)](https://arxiv.org/abs/2205.15019)
    - Backbone or rotamer diffusion
  - ProteinSGM
  [![](https://img.shields.io/badge/repo-PyTorch-yellowgreen)](https://gitlab.com/mjslee0921/proteinsgm)
  [![](https://img.shields.io/badge/DOI-10.1038%2Fs43588--023--00440--3-lightgrey)](https://doi.org/10.1038/s43588-023-00440-3)
    - diffusion on Ca, rotamer, and other measures

----

<a name="seqdes"></a>
### Sequence Design
Methods that from noise sample sequences, e.g. residue unmasking.

  - NOS
  [![](https://img.shields.io/badge/repo-PyTorch-yellowgreen)](https://github.com/ngruver/NOS)
  [![](https://img.shields.io/badge/arxiv-2305.20009-lightgrey)](https://arxiv.org/abs/2305.20009)
    - Masked residue inpaining
  - EvoDiff
  [![](https://img.shields.io/badge/repo-PyTorch-yellowgreen)](https://github.com/microsoft/evodiff)
  [![](https://img.shields.io/badge/DOI-10.1101%2F2023.09.11.556673-lightgrey)](https://doi.org/10.1101/2022.09.11.556673)
    - Masked residue inpaining, conditioned on MSA or single sequence
  - ProteinGenerator
  [![](https://img.shields.io/badge/repo-PyTorch-yellowgreen)](https://github.com/RosettaCommons/protein_generator)
  [![](https://img.shields.io/badge/DOI-10.1101%2F2023.05.08.539766-lightgrey)](https://doi.org/10.1101/2023.05.08.539766)
    - Sequence space diffusion
  - GraDe-IF
  [![](https://img.shields.io/badge/arxiv-2306.16819-lightgrey)](https://arxiv.org/abs/2306.16819)
    - Inverse protein folding: from structure to sequence
  - Anand/Achim
  [![](https://img.shields.io/badge/arxiv-2205.15019-lightgrey)](https://arxiv.org/abs/2205.15019)
    - Masked residue inpaining
  - ProteinDT
  [![](https://img.shields.io/badge/arxiv-2302.04611-lightgrey)](https://arxiv.org/abs/2302.04611)
    - Conditional (from pLM & text) protein sequence generation
  - Frey/Prescient
  [![](https://img.shields.io/badge/repo-PyTorch-yellowgreen)](https://github.com/Genentech/walk-jump)
  [![](https://img.shields.io/badge/arxiv-2306.12360-lightgrey)](https://arxiv.org/abs/2306.12360)
    - MCMC single step denoising sequence
  - PepPrCLIP
  [![](https://img.shields.io/badge/repo-PyTorch-yellowgreen)](https://github.com/programmablebio/pepprclip)
  [![](https://img.shields.io/badge/DOI-10.1101%2F2023.06.26.546591-lightgrey)](https://doi.org/10.1101/2023.06.26.546591)
    - Forward noising ESM2 representations, CLIP based sequence reconstrubction for peptide sequences

----

<a name="structrec"></a>
### Structure Reconstruction
Methods that, given an input in modality X, impute a structure output, e.g. from image domain to PDB structure.
  - CryoDRGN 
  [![](https://img.shields.io/badge/repo-PyTorch-yellowgreen)](https://github.com/ml-struct-bio/cryodrgn)
  [![](https://img.shields.io/badge/DOI-10.1038%2Fs41592--020--01049--4-lightgrey)](https://doi.org/10.1038/s41592-020-01049-4)
    - CryoEM structure reconstruction

----

<a name="seqrec"></a>
### Sequence Reconstruction
Methods that, given an input in modality X, impute a sequence output, e.g. from frequency domain to sequence.
  - InstaNovo 
  [![](https://img.shields.io/badge/repo-PyTorch-yellowgreen)](https://github.com/instadeepai/InstaNovo)
  [![](https://img.shields.io/badge/DOI-10.1101%2F2023.08.30.555055-lightgrey)](https://doi.org/10.1101/2023.08.30.555055)
    - Given proteomics readout, reconstruct peptide sequence
----

<a name="bindpos"></a>
### Binding prediction
Methods that operate on two molecules and predict an aspect of bidning, e.g. pose
  - DiffDock 
  [![](https://img.shields.io/badge/repo-PyTorch-yellowgreen)](https://github.com/gcorso/DiffDock)
  [![](https://img.shields.io/badge/arxiv-2210.01776-lightgrey)](https://arxiv.org/abs/2210.01776)
    - Small molecule binding pose
  - DiffDock-PP
  [![](https://img.shields.io/badge/repo-PyTorch-yellowgreen)](https://github.com/ketatam/DiffDock-PP)
  [![](https://img.shields.io/badge/arxiv-2304.03889-lightgrey)](https://arxiv.org/abs/2304.03889)
    - Protein-protein binding pose
  - NeuralPLexer 
  [![](https://img.shields.io/badge/arxiv-2209.15171-lightgrey)](https://arxiv.org/abs/2209.15171)
    - Small molecule binding
  - DynamicBind
  [![](https://img.shields.io/badge/repo-PyTorch-yellowgreen)](https://github.com/luwei0917/DynamicBind)
  [![](https://img.shields.io/badge/DOI-10.21203%2Frs.3.rs--3225151-lightgrey)](https://doi.org/10.21203/rs.3.rs-3225151/v1)
    - Find binding pockets on protein surfaces
    - ⚠️ no code available @ GitHub repo

----

<a name="bindgen"></a>
### Binding generation
Methods that generate some entity (e.g. small mol) linking or binding an input entity/entities (e.g. linker generation)
  - DiffLinker
  [![](https://img.shields.io/badge/repo-PyTorch-yellowgreen)](https://github.com/igashov/DiffLinker)
  [![](https://img.shields.io/badge/arxiv-2210.05274-lightgrey)](https://arxiv.org/abs/2210.05274)
    - Linker generation
  - DiffSBDD
  [![](https://img.shields.io/badge/repo-PyTorch-yellowgreen)](https://github.com/arneschneuing/DiffSBDD)
  [![](https://img.shields.io/badge/arxiv-2210.13695-lightgrey)](https://arxiv.org/abs/2210.13695)
    - Small molecule generation given pocket
  - DiffAB
  [![](https://img.shields.io/badge/repo-PyTorch-yellowgreen)](https://github.com/luost26/diffab)
  [![](https://img.shields.io/badge/DOI-10.1101%2F2022.07.10.499510-lightgrey)](https://doi.org/10.1101/2022.07.10.499510)
    - Design antibody given antigen structure
  - DiffBP
  [![](https://img.shields.io/badge/arxiv-2211.11214-lightgrey)](https://arxiv.org/abs/2211.11214)
    - Small molecule generation given pocket

----

<a name="molgen"></a>
### Molecule generation
Methods that generate some entity (e.g. small mol) unconditionally or conditionally to target specific molecular properties (e.g. 3D molecule generation)
  - EDM
  [![](https://img.shields.io/badge/repo-PyTorch-yellowgreen)](https://github.com/ehoogeboom/e3_diffusion_for_molecules)
  [![](https://img.shields.io/badge/arxiv-2203.17003-lightgrey)](https://arxiv.org/abs/2203.17003)
  - Diffusion Prior Bridges
  [![](https://img.shields.io/badge/arxiv-2209.00865-lightgrey)](https://arxiv.org/abs/2209.00865)
  - LDM
  [![](https://img.shields.io/badge/repo-PyTorch-yellowgreen)](https://github.com/MinkaiXu/GeoLDM)
  [![](https://img.shields.io/badge/arxiv-2305.01140-lightgrey)](https://arxiv.org/abs/2305.01140)
  - GCDM
  [![](https://img.shields.io/badge/repo-PyTorch-yellowgreen)](https://github.com/BioinfoMachineLearning/bio-diffusion)
  [![](https://img.shields.io/badge/arxiv-2302.04313-lightgrey)](https://arxiv.org/abs/2302.04313)

----

<a name="Discontinued"></a>
### Discontinued

  - ProtDiff_SMCDiff
  [![](https://img.shields.io/badge/repo-PyTorch-yellowgreen)](https://github.com/blt2114/ProtDiff_SMCDiff)
  [![](https://img.shields.io/badge/arxiv-2206.04119-lightgrey)](https://arxiv.org/abs/2206.04119)
    - C-alpha backbone diffusion
    - According to GitHub, superseeded by FrameDiff and RFdiffusion
   
