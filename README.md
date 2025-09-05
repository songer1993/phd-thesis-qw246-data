# PhD Thesis Research Data
## Enhancing Virtual Reality Interactions through Force Feedback: Perception, Tools, and Therapeutic Applications

**Author:** Qisong Wang  
**Institution:** Department of Engineering, University of Cambridge  
**Thesis Year:** 2025  
**Contact:** [qw246@cam.ac.uk](mailto:qw246@cam.ac.uk)

## Overview

This repository contains the complete experimental datasets from three studies investigating force feedback in virtual reality environments. The data supports the findings presented in the PhD thesis titled "Enhancing Virtual Reality Interactions through Force Feedback: Perception, Tools, and Therapeutic Applications."

## Dataset Structure

### 1. JND_Study/
**Just Noticeable Differences in Virtual Stiffness Perception**
- `participant_demographics.csv`: Demographic information for 24 participants
- `nasa_tlx_scores.csv`: NASA Task Load Index scores for both reference conditions
- `trial_data.csv`: Complete trial-by-trial stiffness discrimination data
- `psychometric_functions.csv`: Fitted psychometric function parameters

**Key Findings:** Weber fractions of 48.1% (low reference) and 26.3% (high reference)

### 2. Virtual_Tools_Study/
**Tool-Mediated Virtual Grasping with Force Feedback**
- `participant_demographics.csv`: Demographic data for 52 participants
- `trial_performance.csv`: 6,720 trials of task performance data
- `force_measurements.csv`: Grip force measurements across conditions
- `nasa_tlx_scores.csv`: Workload assessment data
- `experience_ratings.csv`: User experience questionnaire responses

**Key Findings:** Force feedback reduced grip force by 4.7-6.2% across tool weights

### 3. VR_Rehabilitation_Study/
**Playful Rehabilitation using VR and Force Feedback**
- `study1_demographics.csv`: Study 1 participant information (n=7)
- `study2_demographics.csv`: Study 2 participant information (n=14)
- `attitude_measures.csv`: Pre/post attitude assessments
- `task_performance.csv`: Performance metrics for three rehabilitation tasks
- `engagement_metrics.csv`: Playfulness and engagement scores
- `ssq_scores.csv`: Simulator Sickness Questionnaire results
- `expert_assessments.csv`: Physical therapist evaluation data

**Key Findings:** Achieved 8.36/10 playfulness score and 78.6% symptom-free rate

## Data Format

All datasets are provided in CSV format with UTF-8 encoding. Each file includes:
- Header row with variable names
- Consistent participant ID coding across files
- Missing data coded as 'NA'
- Timestamps in ISO 8601 format where applicable

## Variable Definitions

Detailed variable definitions and measurement units are provided in `codebook.pdf` within each study folder.

## Ethics and Data Protection

- Ethics approval: UCL Research Ethics Committee (Project ID: 17833/003)
- All data has been anonymized according to GDPR requirements
- Participant consent obtained for data sharing
- No personally identifiable information is included

## Usage and Citation

This data is made available under the Creative Commons Attribution 4.0 International License (CC BY 4.0).

If you use this data in your research, please cite:

```bibtex
@phdthesis{wang2025enhancing,
  author = {Wang, Qisong},
  title = {Enhancing Virtual Reality Interactions through Force Feedback: 
           Perception, Tools, and Therapeutic Applications},
  school = {University of Cambridge},
  year = {2025},
  department = {Department of Engineering}
}
```

## Contact

For questions about the data or collaboration opportunities:
- **Primary Author:** Qisong Wang (qw246@cam.ac.uk)
- **Department:** Department of Engineering, University of Cambridge
- **Supervisor:** [Supervisor name to be added]

## Version History

- v1.0 (2025-09): Initial release for thesis submission

---
*Last updated: September 2025*