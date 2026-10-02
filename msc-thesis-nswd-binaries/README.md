# Neutron star–white dwarf (NS–WD) binaries as multi-messenger sources

M.Sc. thesis, IIT Bombay, April 2026 · Supervisor: Prof. Rahul Kashyap · Sole author

**PDF:** [Murtaza_MSc_thesis_NSWD_binaries.pdf](Murtaza_MSc_thesis_NSWD_binaries.pdf)

## Abstract

Neutron star–white dwarf binaries are expected to emit gravitational waves in the milli- to deci-hertz band shortly before they merge, and their mergers may power transients, which makes them targets for multi-messenger astronomy. This thesis builds a population-synthesis pipeline to estimate how often such systems form and merge. Early runs with the detailed stellar code MESA showed that it could not carry a binary through a supernova to a bound NS–WD system on its own, so I moved to the rapid binary evolution code binary_c. Primary masses were drawn from a Kroupa initial mass function with uniformly distributed mass ratios, and orbital periods were scaled to the zero-age stellar radii. About one million binaries were evolved on 48 cores of IIT Bombay's PARAM Rudra cluster. Merger delay times were convolved with the cosmic star-formation history of Wilkins et al. (2019), following Dominik et al. (2013). The local merger-rate density is about 79 Gpc⁻³ yr⁻¹ for binary neutron stars (7 mergers), compatible with the GWTC-4.0 range of 7.6–250 Gpc⁻³ yr⁻¹, and about 166 Gpc⁻³ yr⁻¹ for NS–WD binaries (10 mergers). With so few mergers the statistical uncertainties are large, and extending the run to larger populations is the next step.

## My role

I wrote the initial-condition sampler (Kroupa IMF by vectorised rejection sampling, mass ratios, separations), set up and ran binary_c and binary_c-python locally and on the cluster, wrote the analysis pipeline that identifies NS–WD systems and computes delay times, and carried out the merger-rate conversion.

## Limitations

The rates rest on 7 binary-neutron-star and 10 NS–WD mergers, so Poisson errors alone are of order 30–40 %. Results use a single binary-evolution model and a single star-formation history.
