---
layout: default
title: Documentation - CE-QUAL-W2
permalink: /documentation/
---

# CE-QUAL-W2 Documentation

## User Manual Version 4.5

The CE-QUAL-W2 User Manual is organized into five comprehensive parts covering all aspects of model theory, application, and utilities. Each part is available as a PDF download.

### Part 1: Introduction
[Download PDF](documentation/W2manual45_Part1_Intro_rev6.pdf) (1.6 MB)

- Model overview and capabilities
- Getting started with CE-QUAL-W2
- Installation and system requirements
- Basic concepts and terminology
- Model history and development

### Part 2: Theory
[Download PDF](documentation/W2manual45_Part2_Theory_rev6.pdf) (4.8 MB)

- Governing equations
- Numerical solution techniques
- Hydrodynamic algorithms
- Water quality kinetics
- Heat exchange and ice cover
- Theoretical basis for all model processes

### Part 3: Input/Output Files
[Download PDF](documentation/W2manual45_Part3_InputOutputFiles_rev6.pdf) (15 MB)

- Control file structure and parameters
- Bathymetry file setup
- Meteorological data requirements
- Initial conditions
- Boundary conditions
- Water quality parameters
- Output file formats
- Detailed descriptions of all input variables

### Part 4: Model Examples
[Download PDF](documentation/W2manual45_Part4_ModelExamples_rev3.pdf) (8.5 MB)

- Step-by-step tutorials
- Example applications:
  - Reservoir stratification
  - River temperature modeling
  - Lake eutrophication
  - Estuary salinity
- Test cases with solutions
- Troubleshooting guide

### Part 5: Model Utilities
[Download PDF](documentation/W2manual45_Part5_ModelUtilities_rev6.pdf) (3.7 MB)

- Pre-processors for input file generation
- Post-processors for output analysis
- Graphical user interfaces
- Visualization tools
- Bathymetry tools
- Calibration utilities
- Data conversion programs

---

## Quick Reference Guides

### Model Setup Checklist
1. Define model domain and segmentation
2. Prepare bathymetry file
3. Set up control file parameters
4. Prepare meteorological data
5. Define initial conditions
6. Set boundary conditions
7. Configure water quality (if needed)
8. Run model and review outputs

### Common Applications

| Application | Key Processes | Required Data |
|------------|--------------|---------------|
| **Reservoir Stratification** | Temperature, density, mixing | Bathymetry, meteorology, inflows |
| **River Temperature** | Heat exchange, advection | Flow, meteorology, shading |
| **Eutrophication** | Nutrients, algae, DO | Loads, light, temperature |
| **Selective Withdrawal** | Stratification, outlet dynamics | Operations, temperature profiles |
| **Water Age/Residence Time** | Transport, mixing | Flows, bathymetry |

### File Naming Conventions

- **Control file**: `w2_con.npt`
- **Bathymetry**: `bth.npt`
- **Meteorology**: `met.npt`
- **Snapshot output**: `snp.opt`
- **Time series**: `tsr.opt`
- **Profile plots**: `pro.opt`

---

## Additional Resources

### Training Materials
- [Workshop Presentations](/publications/)

### Technical Support
- [Frequently Asked Questions](/support/#faq)

### Related Publications
- [Peer-reviewed Papers](/publications/)
- [Technical Reports](/publications/#reports)
- [Conference Proceedings](/publications/#conferences)

---

*Last updated: August 2025*