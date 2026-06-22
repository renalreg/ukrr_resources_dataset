# Changelog

## 5.2 - 2026-06-09
### Details of changes can be found in the UKRR DataSet Amendments.xlsx
### Added
- Renal diagnosis tab and Comorbidities tab
	> Reinstated from v4: ERFAJ, ERF07, ERF09, COM71, COM72, COM81, COM82, COM83; Added: ERFAK, ERF92, ERF93
- Frailty score, Observation tab
### Changed
- Lab Results tab
	> QBLAP, QBLAR, QBLE5, QBLE4, QBLJJ, QBLC1, QBLC3, QBLJN - Units of measure added; QBLF3 - Item description changed from 'Transferrin saturation' to 'Transferrin saturation percentage'
- Codelists tab
	> Added items to RR1 - Hospital Sites, RR2 - Access Type, RR22 - Medication Route, RR23 - Medication Units
### Removed
- Diagnoses tab
	> DXS (Diagnoses) block removed, items moved to the ERF (Renal diagnoses) and COM (Comorbidities) blocks
 - PV data items tab
 - Lab Results tab and Observations tab
	> Ranges removed

## 5.1.1 - 2024-08-12
### Added
- RR7 Code 300 for "Transplant; Donation after Brainstem Death (DBD)".
	> This is to support RADAR and not intended for submission.

## 5.1.0 - 2024-08-12
### Changed
- Document Structure Update
	> The document has been tidied and certain bits of text made clearer. The dataset is unchanged.
- CodeSets tab, RR23
  	> Codes are all lower-case to match the XML validation
- CodeSets tab, RR23
 	> μ (U+3BC) micrograms recoded to ug
- Lab Results tab
	> Amend text: Please check regularly to avoid patient Identifiable words appearing in text results
- Lab Results tab, QBLGG
	> Amend text: Kt/V measured by a haemodialysis machine" to indicate we do not expect a renal computer derived value
- Lab Results tab, QBLHM
	> Amend text: HIV screening test to allow either antigen or combined antigen/antibody test type
- UKRDC7
	> Amend text: CKD5 at the point where the local clinical practice would have been to start RRT if the patient/clinician had chosen that.  In some centres this will be an eGFR cut off, or perhaps symptoms suggestive of ‘ureamia’
- Observations tab, Weight
	> Widened limits, should now accept values as low as 0.5kg for very small infants receiving CVVH
- HD prescription tab, HDP05
  	> Renumber HDP04 to make list consecutive

### Added
- Lab Results tab: Glomerular filtration rate (GFR) predicted by creatinine based formula (CKD-EPI) WITHOUT ethnicity
- Lab Results tab: Glomerular filtration rate (GFR) predicted by creatinine based formula (MDRD) WITHOUT ethnicity
- PV tab
	> All the items currently in PV data set, taken from https://confluence.ukrdc.org/display/UD/PV+XML+to+UKRDC+RDA+XML+Mapping on 17Nov21 14:30, Items sorted in Alphabetic order
   

### Deleted/depreciated
- Lab Results tab, QBLGQ
  	> IgM antibodies for covid are unlikely to be tested
- UKRDC7, All transfers
	> All of the transfers in on…. are depreciated as they are not present in the XML schema.  Local centres can still use such codes if they wish (locally), and at the UKRR we may well still generate them to help in some types of ‘life-course’ analysis
- UKRDC7, 80
	> Not usable for national audit comparisons as use very varied
- HD prescription tab, HDP03
  	> Duplicate

## 5.0.0 - 2024-05-05
### Added
- Initial Version
	> This is the version of the document that was distributed to sites/suppliers post-Consultation.

