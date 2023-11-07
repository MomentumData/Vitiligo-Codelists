# Momentum Data Vitiligo codelists
OPCRD codelists from Momentum Data, utilised for the study titled: *"Healthcare disparities in vitiligo: a population-based cohort study in the UK"*. 

## Data sources
The OPCRD is a well established primary care network in the UK. The database contains complete data on all events and clinical entities coded in UK primary care. These include sociodemographic factors and demographic information, clinical diagnoses, laboratory test results, primary care issued prescriptions, process of care codes (e.g, specialist dermatology reviews), and anthropometric measurements (e.g. BMI), and are coded using the Read coding and Systemized Nomenclature of Medicine - Clinical Terms (SNOMED CT) coding systems.

## Quality control
All the codelists utilised for data extraction underwent the rigorous quality control process utilised by Momentum Data for multiple real world evidence studies. This process consisted of manual code list generation by a coding expert with a clinical background. The list was then independently reviewed by a second coding expert. The lists then went through an automated quality control process to identify any potential formatting errors or coding inconsistencies. During the data extraction process, high frequency codes were independently reviewed by a third reviewer to ensure that the most commonly used codes correctly match the clinical entity they are being used to identify. A fourth quality control step looks for overlap between code or case definitions where multiple definitions are possible e.g., biochemical disease markers and clinical diagnosis codes for a condition. Finally once variables were generated, the frequency and pattern of variable prevalence was compared with known data from previous analysis in other independent datasets and published literature. Any inconsistencies were reviewed and investigated as appropriate. 

## Algorithms for identification

### Vitiligo
 - Any individual with a [vitiligo specific diagnosis code](https://github.com/MomentumData/Vitiligo-Codelists/blob/main/momentum_codelists_vitiligo)
 - No diagnosis code for an [alternative depigmenting disorder code](https://github.com/MomentumData/Vitiligo-Codelists/blob/main/momentum_codelists_vitiligo_exclusion)ed within a one-year period.
