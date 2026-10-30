# Reproducibility and editorial notes

## Evidence used

The original 22-slide presentation documents the study area, source layers, preprocessing, grid selection, component indicators, weights and map results. Course handouts describe general polygon, raster and Shannon diversity workflows. They do not establish that every suggested tool or setting was used in this specific project. The two uploaded raster handouts contain the same extracted text and were treated as one methodological source.

## Useful additions if available

- An ArcGIS Pro project/package with repaired relative paths and shareable inputs.
- A data manifest listing download dates, dataset editions, source URLs and licence conditions.
- The project CRS, raster resolution/alignment and NoData handling.
- Definitions and formulas for all component indices, including LSI.
- Indicator normalisation, class thresholds and aggregation formulas.
- Full-precision AHP matrix and consistency calculations.
- Hot Spot tool settings and Kernel Density inputs, bandwidth and output cell size.
- Exported grid attributes (GeoPackage or CSV) and original high-resolution map layouts.

Do not add empty code folders just to make the repository look like a software project. An ArcGIS analysis is appropriately documented with maps, methods, results and supporting project files.

## Corrections to consider in a revised presentation

1. Slide 16: CR = 0.03 implies CR < 0.10, not CR > 0.10.
2. Slide 6: verify the attribution of CORINE Land Cover 2018 against the original source metadata; “ESA” may not correctly identify the dataset provider.
3. Slide 7: distinguish visually assessed distribution shapes from a formal normality test.

The original PDF in this repository has not been edited. No numerical GIS analysis was rerun. The two class-area columns were checked to total 100 km²; the differences and combined high/very-high areas in the README were calculated from the presented values.
