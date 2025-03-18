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
