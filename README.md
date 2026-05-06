Content of the File
The HTML document includes the following sections (each clearly labelled):

Data loading – Reading the raw 30‑run Central Composite Design (CCD) dataset.

Outlier identification and removal – Chemical plausibility screening, Grubbs tests, and justification for excluding 10 runs.

Box‑Cox transformation – Normalisation of the FFA response (λ = −0.1695).

Factor coding – Conversion of natural units to coded variables (A, B, C, D).

Full quadratic model fitting – ANOVA tables for Yield and FFA (initial 14‑term models).

Backward stepwise elimination – Sequential removal of non‑significant terms (α = 0.10).

Exhaustive search for best FFA model – Validation of the final reduced model.

Final reduced model ANOVA – Statistically adequate quadratic models for Yield and FFA.

Regression equations – Coded‑unit equations for both responses.

Diagnostic plots – Residuals vs predicted, normal probability plots (saved as PNG files).

RSM surface plots – 3D and contour plots for key factor pairs (saved as PNG files).

Verification summary – Tabulated fit statistics and model quality assessment.

All code is written in Python 3 and uses standard libraries (pandas, numpy, scipy, matplotlib, sklearn, itertools). The output includes printed console results as well as generated figures.

How to Use This File
Viewing: Open the file in any modern web browser (Chrome, Firefox, Edge, Safari). The HTML is self‑contained – no internet connection is required.

Reproducing the analysis: The code can be copied from the browser into a Jupyter notebook or Python IDE and rerun. However, the original Excel data file (RSM_PFAD_dataset-3 (3).xlsx) is not embedded; the user must have access to the same dataset to replicate the exact results.

Figures: All plots generated during the analysis are embedded within the HTML as PNG images (visible when opened).

Printing: The HTML can be printed to PDF for offline reference or inclusion in an electronic thesis appendix.

File Naming Convention
postsub2.html – named to reflect that it is the second version of the post‑submission analytical output.

Compatibility
Encoding: UTF‑8

Styles: Uses JupyterLab light theme; all CSS is embedded.

Math rendering: MathJax is loaded from CDN, so an active internet connection is required for proper rendering of mathematical notation (e.g., Box‑Cox formulae, regression equations). Without an internet connection, the equations will appear as LaTeX source code.

Dependencies for Re‑running (if extracted)
If you extract the Python code and wish to rerun the analysis locally, you will need:

Python 3.8+

Required libraries: pandas, numpy, scipy, matplotlib, scikit‑learn, openpyxl (for reading Excel files)

The original Excel data file placed at /content/drive/MyDrive/RSM_PFAD_dataset-3 (3).xlsx (or modify the file path in the first code cell).

Citation
If you use this analysis or its outputs in further work, please cite the original thesis:

Akpose, I.O. (2026). Optimization, Production and Characterization of Calcium Metallic Soap from Palm Fatty Acid Distillate: A Response Surface Methodology Approach. M.Sc. Thesis, University of Benin, Nigeria.
