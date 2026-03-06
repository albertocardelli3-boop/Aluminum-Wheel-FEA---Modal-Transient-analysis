# Aluminum Wheel FEA - Modal Transient analysis
The objective of this report was to compare, by means
of ANSYS APDL, the results obtained using different
structural models of an 8-spoke wheel. Specifically, the
study concerned the behaviour under a pressure load
applied on the hub and constrained on the outer rim
for the static analysis; it then moved on to analysing the
dynamic behaviour by extracting resonance frequencies 
for selected deformation modes. The objective of
the study focuses on an estimate, as the mesh quality
varies, of the fitting of the static-analysis parameters
such as stiffness, stress, maximum displacement and
error, and of the dynamic-analysis parameters such as
resonance frequencies and participation factors

This project compares, through ANSYS APDL, the results obtained from different structural models of an 8-spoke wheel. The study investigates the wheel response under a pressure load applied on the hub and constraints imposed on the outer rim for the static analysis, and then examines its dynamic behaviour by extracting resonance frequencies and selected deformation modes. The comparison focuses on how mesh quality affects the accuracy of key static parameters, such as stiffness, stress, maximum displacement, and error, as well as dynamic parameters including resonance frequencies and modal participation factors.

This repository contains four ANSYS APDL scripts, each representing a different modelling approach:

This script creates a parametric 2D structural model of the wheel section and performs a static analysis under the prescribed boundary conditions and loading. It is used to evaluate displacement, stress distribution, and solution accuracy in a simplified planar representation.

This script generates a parametric 3D solid model of the wheel sector and performs a static structural analysis. It provides a more detailed representation of the stress and displacement fields, allowing comparison with the 2D static model.

This script builds a parametric 2D model for modal analysis and extracts natural frequencies and deformation modes. It is used to study the dynamic behaviour of the simplified wheel representation and to evaluate the influence of modelling assumptions on resonance prediction.

### 4. 3D Dynamic Analysis
This script creates a parametric 3D solid model for dynamic analysis, including modal extraction and transient/frequency-response evaluation. It provides the most complete representation of the wheel behaviour and is used to compare dynamic results with the simplified 2D approach.
