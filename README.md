# aircraft-fuselage-structural-fatigue-analysis
Aircraft fuselage structural and fatigue analysis using Excel, covering cross-section sizing, bending and shear stress, S-N and strain-life fatigue analysis and crack growth

Structural analysis of an aircraft fuselage cockpit section, carried out as part of an aerospace engineering design project.

The analysis investigates the structural behaviour of the fuselage under cruise and manoeuvre loading, followed by fatigue and crack growth assessments.

## Analysis Covered

- Fuselage cross-section idealisation using a boom-stringer representation
- Skin thickness and stringer sizing
- Second moment of area and stiffness sensitivity
- Shear force and bending moment distributions
- Direct bending stress and shear stress analysis
- Combined stress, principal stress and Von Mises stress
- Manoeuvre loading and structural assessment
- Static displacement using the strain energy method
- Skin thickness parametric study
- Gust load and fatigue cycle analysis
- S-N fatigue analysis using the Morrow mean stress correction
- Strain-life fatigue analysis and Neuber correction
- Crack growth analysis using Paris Law
- Mean stress correction using the Walker equation
- Crack growth life and critical crack length calculations
- Parametric studies investigating the effects of skin thickness and hole size

## Key Results

The analysis identified a maximum combined stress of approximately **190 MPa** under the ultimate manoeuvre loading case, below the **325 MPa yield strength** used for the aluminium alloy 2024-T351 material.

The selected baseline configuration used:

- **Skin thickness:** 0.2 mm
- **Stringer area:** 50 mm²
- **Material:** Aluminium alloy 2024-T351

The crack growth analysis predicted a life of approximately **1554 years** from an initial 0.1 mm defect to the calculated critical crack length under the analysed loading conditions.

Parametric studies were also used to investigate how changes in skin thickness and fastener-hole size influence structural stiffness, stress and crack growth life.

## Files

### `Fuselage Structural and Fatigue Analysis.xlsx`

The main Excel workbook contains the complete analysis. The calculations are organised across multiple linked worksheets, with outputs and graphs generated from the underlying calculations.

The workbook includes the structural sizing, stress analysis, fatigue calculations, crack growth calculations and associated parametric studies.

## Visual Results

The repository includes selected graphs from the analysis showing:

- Fuselage cross-section and structural idealisation
- Stress and stiffness parametric studies
- Shear force and bending moment distributions
- S-N fatigue behaviour
- Strain-life analysis
- Crack growth behaviour

## Software

- Microsoft Excel
- Engineering calculations and analytical methods
- CS-23 structural loading principles
