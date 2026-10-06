# Preterm Birth EHG Paper Reproduction

This repository reproduces the main implementation pipeline of a preterm birth prediction study using Electrohysterogram (EHG) signals.

## Main workflow

EHG records  
→ S2 and S3 signals  
→ Frequency-band filtering  
→ Power spectrum analysis  
→ PF, MF, PA, SE feature extraction  
→ 76-feature matrix  
→ Feature subsets  
→ Sequential Forward Selection  
→ SMOTE  
→ Classification  
→ Performance evaluation

## Project structure

- `notebooks/` - step-by-step implementation notebooks
- `src/` - reusable Python code
- `data/` - dataset locations
- `docs/` - methodology and notes
- `tests/` - validation tests

## Current progress

- [x] Environment setup
- [ ] Dataset exploration
- [ ] Signal construction
- [ ] Filtering
- [ ] Spectrum analysis
- [ ] Feature extraction
- [ ] Feature selection
- [ ] Classification
- [ ] Final evaluation