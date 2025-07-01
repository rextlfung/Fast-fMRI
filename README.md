# Fast-fMRI
A set of tools for highly accelerated fMRI acquisition and reconstruction.

This is the parent repository of these three repositories:
1. [Acquisition](https://github.com/rextlfung/rand3depi): Random sampling pattern generation, pulseq sequence programming, and pulseq --> GE interpretation.
2. [Preprocessing](https://github.com/rextlfung/fmri-prep): GE ScanArchive data loading, linear phase correction (LPC) for odd/even echoes, allocation of randomly sampled data.
3. [Reconstruction](https://github.com/rextlfung/fmri-recon): Locally low-rank (LLR) image reconstruction using the proximal optimized gradient method (POGM) from [MIRT](https://github.com/JeffFessler/MIRT.jl)
