# Momentum Data Vitiligo codelists
Codelists from Momentum Data, utilised for the study titled: *"Healthcare disparities in vitiligo: a population-based cohort study in the UK"*. 

## Quality control
All the codelists utilised for data extraction underwent the rigorous quality control process utilised by Momentum Data for multiple real world evidence studies. This process consisted of manual code list generation by a coding expert with a clinical background. The list was then independently reviewed by a second coding expert. The lists then went through an automated quality control process to identify any potential formatting errors or coding inconsistencies. During the data extraction process, high frequency codes were independently reviewed by a third reviewer to ensure that the most commonly used codes correctly match the clinical entity they are being used to identify. A fourth quality control step looks for overlap between code or case definitions where multiple definitions are possible e.g., biochemical disease markers and clinical diagnosis codes for a condition. Finally once variables were generated, the frequency and pattern of variable prevalence was compared with known data from previous analysis in other independent datasets and published literature. Any inconsistencies were reviewed and investigated as appropriate. 

## Algorithms for identification

### Vitiligo
1. Any individual with a [vitiligo specific diagnosis code](https://github.com/MomentumData/Vitiligo-Codelists/blob/main/momentum_codelists_vitiligo)
2. No diagnosis code for an [alternative depigmenting disorder coded](https://github.com/MomentumData/Vitiligo-Codelists/blob/main/momentum_codelists_vitiligo_exclusion) within a one-year period.

### Depression
 - Any coded [depressive episode](https://github.com/MomentumData/Vitiligo-Codelists/blob/main/momentum_codelists_depression.txt) **AND** [concurrent treatment for depression](https://github.com/MomentumData/Vitiligo-Codelists/blob/main/momentum%20_codelists_depression_treatment.txt).
 - Any coded [depressive episode](https://github.com/MomentumData/Vitiligo-Codelists/blob/main/momentum_codelists_depression.txt) **AND** [current treatment for depression](https://github.com/MomentumData/Vitiligo-Codelists/blob/main/momentum%20_codelists_depression_treatment.txt).
 - Any code for [recurrent depressive disorder](https://github.com/MomentumData/Vitiligo-Codelists/blob/main/momentum_codelists_depression.txt).

### Anxiety
 - Any coded [anxiety episode](https://github.com/MomentumData/Vitiligo-Codelists/blob/main/momentum_codelists_anxiety.txt) **AND** [concurrent treatment for anxiety](https://github.com/MomentumData/Vitiligo-Codelists/blob/main/momentum_codelists_anxiety_treatment.txt).

### Depression or anxiety
 - Composite of anxiety and depression outcomes. Any valid identification of depression or anxiety outcomes above.

### Sleep disturbance
 - Any coded [sleep disturbance](https://github.com/MomentumData/Vitiligo-Codelists/blob/main/momentum_codelists_sleep_disturbance.txt) event.

### Mental health referral
 - Any coded [CBT (Cognitive Behavioural Therapy), counselling, IAPT (Improving access to psychological therapies), psychiatry review or psychotherapy](https://github.com/MomentumData/Vitiligo-Codelists/blob/main/momentum_codelists_mental_health_referrals.txt) event.

### Primary care encounters
 1. Identified from occurence of a recorded primary care interaction.
 2. An interval of one day between interactions is required to be counted towards the number of primary care interactions.

### Dermatology referral
 - Any coded [specialist dermatology referral or specialist dermatology review](https://github.com/MomentumData/Vitiligo-Codelists/blob/main/momentum_codelists_dermatology_referrals.txt).

### Time-off work
 - Any coded [issue of a Med 3 certificate of fitness for work](https://github.com/MomentumData/Vitiligo-Codelists/blob/main/momentum_codelists_time_off_work.txt) - indicating time off work for illness or other evidence.

### Unemployment
 - Any coded [unemployment](https://github.com/MomentumData/Vitiligo-Codelists/blob/main/momentum_codelists_unemployment.txt).
