# Aircraft Flight Dynamics Simulation in MATLAB

This repository contains a MATLAB aircraft flight dynamics term project focused on trim calculation, nonlinear aircraft motion simulation, and longitudinal/lateral stability analysis.

The project was developed as an educational engineering simulation exercise. It uses aerodynamic force and moment models, atmospheric properties from the US Standard Atmosphere 1976 model, numerical integration with ode45, and eigenvalue-based stability analysis.

## Project Overview

The MATLAB script explores aircraft flight dynamics through several connected stages:

- Aircraft parameter definition
- Aerodynamic force and moment calculation
- Trim condition setup
- Wing-level steady-flight calculation
- Nonlinear aircraft motion simulation
- Response to longitudinal and lateral control inputs
- Linearization and stability analysis
- Longitudinal and lateral eigenvalue evaluation

The goal of the project is to understand how aircraft states evolve under aerodynamic forces, moments, control inputs, and initial conditions.

## Repository Structure

- src/aircraft_flight_dynamics_project.m: Main MATLAB script for trim, simulation, and stability analysis
- src/f_atmos_US76.m: Helper function for the US Standard Atmosphere 1976 model
- docs/original_project_code.pdf: Original exported project/code document
- original/ReadME.txt: Original short project note
- README.md: Repository documentation
- .gitignore: Ignore rules for temporary MATLAB and system files

## Main Features

- Aircraft mass, inertia, geometry, and aerodynamic coefficient definition
- Standard atmosphere calculation as a function of altitude
- Trim condition analysis
- Nonlinear dynamic simulation using MATLAB ode45
- Control input response simulation
- Longitudinal and lateral stability analysis
- Eigenvalue-based interpretation of aircraft modes

## How to Run

Open MATLAB and set the repository root as the current working directory.

Then run:

cd src
aircraft_flight_dynamics_project

The script calls f_atmos_US76.m to calculate atmospheric properties and then performs the flight dynamics calculations and simulations.

## Requirements

- MATLAB
- Basic MATLAB plotting and numerical integration functionality
- No external toolbox requirement is specified in the original project files

## Notes

This is an educational term project. It is intended to demonstrate core concepts in aircraft flight dynamics, numerical simulation, trim analysis, and stability evaluation rather than serve as a production-level aircraft simulation package.

## Possible Improvements

- Refactor the main script into smaller reusable MATLAB functions
- Add clearer configuration sections for aircraft parameters and control inputs
- Export simulation figures into a figures folder
- Add comments explaining each aircraft state and coefficient
- Add comparison between nonlinear and linearized responses
- Add a short technical report summarizing trim and stability results

## Author

Doga Ozbek
