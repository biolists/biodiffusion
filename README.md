📖 **Table of contents**
* [Structure design](#structdes)
* [Sequence design](#seqdes)
* [Structure reconstruction](#structrec)
* [Binding prediction](#bindpos)
* [Binder generation](#bindgen)


💡 **Notes**
- The following lists are curated by humans, as such may be incomplete
- We do not wish to advertize one tool over any other, but simply list the tools we are aware of in a random order
- Any suggestions for improvements and additions are welcome as issues or pull requests
- Projects we identify as discontinued are marked with 💀 and in a section at the end
- If you wish to include this list in a publication do so by using the link "https://github.com/biolists/biodiffusion"

⚡️ **Brought to you by:** 
- [@sacdallago](https://twitter.com/sacdallago)

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

----

<a name="seqdes"></a>
### Sequence Design
Methods that from noise sample sequences, e.g. residue unmasking.

  - EvoDiff
  [![](https://img.shields.io/badge/repo-PyTorch-yellowgreen)](https://github.com/microsoft/evodiff)
  [![](https://img.shields.io/badge/DOI-10.1101%2F2023.09.11.556673-lightgrey)](https://doi.org/10.1101/2022.09.11.556673)

----

<a name="structrec"></a>
### Structure Reconstruction
Methods that, given an input in modality X, impute a structure output, e.g. from image domain to PDB structure.
  - CryoDRGN 
  [![](https://img.shields.io/badge/repo-PyTorch-yellowgreen)](https://github.com/ml-struct-bio/cryodrgn)
  [![](https://img.shields.io/badge/DOI-10.1038%2Fs41592--020--01049--4-lightgrey)](https://doi.org/10.1038/s41592-020-01049-4)

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

----

<a name="Discontinued"></a>
### Discontinued

  - ProtDiff_SMCDiff
  [![](https://img.shields.io/badge/repo-PyTorch-yellowgreen)](https://github.com/blt2114/ProtDiff_SMCDiff)
  [![](https://img.shields.io/badge/arxiv-2206.04119-lightgrey)](https://arxiv.org/abs/2206.04119)
    - C-alpha backbone diffusion
    - According to GitHub, superseeded by FrameDiff and RFdiffusion
   
