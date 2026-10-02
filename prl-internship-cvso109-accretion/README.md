# Accretion rate of the T Tauri star CVSO 109 from automated emission-line fitting

Summer internship report, Physical Research Laboratory (PRL), Ahmedabad, 2 June – 30 July 2026 · Supervisor: Prof. Manash Samal · Sole author

**PDF:** [Murtaza_PRL_internship_report_CVSO109.pdf](Murtaza_PRL_internship_report_CVSO109.pdf)

## Abstract

The mass accretion rate of a young star can be estimated from the luminosity of its emission lines, but measuring many lines across many epochs by hand is slow. I used the Python package star-melt to automate line detection, continuum subtraction and multi-component Gaussian fitting on multi-epoch VLT/UVES spectra of the classical T Tauri star CVSO 109 (Haro 5-66, 440 pc). Stellar parameters (0.5 M☉, 2.66 R☉, A_V = 0.01) were taken from Maucó et al. (2018). After correcting line wavelengths for the systemic radial velocity, I converted the fitted equivalent widths and continuum fluxes into line luminosities, and then into accretion luminosities and mass accretion rates using the empirical relations of Alcalá et al. (2017), for Ca II K, Hδ, He I 5876 Å and Hα. The package's integrated fluxes lost their units after an internal rescaling, so I measured line flux as the absolute equivalent width times the local continuum instead. The resulting rates range from about 2 × 10⁻¹⁰ to 2 × 10⁻⁸ M☉ yr⁻¹, with Hα giving about 4 × 10⁻⁹ M☉ yr⁻¹, comparable to the literature value of about 6.7 × 10⁻⁹ M☉ yr⁻¹. Profile analysis of broad and redshifted components is left for future work.

## My role

I carried out the full analysis: line identification against the NIST database, Gaussian fitting, flux calibration, dereddening, the modified flux measurement, and the accretion-rate calculation. The report also contains a literature review of accretion on young stars and of simulation methods.

## Limitations

Rates from different lines and epochs differ by more than an order of magnitude, and only a small number of line–epoch combinations were fitted. Only UVES data were analysed.
