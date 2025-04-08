# PTB Diagnostic ECG Database
## Overview
The PTB Diagnostic ECG Database is a well-known dataset collected and maintained by the Physikalisch-Technische Bundesanstalt (PTB) in Germany. It’s commonly used for ECG classification tasks, especially to detect cardiac abnormalities.

## Key Characteristics
1. Total Number of Records: 549 records from 290 subjects
2. Subjects: 290 (including healthy individuals and patients with heart conditions)
3. Leads: 15 per record (standard 12-lead + 3 Frank leads)
4. Sampling Frequency: 1000 Hz
5. Resolution: 16-bit
6. Duration: Varies per record (few seconds to minutes)
7. Data Format: WFDB (WaveForm DataBase)

## Diagnoses Provided
Each record includes annotations by expert cardiologists and often contains one or more diagnoses:
- Myocardial infarction (MI)
- Cardiomyopathy
- Bundle branch block
- Dysrhythmia
- Hypertrophy
- Healthy control (normal)
- Other non-cardiac conditions

## Use Cases
The PTB dataset is widely used in:
- ECG signal classification
- Myocardial infarction detection
- Deep learning on physiological signals
- Medical diagnostics and research

## Source:
https://www.physionet.org/physiobank/database/ptbdb/
