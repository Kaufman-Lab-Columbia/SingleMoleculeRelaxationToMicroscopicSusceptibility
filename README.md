# SingleMoleculeRelaxationToMicroscopicSusceptibility

Python/Jupyter tools for transforming single-molecule linear dichroism trajectories into frequency-domain susceptibility spectra.

## Repository Structure

### TimeDomainAnalysisForSusceptibility.ipynb
Compute autocorrelation functions (ACFs), perform single-molecule KWW fitting, and calculate quasi-ensemble (QE) averages.

### FrequencyDomainAnalysisForSusceptibility.ipynb
Transform ACFs into frequency-domain susceptibility spectra and perform Havriliak–Negami (HN) fitting.

### SingleMoleculeKWWSusceptibility.ipynb
Generate susceptibility spectra from single-molecule KWW parameters.

### FreqDomainKWWFit.ipynb
Fit susceptibility spectra directly in the frequency domain using a KWW model.

### NumEvalKWWAndFitFreqDomain.ipynb
Numerically evaluate time-domain KWW decays, transform them into frequency-domain susceptibility spectra, and perform HN fitting.

## Dependencies

- NumPy
- Pandas
- SciPy
- Matplotlib
- Statsmodels
- scikit-learn
- Joblib

## License

Distributed under the MIT License. See the LICENSE file for details.

## Referencing

If you use this repository in published work, please cite:

Citation to be added upon publication.
