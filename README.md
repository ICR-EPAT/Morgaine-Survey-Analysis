# Morgaine-Survey-Analysis
Morgaine Stiles - Survey analysis

Fields to clean & tidy:
- NCT/ISRCTN Number
- Funding type: E.g "Individual" -> Other, "Private" -> Industry, "Government" -> Non-industry, *Blank* -> "Missing" etc.
- Trial design: Only interested in the 'Allocation' & 'Intervention model' for CTGOV, ISRCTN is free text so try and discern the same information into categorical bins.
- Intervention type: 'Biological' -> IMP, 'Drug' -> IMP, 'Dietary supplement' -> Supplement, 'Behavioural' -> Behavioural, 'Combination' -> Combination, 'Device' -> Device, 'Procedure' -> Procedure/Surgery
- Protocol/SAP: Check website for included protocol & SAP, when combined into the same document use "Combined"
- Trial Phase: Format ISRCTN trials into the CTGOV format.
- Sponsor type: Re-label 'Industry' or 'Non-industry'

#########################################################################################################

Intervention type field/s coding:

Fields broken down: Intervention_type 2 = Main intervention category, INT1-6 = Individual interventions listed 

'IMP'' <- "Biological', "Drug", "Standard Care", "IMP", "Vaccine", "Antibiotics", " Anti-viral agents", " Anti-fungal agent", "Anti-emetics"

'Supplement' <- "Supplement", "Dietary supplement"

'Behavioural' <- "Behavioural", "Behaviour" 

'Procedure/surgery' <- "Procedure", "Radiation", "Bone Marrow Transplant", "Vanicream Gentle Facial Cleanser", "EltaMD UV Daily Broad-Spectrum SPF 40", "EltaMD PM Therapy Facial Moisturizer", " Vanicream Lite Lotion", "Biopsy", "Diagnostic Test", "Vestibular Socket Therapy", "Connective tissue graft", 

'Other' <- "Placebo", "ISA 51D", "Saline", "Supported Care", "Best Supportive Care", "Best Practice", "Quality-of-Life Assessment", "Questionnaire Administration", "Eye Patch"

'Device' <- "Device", "Accupuncture therapy", "Implant", 



