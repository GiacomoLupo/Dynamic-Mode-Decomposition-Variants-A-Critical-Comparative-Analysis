# Dynamic-Mode-Decomposition-Variants-A-Critical-Comparative-Analysis
This repository contain the Master's thesis titled "Dynamic Mode Decomposition Variants: A Critical Comparative Analysis."

Abstract

This work investigates various variants of Dynamic Mode Decomposition (DMD) and their application to the Lorenz system, a well-known example of chaotic dynamics. DMD is a data-driven technique based on the Koopman operator theory, which enables the spectral analysis of nonlinear dynamical systems. Despite its versatility, the standard DMD method has certain limitations, such as sensitivity to noise and challenges in analyzing high-dimensional data. These limitations have been addressed by the development of specialized variants.

Throughout this work, six variants of DMD are derived, analyzed, and compared in detail:

    Low-Rank DMD (lrDMD)

    Sparse DMD (spDMD)

    Optimized DMD (OptDMD)

    Extended DMD (EDMD)

    Measure-preserving EDMD (mpEDMD) with QR factorization

    EDMD with Dictionary Learning (EDMD-DL)

Each variant was applied to the Lorenz system to investigate their strengths and weaknesses, as well as to evaluate their suitability for analyzing chaotic systems.

Key results include novel visualizations of the Koopman operator's eigenfunctions using EDMD with Thin-Plate Splines, along with a comprehensive spectral analysis of the Lorenz system using mpEDMD. The formal derivation of mpEDMD with QR factorization represents an important contribution by filling a gap in the existing literature regarding the use of this more robust method. Notably, this work also presents the first application of EDMD-DL to the Lorenz system, demonstrating the potential of machine learning methods to improve the analysis of chaotic systems with DMD.

These findings not only deepen our understanding of the Lorenz system but also lay a solid foundation for the future application of DMD methods to more complex dynamic systems.

In conclusion, this work shows that the combination of DMD variants and modern numerical approaches offers a powerful methodology for investigating nonlinear dynamics. The importance of clear derivations and didactic presentation is also emphasized to make these methods more accessible for future research.
