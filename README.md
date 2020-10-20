# SSRM-3D-Resistivity-Mapping
Image analysis tools for creating 3D resistivity and phase maps from Scanning-spreading resistance microscopy.

## Abstract

In this work, Python code is applied to data acquired with **s**canning **s**preading **r**esistance **m**icroscopy (SSRM) to extract histograms and develop visualizations of raw resistivity data in three-dimensions (3-D). This work has been applied to composite electrodes for lithium-ion battery negative electrodes containing graphite, silicon nanoparticles, conductive carbon additive, and polymeric binder. The intrinsic electronic properties of these individual electrode components lend to their identification from SSRM resistivity data: from extracted histograms, SSRM resistivity thresholds can be applied to extract distinct volumes from the composite structure. This Python code serves to contribute to the analysis of electrode component dispersion and distribution within lithium-ion battery negative electrode upon fabrication, and their subsequent heterogeneous development of solid electrolyte interphase and resulting aging processes.

## Technical Description

Raw data (acquired in SSRM) is read from an ASCI file; linear interpolation is carried out between individual resistivity maps (currently configured for four repeated scans over a given area, with equal x and y data density (i.e. 128×128, 256×256, etc.). Linear interpolation results in the creation of additional layers in between experimental scans with a given z-distance increment given in nanometers. A histogram generated from raw experimental data is plotted and printed prior to the generation of thresholded volumes. In the extraction of individual 3-D volumes corresponding to species of a given electronic resistivity, thresholds are input for their distinction from surrounding material. Lastly, the resistivity layers (experimentally obtained and interpolated) are depicted in 3-D over a given resistivity scale range. 

## Installation and Dependencies
(content under construction)

## Running the Code
(Content under conztruction)
