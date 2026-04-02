# VTCS Diagnostic Microscope

## Overview
The VTCS Diagnostic Microscope is a data analysis and two-phase decomposition tool designed to evaluate complex, non-linear growth systems. It was originally built to analyze cosmological expansion datasets, specifically to identify phase shifts (Transmutations) and capacity limits (Plateaus) in observational data.

Standard linear or infinite-growth models often fail when systems reach saturation. The VTCS Microscope uses a **Logistic Bridge** framework to decompose data into two distinct phases ($S_1$ and $S_2$), allowing researchers to pinpoint the exact moment a system shifts gears.

## Key Features
* **Two-Phase Decomposition:** Separates data into an initial Character phase ($S_1$) and a secondary Tension phase ($S_2$).
* **Transmutation Identification ($\tau$):** Automatically calculates the exact coordinate where the system transitions between phases.
* **Capacity Enforcement:** Models natural system limits (plateaus) rather than assuming infinite runaway growth.
* **Archetype Classification:** Categorizes the behavior of the dataset (e.g., "Binary Cascade") based on phase dominance and trajectory.

## The Hubble Tension Context
This tool was utilized to analyze the Pantheon+ Supernova dataset alongside the standard $\Lambda$CDM model. By applying the microscope to the data, it demonstrated that the "Hubble Tension" is not a failure of the universe, but a measurable **Binary Cascade** transitioning at a specific $\tau$ coordinate. 

Read the full analysis and findings on Zenodo: [Insert Zenodo DOI Link Here]

## Data Input Format
The Microscope accepts `.csv` files formatted with `Time` and `Strain` (or normalized step/value equivalents).

Example:
Time,Strain
0,0.000
10,0.165
20,0.262
...

## Usage
[Insert basic installation or run instructions here, e.g., `npm start` or `python main.py`]
