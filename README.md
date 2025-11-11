

# mongird-etal_2025

**Energy Infrastructure Futures: A Multiscale Evaluation of Projected Power Plant Siting Across the Western Interconnection**

Kendall Mongird<sup>1\*</sup>, Kerem Ziya Akdemir<sup>1</sup>, Cameron Bracken<sup>1</sup>, Casey D. Burleyson<sup>1</sup>, Travis Thurber<sup>1</sup>, Chris R. Vernon<sup>1</sup>, Mengqi Zhao<sup>1</sup>, Jennie S. Rice<sup>1</sup>

<sup>1 </sup>Pacific Northwest National Laboratory, Richland, WA, USA.

\* corresponding author:  kendall.mongird@pnnl.gov

## Abstract
The US Western Interconnection is facing unprecedented challenges in the form of less predictable peak demand, increasingly diverse generating resources, and fast-growing loads due to the onset of artificial intelligence, hyperscale computing, and electrification. Projecting where future generation may be developed is critical to maintaining a robust and resilient electric grid under this mounting uncertainty and variability. Using an integrated multisectoral, multiscale modeling framework that links a human-Earth systems model, an hourly load model, a geospatial power plant siting model, and an hourly grid operations model, we evaluate the power plant landscape evolution under eight alternative futures between 2020 and 2055. These futures represent a wide but plausible range of atmospheric conditions, emissions constraints, and economic, technological, and population growth assumptions. We find that local-level development can vary substantially both by generation type and capacity buildout across these futures. Specific regions of the Western Interconnection are projected to see large amounts of capacity development regardless of the future scenario. We additionally determine that projected power plant locations are more heavily influenced by the cost to interconnect to the electric grid than the locational energy value. 

## Journal reference
to be filled in upon publication

## Data reference

| Dataset | Type | Repository Link | DOI |
| --- | --- | --- |--- |
| CERF: IM3 Projected Western US Power Plant Locations | Input Data | https://data.msdlive.org/records/62fpt-0jr75 | https://doi.org/10.57931/2479527 |
| Energy Infrastructure Futures: A Multiscale Evaluation of Projected Power Plant Siting Across the Western Interconnection |  Input and Output Data | | https://doi.org/10.57931/2998526 | 

## Contributing modeling software
| Model | Version | Model Repository Link | DOI of Specific Version |
| --- | --- | --- | --- |
| GO | v0.1.0 | https://github.com/IMMM-SFA/go | https://doi.org/10.5281/zenodo.15399795 |
| TEP | v1.1.0 | https://github.com/keremakdemir/Transmission_Expansion_Planner | https://doi.org/10.5281/zenodo.15413081 |
| GCAM-USA | v5.3 | https://github.com/JGCRI/gcam-core | https://doi.org/10.5281/zenodo.3908600 |
| CERF | v2.4.0 | https://github.com/IMMM-SFA/cerf | https://doi.org/10.5281/zenodo.13830460 |
| TELL | v1.1.0 | https://github.com/IMMM-SFA/tell | https://doi.org/10.5281/zenodo.8264217 |
| reV | v0.7.0 | https://github.com/NREL/reV | https://doi.org/10.5281/zenodo.7301491 |


## Reproduce my analysis and figures
Use the scripts/files found in the `scripts` directory to reproduce the analysis and figures presented in this publication. 
- Please check and make sure that all the necessary packages listed in `requirements.txt` are installed in your local Python environment.

Run the following scripts to complete the analysis and prepare figures:

| Script Name | Description | 
| --- | --- | 
| `prepare_data.py` | Script to organize data for analysis and plotting |
| `run_analysis.py` | Script to run the random forest classifier and SHAP analysis |
| `plot_fig_3.py` | Script to plot Fig 3, SI-1, and SI-2 |
| `plot_fig_4.py` | Script to plot Fig 4 and SI-3 |
| `plot_fig_5.py` | Script to plot Fig 5 |
| `plot_fig_6.py` | Script to plot Fig 6 and SI-4 |
| `plot_fig_7.py` | Script to plot Fig 7 and SI-5-12 |

