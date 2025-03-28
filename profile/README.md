The objective of _METAdata for CLImate Products_ (METACLIP) is to encode the end-to-end provenance required to ensure the traceability and reproducibility of climate products, particularly in the climate change domain including global and regional climate projections. 

The core [METACLIP ontologies](https://github.com/metaclip/ontologies) extend the [W3C PROV](https://www.w3.org/TR/2013/REC-prov-dm-20130430/) data model standard to describe the different activities, agents and transformations involved in the product generation workflow, from input data, to data processing and to final product generation (e.g. climate change maps, with associated uncertainty). METACLIP builds on the existing controlled vocabularies of intiatives such as CMIP (e.g. [CMIP6](https://github.com/metaclip/CMIP6)) and CORDEX (work in progess). 

METACLIP was used to define the provenance of the [IPCC AR6 Atlas](http://interactive-atlas.ipcc.ch) (see details [here](https://github.com/metaclip/IPCC-AR6-Atlas)). 

**Illustrative example:** Provenance for a subset from CMIP6 corresponding to daily maximum temperature from a single model (EC-Earth3-VEG-LR) for a particular run (r1i1p1f1) for a single scenario SSP370 ([.jsonld](https://github.com/metaclip/.github/blob/main/profile/METACLIP-CMIP6-demo.jsonld) file; [interactive visualization](https://json-ld.org/playground/#startTab=tab-expanded&json-ld=https%3A%2F%2Fraw.githubus[…]IP6-METACLIP-Provenance_Demo_daily-tasmax_ssp3_7_0.jsonld) in JSON-LD Playground).

![METACLIP CMIP6 example](https://github.com/metaclip/.github/blob/main/profile/METACLIP-CMIP6-demo.png)
 
More info in the [METACLIP paper](https://doi.org/10.1016/j.envsoft.2019.07.005) and the [AGU24 presentation](https://agu24.ipostersessions.com/Default.aspx?s=50-0B-A2-D6-50-24-05-87-67-9B-4A-09-A3-FE-B3-3D) (video included). 
