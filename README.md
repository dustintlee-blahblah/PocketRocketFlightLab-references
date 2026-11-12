# Pocket Rocket Flight Lab — reference library

Public-release reports behind the physics of [Pocket Rocket Flight Lab](https://github.com/dustintlee-blahblah/PocketRocketFlightLab),
kept here so anyone can check the app's methods against their sources. None of these files are part of the app or its
builds. What the app takes from each one is in the app's
[REFERENCES.md](https://github.com/dustintlee-blahblah/PocketRocketFlightLab/blob/main/REFERENCES.md),
[AERODYNAMICS.md](https://github.com/dustintlee-blahblah/PocketRocketFlightLab/blob/main/AERODYNAMICS.md) and
[VALIDATION.md](https://github.com/dustintlee-blahblah/PocketRocketFlightLab/blob/main/VALIDATION.md).

Every document here is a U.S. government report: NACA and NASA reports and a NASA contractor report from the NASA
Technical Reports Server (NTRS), Air Force and Army reports marked "Approved for public release; distribution
unlimited", and an Air University handbook. Works of the U.S. government are not subject to copyright in the United
States. Copyrighted sources the app uses (Hoerner's *Fluid-Dynamic Drag*, papers by Box, Bishop and Hunt, articles in
*High Power Rocketry*, and others) are cited in REFERENCES.md but not stored here.

## Aerodynamics: drag, lift and center of pressure

| File | Report | Source |
| --- | --- | --- |
| [NACA-TN-3819](reports/NACA-TN-3819_Love_1957_base-pressure-supersonic.pdf) | Love, *Base pressure at supersonic speeds on two-dimensional airfoils and on bodies of revolution with and without fins having turbulent boundary layers*, 1957 | [NTRS 19930084517](https://ntrs.nasa.gov/citations/19930084517) |
| [NACA-R-1307](reports/NACA-R-1307_Pitts-Nielsen-Kaattari_1959_wing-body-tail-lift-CP.pdf) | Pitts, Nielsen and Kaattari, *Lift and center of pressure of wing-body-tail combinations at subsonic, transonic, and supersonic speeds*, 1959 | [NTRS 19930091008](https://ntrs.nasa.gov/citations/19930091008) |
| [NASA-TR-R-100](reports/NASA-TR-R-100_Stoney_1961_zero-lift-drag-collection.pdf) | Stoney, *Collection of zero-lift drag data on bodies of revolution from free-flight investigations*, 1961 | NTRS |
| [NACA-RM-L53K17](reports/NACA-RM-L53K17_Stoney_1954_transonic-drag-eight-noses.pdf) | Stoney, *Transonic drag measurements of eight body-nose shapes*, 1954 | [NTRS 19930087953](https://ntrs.nasa.gov/citations/19930087953) |
| [NACA-TN-4370](reports/NACA-TN-4370_Yohner-Hansen_1958_laminar-boundary-layer-similarity-solutions.pdf) | Yohner and Hansen, *Some numerical solutions of similarity equations for three-dimensional laminar incompressible boundary-layer flows*, 1958 | [NTRS 19930085287](https://ntrs.nasa.gov/citations/19930085287) |
| [NASA-TM-84599](reports/NASA-TM-84599_Spearman_1983_wind-tunnels-sounding-rocket-aero.pdf) | Spearman, *The role of wind tunnels in predicting sounding rocket aerodynamics*, 1983 | [NTRS 19830009240](https://ntrs.nasa.gov/citations/19830009240) |
| [NACA-TN-4197](reports/NACA-TN-4197_Martin_1958_flutter-missile-fins.pdf) | Martin, *Summary of flutter experiences as a guide to the preliminary design of lifting surfaces on missiles*, 1958 | [NTRS 19930085030](https://ntrs.nasa.gov/citations/19930085030) |

## Missile DATCOM and the Army handbook

| File | Report | Source |
| --- | --- | --- |
| [AFWAL-TR-86-3091](reports/AFWAL-TR-86-3091_Vukelich_1988_Missile-DATCOM-vol1-final-report.pdf) | Vukelich, Stoy, Burns, Castillo and Moore, *Missile DATCOM, Volume I – Final report*, 1988 | [DTIC ADA211086](https://apps.dtic.mil/sti/citations/ADA211086) |
| [AFRL-VA-WP-TR-1998-3009](reports/AFRL-VA-WP-TR-1998-3009_Blake_1998_Missile-DATCOM-users-manual-1997.pdf) | Blake, *Missile DATCOM user's manual – 1997 FORTRAN 90 revision*, 1998 | DTIC |
| [AFRL-RB-WP-TR-2011-3071](reports/AFRL-RB-WP-TR-2011-3071_Rosema_2011_Missile-DATCOM-users-manual-2011.pdf) | Rosema, Doyle, Auman, Underwood and Blake, *Missile DATCOM user's manual – 2011 revision*, 2011 | DTIC |
| [AFRL-RQ-WP-TR-2014-0281](reports/AFRL-RQ-WP-TR-2014-0281_Rosema-Doyle_2014_Missile-DATCOM-users-manual-2014.pdf) | Rosema, Doyle and Blake, *Missile Data Compendium (DATCOM) user manual – 2014 revision*, 2014 | [DTIC AD1000581](https://apps.dtic.mil/sti/citations/AD1000581) |
| [MIL-HDBK-762](reports/MIL-HDBK-762_1990_design-of-aerodynamically-stabilized-free-rockets.pdf) | *Design of aerodynamically stabilized free rockets*, U.S. Army Missile Command, 1990 | Distribution statement A |

## Measured rockets (the app's check cases)

| File | Report | Source |
| --- | --- | --- |
| [NACA-RM-A53D02](reports/NACA-RM-A53D02_James-Carros_1953_fin-stabilized-body-M0.6-10.pdf) | James and Carros, *Experimental investigation of the zero-lift drag of a fin-stabilized body of revolution at Mach numbers from 0.6 to 10*, 1953 | NTRS |
| [NACA-RM-E50D28](reports/NACA-RM-E50D28_Esenwein_1950_RM-10-M1.49-1.98.pdf) | Esenwein, Obery and Schueller, *Aerodynamic characteristics of NACA RM-10 missile in 8- by 6-foot supersonic wind tunnel at Mach numbers from 1.49 to 1.98, II*, 1950 | [NTRS 19930086134](https://ntrs.nasa.gov/citations/19930086134) |
| [NACA-RM-L56G24](reports/NACA-RM-L56G24_Gillespie_1956_ballistic-missile-model-supersonic.pdf) | Gillespie, *Supersonic investigation of the lift, drag, static stability, and hinge-moment characteristics of a rocket-powered model of a ballistic-missile configuration*, 1956 | [NTRS 19690093428](https://ntrs.nasa.gov/citations/19690093428) |
| [NASA-TN-D-4013](reports/NASA-TN-D-4013_Ferris_1967_Arcas-M0.6-1.2.pdf) | Ferris, *Static stability investigation of a single-stage sounding rocket at Mach numbers from 0.60 to 1.20*, 1967 | NTRS |
| [NASA-TN-D-4014](reports/NASA-TN-D-4014_Babb-Fuller_1967_Arcas-M1.5-4.63.pdf) | Babb and Fuller, *Static stability investigation of a sounding-rocket vehicle at Mach numbers from 1.50 to 4.63*, 1967 | [NTRS 19670020031](https://ntrs.nasa.gov/citations/19670020031) |
| [NASA-TM-X-653](reports/NASA-TM-X-653_Jorgensen_1962_flares-vs-fins.pdf) | Jorgensen, Spahr and Hill, *Comparison of the effectiveness of flares with that of fins for stabilizing low-fineness-ratio bodies at Mach numbers from 0.6 to 5.8*, 1962 | [NTRS 19720065133](https://ntrs.nasa.gov/citations/19720065133) |
| [NASA-TM-X-677](reports/NASA-TM-X-677_Pierpont_1962_two-stage-fin-interference-transonic.pdf) | Pierpont, *Preliminary investigation of interference effects of multicoplanar fins on a two-stage rocket launch vehicle with winged spacecraft at transonic speeds*, 1962 | [NTRS 19660024055](https://ntrs.nasa.gov/citations/19660024055) |
| [NASA-TM-2005-213541](reports/NASA-TM-2005-213541_Allen_2005_strakes-tail-fins-M0.6-4.63.pdf) | Allen, *Aerodynamics of an axisymmetric missile concept having cruciform strakes and in-line tail fins from Mach 0.60 to 4.63*, 2005 (digital data: [NTRS 20050165156](https://ntrs.nasa.gov/citations/20050165156)) | [NTRS 20050160470](https://ntrs.nasa.gov/citations/20050160470) |
| [NASA-CR-75752](reports/NASA-CR-75752_Vought-AST-E1R-13319_1961_Aerobee-150A-performance.pdf) | Vought Astronautics, *Performance summary for the Aerobee 150A sounding rocket vehicle*, report AST/E1R-13319, 1961, under NASA contract NAS1-1013 | NTRS (CR-75752) |

## General

| File | Report | Source |
| --- | --- | --- |
| [AU-18, part 1](reports/AU-18_Air-University_1970_Space-Handbook-part-1.pdf), [part 2](reports/AU-18_Air-University_1970_Space-Handbook-part-2.pdf) | Air University, *Space Handbook* (AU-18), 1970 edition | U.S. Air Force publication; this scan carries rasaero.com's mark |
