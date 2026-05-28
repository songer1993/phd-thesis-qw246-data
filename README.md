# PhD Thesis Research Data
## Enhancing Virtual Reality Interactions through Force Feedback: Perception, Tools, and Therapeutic Applications

**Author:** Qisong Wang  
**Institution:** Department of Engineering, University of Cambridge  
**Thesis Year:** 2025  
**Contact:** [qw246@cam.ac.uk](mailto:qw246@cam.ac.uk)

## Overview

This repository contains anonymised participant-level datasets from three studies investigating force feedback in virtual reality environments. The data supports the findings presented in the PhD thesis titled "Enhancing Virtual Reality Interactions through Force Feedback: Perception, Tools, and Therapeutic Applications."

## Dataset Structure

### 1. jnd/
**Just Noticeable Differences in Virtual Stiffness Perception**
- `DEMO.csv`: Demographic information for 24 recruited participants
- `NASATLX.csv`: NASA Task Load Index scores for both reference conditions  
- `PARTICIPANT_TRIALS.csv`: Trial-by-trial stiffness discrimination data
- `index.csv`: Study metadata and experimental parameters

**Reported thesis/publication findings:** Weber fractions of 48.1% (low reference) and 26.3% (high reference), based on 23 analysed participants after one outlier exclusion.

### 2. virtual_tools/
**Tool-Mediated Virtual Grasping with Force Feedback**
- `DEMO.csv`: Demographic data for 52 participants
- `PARTICIPANT_TRIALS.csv`: Trial-level task summaries with mass condition, attempt durations, task completion time, and error count
- `NASATLX.csv`: Workload assessment data
- `EXPERIENCE.csv`: User experience questionnaire responses
- `index.csv`: Study metadata and experimental parameters

**Reported thesis findings:** Force feedback reduced normalised grip force by 12.0-13.2% across object masses. The CSV files here contain task summaries and questionnaire responses, not raw force-profile time series.

### 3. rehabilitation/
**Playful Rehabilitation using VR and Force Feedback**

**Study 1 (n=7):**
- `S1 - DEMO.csv`: Participant demographics
- `S1 - ATTITUDES1.csv`: Pre-study attitude assessments
- `S1 - ATTITUDES2.csv`: Post-study attitude assessments
- `S1 - EXPERIENCE1.csv`: Subtask 1 experience ratings
- `S1 - EXPERIENCE2.csv`: Subtask 2 experience ratings
- `S1 - EXPERIENCE3.csv`: Subtask 3 experience ratings
- `S1 - SSQ.csv`: Simulator Sickness Questionnaire results

**Study 2 (n=14):**
- `S2 - DEMO.csv`: Participant demographics
- `S2 - ATTITUDES1.csv`: Pre-study attitude assessments
- `S2 - ATTITUDES2.csv`: Post-study attitude assessments
- `S2 - EXPERIENCE1.csv`: Subtask 1 experience ratings
- `S2 - EXPERIENCE2.csv`: Subtask 2 experience ratings
- `S2 - EXPERIENCE3.csv`: Subtask 3 experience ratings
- `S2 - NASATLX.csv`: NASA Task Load Index scores
- `S2 - SSQ.csv`: Simulator Sickness Questionnaire results
- `index.csv`: Combined study metadata

**Key Findings:** Achieved 8.36/10 playfulness score and 78.6% symptom-free rate

## Data Format

All datasets are provided in CSV format with UTF-8 encoding. Each file includes:
- Header row with variable names
- Internal participant ID coding for linking rows within each study
- Anonymised or pseudonymised participant-level records

## Variable Definitions

Variable names are provided in the CSV header rows and study metadata in each `index.csv`. Detailed methodology and measurement definitions are provided in the associated thesis chapters and Appendix 2.

## Ethics and Data Protection

- Ethics review: Ethics Committee of the Department of Engineering, University of Cambridge.
- Thesis Appendix 2 lists study protocols 20200710 (JND), 20210816 (Virtual Tools), and 20210526 (VR Rehabilitation).
- Participant materials state that anonymised results may be published and presented. Consent forms state that data gathered in the studies may be stored anonymously and securely and used for future research.
- No direct participant identifiers are included in the CSV files.

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
- **Supervisor:** Prof Per Ola Kristensson

## Version History

- v1.1 (2026-05): Corrected ethics reviewer, consent wording, file-description, and force-feedback result summaries.
- v1.0 (2025-09): Initial release for thesis submission

---
*Last updated: May 2026*
