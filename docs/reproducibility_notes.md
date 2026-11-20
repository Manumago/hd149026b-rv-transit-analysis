# Reproducibility and source notes

This repository currently preserves an eight-page academic report and its six embedded figures. **No original Python code or observational data files were included in the source material provided for this repository.** Therefore, it should not be described as a fully reproducible pipeline.

## Report sections represented here

- Pages 2–3: velocity, transit, and habitable-zone equations.
- Page 4: Lomb–Scargle periodogram and phase-folded radial-velocity fit.
- Page 5: transit photometry and fitted transit light curve.
- Page 6: habitable-zone figure and results.

## Matters to revisit when the code is available

- Confirm the provenance of all photometric observations. The report mentions TESS light curves and also cites a 2006 source in the transit section; these statements should not be treated as a verified dataset attribution.
- Confirm the reference values and which published study supports each planet parameter.
- Document the fitting method, input uncertainties, units, and error propagation.
- Confirm exact date/year of the project for consistency with the CV; PDF file metadata indicates compilation in 2025, while a previously prepared CV entry listed 2024.
- The habitable-zone analysis examines stellar models, not the potential habitability of the hot planet HD 149026b.

## File handling

- Images in `figures/` were directly extracted from the user-provided PDF; they are not regenerated computations.
- The report is retained unchanged.
- The README's short physical discussion is explanatory and should not be mistaken for original source code.
