---
layout: default
title: Examples - CE-QUAL-W2
permalink: /examples/
---

# Example Applications

## Tutorial Examples

These examples are designed to help new users learn CE-QUAL-W2 step by step.

### 1. Simple Reservoir
**Objective**: Learn basic model setup and thermal stratification

- Idealized rectangular reservoir
- Seasonal stratification dynamics
- Basic inflow/outflow configuration
- Focus on temperature modeling

[Download Files](#) | [View Tutorial](documentation/W2manual45_Part4_ModelExamples_rev3.pdf)

### 2. River Temperature
**Objective**: Model stream temperature with shading

- Single branch river system
- Point and non-point heat sources
- Riparian shading effects
- Comparison with field data

[Download Files](#) | [View Tutorial](documentation/W2manual45_Part4_ModelExamples_rev3.pdf)

### 3. Lake Eutrophication
**Objective**: Simulate nutrient cycling and algae dynamics

- Nutrients (N, P, Si)
- Multiple algae groups
- Dissolved oxygen dynamics
- Sediment oxygen demand

[Download Files](#) | [View Tutorial](documentation/W2manual45_Part4_ModelExamples_rev3.pdf)

---

## Real-World Applications

### DeGray Reservoir, Arkansas
<div style="background: #f5f5f5; padding: 1em; margin: 1em 0;">
<strong>Application</strong>: Selective withdrawal optimization<br>
<strong>Key Features</strong>: Multiple outlets, water quality management<br>
<strong>Period</strong>: 1985-1990<br>
<strong>Processes</strong>: Stratification, selective withdrawal, water quality
</div>

The DeGray Reservoir model demonstrates:
- Complex bathymetry setup
- Multiple withdrawal ports
- Temperature and DO management
- Model calibration procedures

[Download Model Files](#) | [View Report](#)

### Columbia River System
<div style="background: #f5f5f5; padding: 1em; margin: 1em 0;">
<strong>Application</strong>: System-wide temperature TMDL<br>
<strong>Key Features</strong>: Multiple reservoirs and river reaches<br>
<strong>Period</strong>: 2000-2010<br>
<strong>Processes</strong>: Temperature, TDG, flow regulation
</div>

This comprehensive model includes:
- Multiple dams and reservoirs
- Run-of-river and storage projects
- Total dissolved gas modeling
- Fish habitat assessment

[Download Model Files](#) | [View Report](#)

### Tenkiller Ferry Lake, Oklahoma
<div style="background: #f5f5f5; padding: 1em; margin: 1em 0;">
<strong>Application</strong>: Eutrophication and water quality<br>
<strong>Key Features</strong>: Nutrient loading, algae blooms<br>
<strong>Period</strong>: 1990-1995<br>
<strong>Processes</strong>: Nutrients, algae, DO, pH
</div>

Model highlights:
- Watershed nutrient loading
- Multiple algae groups
- Taste and odor compounds
- Management scenario testing

[Download Model Files](#) | [View Report](#)

---

## Benchmark Tests

### Test Case 1: Density Current
Tests model's ability to simulate density-driven flows

- Lock exchange problem
- Comparison with analytical solution
- Grid sensitivity analysis

[Download](#) | [Results](#)

### Test Case 2: Wind Setup
Validates wind-driven circulation

- Rectangular basin
- Uniform wind stress
- Comparison with theory

[Download](#) | [Results](#)

### Test Case 3: Internal Seiche
Tests internal wave dynamics

- Two-layer stratification
- Seiche period validation
- Energy dissipation

[Download](#) | [Results](#)

---

## Model Setup Templates

### Reservoir Template
Complete setup for typical reservoir application:
- Control file with common parameters
- Example bathymetry file
- Meteorological data format
- Initial conditions setup

[Download Template](#)

### River Template
Ready-to-modify river model:
- Single branch configuration
- Shade file example
- Temperature boundary conditions
- Hydraulic structures

[Download Template](#)

### Lake Template
Lake water quality model framework:
- Multiple basins
- Water quality constituents
- Sediment interactions
- Wind sheltering

[Download Template](#)

---

## Visualization Examples

### Animation Gallery

| Preview | Description | Download |
|---------|-------------|----------|
| ![Temperature Animation](assets/images/temp_anim_thumb.png) | Seasonal stratification cycle | [MP4](#) |
| ![Velocity Vectors](assets/images/velocity_thumb.png) | Flow patterns during turnover | [MP4](#) |
| ![Water Quality](assets/images/wq_thumb.png) | Algae bloom development | [MP4](#) |

### Output Processing Scripts

**Python Scripts**
- Temperature contour plots
- Time series extraction
- Profile comparisons
- Animation generation

[Download Python Package](#)

**MATLAB Scripts**
- W2 output reader
- Calibration plots
- Statistical analysis
- 3D visualizations

[Download MATLAB Toolbox](#)

---

## Contributing Examples

Have you developed an interesting CE-QUAL-W2 application? We welcome contributions to our example library!

### Submission Guidelines
1. Provide complete input files
2. Include brief description and objectives
3. Document any modifications or special features
4. Include sample outputs if possible

### Benefits of Contributing
- Help other users learn from your experience
- Showcase your modeling work
- Contribute to the CE-QUAL-W2 community
- Get feedback from other users

[Submit an Example](/support/#contact)

---

## Additional Resources

- [User Manual Examples Section](documentation/W2manual45_Part4_ModelExamples_rev3.pdf)
- [Training Workshop Materials](/publications/)
- [User Forum](/support/#forum)

---

*Note: Some download links are placeholders and will be activated as content is uploaded to the repository.*