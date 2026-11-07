# Petrophysical & Geomechanical Evaluation Tool
### Formation Evaluation | Rock Physics | Fluid Substitution | Seismic Integration

**Author:** MATTEO MIRABILIO  
**Project:** CSS – Petrophysical & Geomechanical Assessment  
**Domain:** Reservoir Characterization | Petrophysics | Geomechanics | Seismic Studies

---

## 1. Repository Overview

The **Petrophysical & Geomechanical Evaluation Tool** is a Python-based research and engineering application designed to perform integrated formation evaluation, petrophysical analysis and geomechanical characterization.

The tool combines well-log QA/QC, petrophysical interpretation, rock physics modelling and fluid substitution workflows to support reservoir characterization and seismic studies.

Its primary objective is to transform raw well-log measurements into reliable formation properties, elastic parameters and geomechanical indicators, providing an integrated framework for evaluating subsurface formations within CSS projects.

## 2. Main Objectives

- Perform quality control and validation of wireline and LWD logs.
- Evaluate lithology, porosity, shale volume and fluid saturation.
- Estimate formation permeability and reservoir properties.
- Calculate dynamic elastic properties from sonic and density logs.
- Estimate geomechanical parameters and mechanical rock behaviour.
- Perform rock physics modelling and fluid substitution.
- Evaluate the influence of fluid properties on seismic velocities and amplitudes.
- Generate petrophysical and geomechanical outputs for seismic integration.

## 3. Main Modules

### Module 01 – Well Log QA/QC
- LAS data import and validation.
- Depth matching and curve consistency.
- Missing values and anomalous measurements detection.
- Sonic and density log quality assessment.
- Caliper and borehole-condition evaluation.
- Automated QC flags and reporting.

### Module 02 – Petrophysical Formation Evaluation
- Gamma Ray and shale volume estimation.
- Total and effective porosity calculation.
- Water saturation estimation (Archie).
- Lithology and mineral identification.
- Formation permeability estimation.
- Reservoir interval identification and net-to-gross evaluation.

### Module 03 – Rock Physics Modelling
- P-wave and S-wave velocity analysis.
- Bulk and shear modulus calculation.
- Dynamic Young's modulus.
- Poisson's ratio.
- Bulk density and acoustic impedance.
- Vp/Vs ratio and elastic parameter crossplots.

### Module 04 – Fluid Substitution
Implementation of fluid substitution workflows based on Gassmann theory.

- Initial reservoir fluid properties.
- Brine, oil and gas scenarios.
- Fluid bulk modulus estimation.
- Saturation scenarios.
- Predicted Vp and Vs variations.
- Density and acoustic impedance variations.
- Synthetic seismic response comparison.

### Module 05 – Geomechanical Assessment
- Dynamic elastic properties.
- Static elastic properties estimation.
- Unconfined Compressive Strength (UCS) estimation.
- Overburden pressure calculation.
- Pore pressure evaluation.
- Minimum and maximum horizontal stress estimation.
- Fracture gradient and formation integrity indicators.
- Mechanical stratigraphy and formation stability assessment.

### Module 06 – Seismic Integration
- Petrophysical-to-elastic property integration.
- Synthetic seismic modelling inputs.
- Acoustic impedance modelling.
- Fluid sensitivity analysis.
- Seismic response comparison between saturation scenarios.
- Formation-scale elastic property interpretation.

## 4. Proposed Workflow

```text
WELL LOG DATA (LAS / DLIS)
          |
          v
    LOG QA/QC
          |
          v
 FORMATION EVALUATION
          |
          v
 PETROPHYSICAL MODEL
          |
          v
   ROCK PHYSICS
          |
          v
  FLUID SUBSTITUTION
          |
          v
 GEOMECHANICAL MODEL
          |
          v
 SEISMIC INTEGRATION
          |
          v
 FINAL RESULTS & REPORT
```

## 5. Expected Outputs

| Output | Description |
|---|---|
| Log QC Report | Curve quality and validation |
| Petrophysical Report | Porosity, Vsh, Sw and lithology |
| Rock Physics Report | Vp, Vs, density and elastic moduli |
| Fluid Substitution | Reservoir fluid sensitivity scenarios |
| Geomechanical Report | UCS, stress and elastic properties |
| Seismic Parameters | Acoustic impedance and seismic inputs |
| Final Report | Integrated formation evaluation |

## 6. Technology Stack

- Python 3.x
- NumPy – Numerical calculations
- Pandas – Well-log data management
- Matplotlib – Scientific visualization
- Plotly – Interactive crossplots and dashboards
- LAS / CSV / TXT – Input data formats

## 7. Scientific Methodology

The application integrates established petrophysical and rock physics methodologies, including:

- Archie water saturation model.
- Wyllie time-average and sonic porosity approaches.
- Density-neutron porosity interpretation.
- Gassmann fluid substitution.
- Isotropic elastic theory.
- Dynamic elastic moduli estimation.
- Empirical UCS correlations.
- Effective stress and poroelastic principles.

Model assumptions, calibration requirements and data-quality limitations should be documented for each interpretation.

## 8. Project Applications

The tool is designed to support:

- CSS reservoir characterization.
- Formation evaluation and reservoir quality assessment.
- Integrated petrophysical and geomechanical studies.
- Seismic attribute interpretation.
- Fluid sensitivity and 4D seismic feasibility studies.
- Reservoir monitoring and development planning.
- Well-log-based seismic model calibration.

## 9. Project Philosophy

**From Well Logs to Seismic Intelligence.**

The objective is to establish an integrated analytical workflow connecting formation properties, rock mechanical behaviour and fluid-dependent elastic responses.

By combining petrophysics, geomechanics and rock physics, the tool provides a practical framework for improving subsurface characterization and supporting seismic interpretation.

---

**Author:** MATTEO MIRABILIO  
**Repository:** Petrophysical & Geomechanical Evaluation Tool  
**Version:** 1.0 – Research & Engineering Framework
