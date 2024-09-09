# Bobkov Look-Up Table for Critical Heat Flux (CHF)

This MATLAB function calculates the critical heat flux (CHF) based on the Bobkov Look-Up Table (LUT), as described in the paper:

> Bobkov, V. P., et al. "A modified table for calculating critical heat fluxes in assemblies of triangularly packed fuel rods." *Thermal Engineering* 58 (2011): 317-324.

## Features

- Provides an interpolated CHF value for given inputs of mass flux, thermodynamic equilibrium quality, and pressure.
- Uses a pre-defined LUT for interpolation.

## Inputs

The function accepts the following inputs:

- `g`: Mass flux (kg/m²·s)
- `x`: Thermodynamic equilibrium quality (-)
- `p`: Pressure (kPa)

## Outputs

- `chf`: Critical heat flux (kW/m²)

## Usage

```matlab
chf = bobkov3(g, x, p);
