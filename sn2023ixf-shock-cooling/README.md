# Finding Azatoth: progenitor of SN 2023ixf from GROWTH-India Telescope light curves

Course project (PH-556), IIT Bombay, autumn 2025 · Observational astronomy course of Prof. Varun Bhalerao · Team project; report written by Ali Murtaza

**PDF:** [Murtaza_SN2023ixf_shock_cooling_report.pdf](Murtaza_SN2023ixf_shock_cooling_report.pdf)

## Abstract

SN 2023ixf in M101 is one of the nearest core-collapse supernovae of the past 25 years. We performed aperture photometry on GROWTH-India Telescope images in the g, r and i bands over roughly ten days after discovery, calibrating each frame against five SDSS stars and taking the median zero point. We then fitted the shock-cooling model of Morag, Sapir and Waxman (2023) to the multi-band light curves with the emcee sampler, using the lightcurve_fitting package. The shock velocity, (6.6 ± 1.3) × 10³ km s⁻¹, agrees with the published value, and the explosion epoch lies within about 0.3 days of it. The progenitor radius, 144 (+57/−43) R☉, and the envelope mass, 1.0 (+0.5/−0.3) M☉, are well below the published 410 ± 10 R☉ and about 5 M☉. We attribute this to our single epoch per night and the lack of ultraviolet data, where the early emission peaks. Blackbody fits to the spectral energy distribution show the temperature falling from about 18 kK to 10 kK while the radius grows from about 2000 to 7000 R☉, and the g−r and r−i colours redden over the same interval.

## Team and my role

Four students split the work by band. I did the i-band photometry and the zero-point calibration, and wrote this report. Jyoti did the r band, Abhinav the g band, and Hitesh worked on setting up the model fit. When our calibrations disagreed because Gaia has no i band, we recalibrated every band against SDSS.

## Limitations

The model can only use the first few days of data, our cadence was one point per night, and we had no ultraviolet coverage. The radius and envelope-mass results should be read as a test of the method on sparse data, not as measurements.
