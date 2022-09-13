# Analysis of Physical experiment data to explore washover formation in non-built & built environments

This repository includes code for organising & plotting (some of) the experimental results

Preprint:
[![Earth ArXiv Preprint
DOI](https://img.shields.io/badge/%F0%9F%8C%8D%F0%9F%8C%8F%F0%9F%8C%8E%20EarthArXiv-doi.org%2F10.31223%2FX5JH1X-%23FF7F2A)](https://doi.org/10.31223/X5JH1X)

Code DOI: 
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.6641396.svg)](https://doi.org/10.5281/zenodo.6641396)



## Description of the experiment

To generate a dataset of model washover morphology for comparison against remotely sensed observations at the field scale, we conducted a physical experiment that examined under controlled conditions how washover morphology manifest in non-built and built settings under the same forcing.

Here, we followed the premise of a previous physical experiment – smaller in scale by an order of magnitude – by Lazarus (2016), which produced barrier overwash morphology arrayed along a spatially extended, topographically uniform, non-built domain. We used an experimental design that is likewise spatially extended in the alongshore dimension, thus generating in each trial multiple washover features (n ~ 10^1) and a distribution of morphometric characteristics even under constant forcing.

This experiment ran in the Total Environment Simulator (TES) at the University of Hull (UK). The TES is a 6 x 10 m modular basin, fully enclosed on three sides with an outlet fully spanning one end of the flume to allow recirculation of water. Following the basic experimental design described by Lazarus (2016), we constructed a topographically uniform, low barrier (0.05 m height x 1 m cross-shore width x 10 m alongshore length) of sorted, medium sand (D50 ~ 0.25–0.5 mm) spanning the long dimension of the flume. Barrier uniformity and reproducibility was achieved by mounting a plywood template of the cross-shore profile to an overhead gantry, and running the template along the length of a loosely shaped barrier. The combination of a spatially extended alongshore dimension and low barrier elevation facilitates, in a given trial, the formation of many overwash sites and corresponding washover deposits (order n ~ 10^1) arrayed along the barrier.

To drive the overwash process, one side of the barrier (the "ocean" side) was gradually filled as a reservoir; discharge into the reservoir was held constant, and inflow was baffled using a box of cobbles. Overwash flow and washover deposition began once the water level in the reservoir exceeded the height of the barrier crest. The receiving side of the barrier (the "back-barrier floodplain" side) was left dry, and overwash flow was allowed to drain away. A trial ceased when sediment transport had effectively ceased (typically ~20–25 mins). The back-barrier floodplain was either left bare, to represent a non-built barrier setting, or was configured with blocks of bricks to represent a built setting. Brick units were gridded into different patterns to represent a range of built fractions, taken as the total footprint area of brick units relative to the total area built (including the open space between brick blocks).

We tested two forcing regimes: one in which overwash flow is driven by still-water levels above the barrier elevation, mimicking barrier inundation (Lazarus, 2016); and one in which overwash flow is driven by wave overtopping. For inundation, inflow into the ocean reservoir was continuous (2.9 Ls^-1) and water allowed to flow freely over the barrier. For wave-driven forcing, the seaward reservoir was filled with water to the height of the barrier crest, and then a small wave paddle (Emriver EM2 wave paddle; ~1.1 s period; ~0.01 m wave amplitude) used to push water over the barrier. The wave paddle was able to drive overwash across approximately 4 m of the barrier at a time; when sediment transport had effectively ceased in one half, the trial was paused, the paddle shifted to face the unworked half of the barrier, and the trail restarted.

The full barrier was scanned before and after a trial (drained) using an overhead-mounted terrestrial laser scanner to generate digital elevation models (resolution to within ~1.5 mm). The raw point-clouds were processed using the in-built software of the FARO laser scanner mounted in the TES. Taking the difference between the resulting digital elevation models to emphasise patterns of accretion, we manually identified and digitized 501 individual washover deposits and measured their morphometric characteristics. Conditions for each experimental trial, along with all of the experimental data, are available from Williams et al. (2022).

REFERENCES

Lazarus, E. D. (2016). Scaling laws for coastal overwash morphology. Geophysical Research Letters, 43, 113–119. https://doi.org/10.1002/2016GL071213

Williams, H. E., Lazarus, E. D., & Goldstein, E. B. (2022) Data and morphometric results from a physical experiment simulating washover deposition [data set]. Zenodo, https://doi.org/10.5281/zenodo.7075282


