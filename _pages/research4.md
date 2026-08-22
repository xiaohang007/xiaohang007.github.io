##### **1. Generative inverse design of cold metals for low-power electronics**

Cold metals are metals with an intrinsic energy gap close to the Fermi level. This unusual band structure can enable cold-carrier injection and steep-slope transistors, making the materials promising contacts for low-power electronics. However, conventional high-throughput screening can only search structures that are already present in materials databases.

We combine the MatterGPT conditional generative model with the SLICES crystal language to explore this uncharted chemical space. As illustrated in the graphical abstract, the model generates candidate crystals conditioned on thermodynamic stability and the minimum band-edge distance. A multi-stage workflow then filters the candidates by symmetry, uniqueness, and novelty before high-throughput first-principles validation.

Training on 26,309 metallic structures, the workflow generated 148,506 unique candidates targeting 50–500 meV band-edge distances; 92.1% could be reconstructed as three-dimensional crystal structures. The screening and DFT calculations identified 257 cold metals that are novel relative to the Materials Project database, covering p-type, n-type, and np-type band-edge characteristics. Phonon, electronic-structure, and work-function calculations for representative candidates further support their dynamical stability and relevance for device contacts.

**selected publications**

- [Materials & Design 269, 116776 (2026)](https://www.sciencedirect.com/science/article/pii/S0264127526013511)
