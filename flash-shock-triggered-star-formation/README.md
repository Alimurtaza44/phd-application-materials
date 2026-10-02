# Simulation of shock-triggered star formation in FLASH

Chapter of a group course project, Advanced Astrophysics, IIT Bombay · Instructor: Prof. Rahul Kashyap · Chapter written by Ali Murtaza

**PDF:** [Murtaza_FLASH_shock_triggered_star_formation.pdf](Murtaza_FLASH_shock_triggered_star_formation.pdf)

## Abstract

Supernova shocks may trigger star formation by compressing a molecular cloud until its Jeans mass falls below the cloud mass. I used the adaptive-mesh code FLASH to test this in two stages. In Phase I, a Mach-2 planar shock (γ = 5/3, ρ₂/ρ₁ = 2.28, P₂/P₁ = 4.75) ran into a pressure-balanced cloud with density contrast χ = 100, and the Jeans mass inside the cloud dropped as it was compressed. In Phase II, I replaced the planar shock with a spherical Sedov–Taylor blast wave and used near-isothermal gas (γ = 1.01) to mimic efficient cooling, motivated by the isothermal scaling M_J,2 = M_J,1 / M. A point-source explosion crashed the code, so I used a finite initial radius, the HLLC Riemann solver and first-order interpolation to keep the run stable. No proper cooling model was implemented in Phase II, so the Jeans-mass evolution there is not physically reliable.

## Scope

This repository contains only my chapter. The study's other chapters were written by teammates and are not included.

## Limitations

Radiative cooling is not modelled in Phase II. Implementing it is the main outstanding step.
