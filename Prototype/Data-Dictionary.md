# Data Dictionary

## Overview

This synthetic dataset illustrates the type of structured clinical information that could be generated through lightweight routine data capture in underrepresented healthcare settings.

The dataset contains synthetic records representing chronic disease patients and is intended solely for demonstrating data structures, reporting workflows, and data quality assessment methods.

## Variables

| Variable          | Description                                    | Type        |
| ----------------- | ---------------------------------------------- | ----------- |
| patient_id        | Unique patient identifier                      | String      |
| sex               | Patient sex                                    | Categorical |
| birth_date        | Date of birth                                  | Date        |
| residence         | Area of residence                              | String      |
| center            | Healthcare facility identifier                 | String      |
| height            | Height (cm)                                    | Numeric     |
| weight            | Weight (kg)                                    | Numeric     |
| bmi               | Body Mass Index                                | Numeric     |
| sbp               | Systolic blood pressure (mmHg)                 | Numeric     |
| dbp               | Diastolic blood pressure (mmHg)                | Numeric     |
| heart_rate        | Heart rate (beats/minute)                      | Numeric     |
| hemoglobin        | Hemoglobin level (g/dL)                        | Numeric     |
| hospitalized      | Hospitalization status                         | Binary      |
| death             | Mortality status                               | Binary      |
| current_treatment | Current treatment category                     | String      |
| disease_group     | Disease category (SCD, Hypertension, Diabetes) | Categorical |

## Intended Use

The variables included in this prototype were selected because they are routinely collected or potentially collectible in many healthcare settings and can support both clinical monitoring and population-level analyses.

No real patient data are included.
