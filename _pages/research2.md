##### **2. SLICES: An invertible, invariant crystal language for inverse design of solid-state materials using GenAI**

The Problem: Unlike the field of molecular design, which has rapidly advanced thanks to representations like SMILES, the inverse design of crystalline materials has been hindered by the lack of an invertible and invariant representation.

The Solution (SLICES): To solve this, researchers developed the Simplified Line-Input Crystal-Encoding System (SLICES), a string-based representation that guarantees invariance by encoding only chemical composition and topology. It demonstrated unprecedented invertibility, with a 94.95% reconstruction success rate for over 40,000 diverse crystal structures. This enables the use of generative models like MatterGPT for the inverse design of crystals with target properties such as energy above hull and band gap.

Further Improvement (SLICES-PLUS): While effective, SLICES did not explicitly control for spatial symmetry, often leading to the generation of low-symmetry materials. To address this, SLICES-PLUS was developed. It enhances the original SLICES string by appending encoded information about the crystal's spatial symmetry operations (rotation matrices and translation vectors) derived from Wyckoff positions. This enhancement allows models to precisely target and control both the physical properties and the crystal system (e.g., cubic) of the generated materials.


**selected publications**
- [Nat Commun 14, 7027 (2023)](https://www.nature.com/articles/s41467-023-42870-7)
- [Materials & Design 253, 113856 (2025)](https://www.sciencedirect.com/science/article/pii/S026412752500276X)


**other references**
- [Arxiv Preprint (2024)](http://arxiv.org/abs/2406.17295)


