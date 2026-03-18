# Initial structures for E2 adsorption on SWCNT

This repository contains the input files used to prepare the initial molecular structure for a Bayesian optimization–based structure search of adsorption configurations.

The broader goal of this work is to investigate the adsorption of 17-β-estradiol (E2) on a single-walled carbon nanotube (SWCNT) for electrochemical sensor applications.

## Files in this repository

### `geometry_estradiol.in`
Geometry input file for the E2 molecule. This structure is used as the starting point for further alignment and preparation steps in the adsorption structure search workflow. :contentReference[oaicite:0]{index=0}

### `estradiol_aling_byhand.ipynb`
Jupyter notebook used to align the E2 molecule manually after relaxation. The alignment is needed so that the adsorption configurations are built consistently and with the correct molecular orientation.

## Background

The initial E2 structure was re-relaxed using updated van der Waals corrections. Because this relaxation changed the molecular geometry and center of mass, the molecule had to be aligned again before generating adsorption configurations.

The files in this repository are therefore part of the preprocessing workflow used to create reliable initial structures for Bayesian optimization–based adsorption simulations.

## Purpose

These files support:
- preparation of the initial E2 structure
- alignment of the relaxed molecule
- generation of starting configurations for adsorption studies on SWCNT

## Application

The prepared structures are intended for adsorption simulations that study E2 adsorption on SWCNT surfaces in the context of electrochemical sensing.
