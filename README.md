# Snow Bunting

Compiled site for an animated map of a year of bird migration across the Americas, served with GitHub Pages:
https://khayoon.github.io/snow-bunting/

The map shows 17 species, simulated from eBird reports. Dots scale with population, compressed, so each dot
stands for many birds. Routes between half-monthly distributions are interpolated, not GPS tracks.

## Sources

- Sightings: eBird Observation Dataset, via [GBIF](https://www.gbif.org/dataset/4fa7b334-ce0d-4e88-aaae-2e0c138d049e)
- Populations: Partners in Flight, USFWS, BirdLife, Audubon, Morrison et al. 2006
- Night imagery: NASA, through the `three-globe` package
- Borders and land: Natural Earth, through the `world-atlas` package
- Concept: after Aaron J. Becker's European migration map at mapped.earth
