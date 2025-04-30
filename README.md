# fMRI Analysis: First-Level Analysis of Cognitive Control

## Overview
This repository contains the analysis pipeline and results from a first-level fMRI study investigating cognitive control processes using the flanker task. The analysis was conducted using SPM-25, focusing on the neural correlates of conflict resolution between incongruent and congruent conditions.

## Abstract
The study examines brain activity patterns during cognitive control tasks, specifically comparing incongruent and congruent conditions across multiple sessions. The analysis pipeline includes preprocessing steps, model specification, and statistical inference to identify brain regions involved in executive function and conflict resolution.

## Key Components

### 1. Preprocessing Pipeline
- **Realignment**: Correction for head motion
- **Slice Timing**: Addressing temporal disparities between slices
- **Coregistration**: Alignment of functional and anatomical images
- **Segmentation**: Brain tissue classification
- **Normalization**: Standard space transformation
- **Smoothing**: Enhancement of signal-to-noise ratio

### 2. Model Specification
- **Experimental Design**: Flanker task with incongruent and congruent conditions
- **Session Structure**: Multiple scanning sessions
- **Parameter Estimation**: Statistical modeling of brain activity

### 3. Statistical Analysis
- **Contrast Management**: 
  - t-contrast comparing incongruent vs. congruent conditions
  - Contrast vector: [0.5 -0.5 0.5 -0.5]
  - Significance threshold: p < 0.01 (uncorrected)
  - Extent threshold: 10 voxels

### 4. Results Visualization
- Statistical parametric maps
- Anatomical overlays
- Local and global maxima tables

## Key Findings
The analysis revealed significant activation patterns in brain regions associated with cognitive control, particularly in the prefrontal cortex and anterior cingulate cortex. These findings provide insights into the neural mechanisms underlying conflict resolution and executive function.

## Future Directions
1. Second-level Analysis: Extension to group-level analysis
2. Region of Interest (ROI) Analysis: Detailed characterization of specific brain regions
3. Functional Connectivity Analysis: Investigation of network-level organization
4. Multi-Modal Integration: Combination with other neuroimaging modalities

## Technical Details
- **Software**: SPM-25
- **Dataset**: OpenNeuro (ds000102)
- **Analysis Tools**: SPM's built-in visualization and statistical tools

## References
1. Han, H., & Park, J. (2018). Using SPM 12's second-level Bayesian inference procedure for fMRI analysis: practical guidelines for end users. Frontiers in neuroinformatics, 12, 1.
2. Smith, S. M. (2004). Overview of fMRI analysis. The British Journal of Radiology, 77(suppl 2), S167-S175.
3. Jahn, A. (2019). SPM-25 manual and onset times conversion. https://github.com/andrewjahn
4. Jahn, A. (2020). Introduction to SPM-25 flanker test. https://youtube.com/playlist?list=PLIQIswOrUH689KpRPCa5-h6U-m9CddWM6&si=FyEtHKeg2wWPsAT6
5. SPM (2014). Official website of SPM-25. https://www.fil.ion.ucl.ac.uk/spm/software/spm12/
6. Open Neuro. (2018). Dataset from Open Neuro. https://openneuro.org/datasets/ds000102/versions/00001

## License
This work is licensed under [appropriate license].

## Contact
For questions or collaborations, please contact [contact information]. 
