---
# MIOP terms
methodology_category: Omics Analysis
project: NOAA Pacific Marine Environmental Laboratory Ocean Molecular Ecology Program Protocols
purpose: Qubit assay [NCIT:C183239]
analyses: Qubit assay [NCIT:C183239]
geographic_location: 'North East Pacific Ocean [GAZ:00013765], Bering Sea [GAZ:00008990], Arctic Ocean [GAZ:00000323]'
broad_scale_environmental_context: marine biome [ENVO:00000447], marine photic zone [ENVO:00000209]
local_environmental_context: oceanic epipelagic zone biome [ENVO:01000035], marine benthic biome [ENVO:01000024]
environmental_medium: sea water [ENVO:00002149], tissue [UBERON:0000479], planktonic material [ENVO:01000063]
target: DNA [NCIT:C449]
creator: Shannon Brown, Han Weinrich, Kenna Dailey
materials_required: 
skills_required: sterile technique, pipetting skills, standard molecular technique
time_required: 180
personnel_required: 1
language: en
issued: 2025-06-04
audience: scientists
publisher: NOAA Pacific Marine Environmental Laboratory Ocean Molecular Ecology Group; University of Washington Cooperative Institute for Climate, Ocean, & Ecosystem Studies
hasVersion: 1
license: CC0 1.0 Universal
maturity level: mature

# FAIRe terms
concentration_method: Qubit 4.0 Fluorometer (Invitrogen)
---

# NOAA PMEL OME Qubit Quantification Protocol

## PROTOCOL INFORMATION

### Minimum Information about an Omics Protocol (MIOP)

- MIOP terms are listed in the YAML frontmatter of this page.
- See [MIOP_definition.md](https://github.com/BeBOP-OBON/0_protocol_collection_template/blob/main/MIOP_definition.md) for list and definitions.

### Making eDNA FAIR (FAIRe)

- FAIRe terms are listed in the YAML frontmatter of this page.
- See <https://fair-edna.github.io/download.html> for the FAIRe checklist and more information.
- See <https://fair-edna.github.io/guidelines.html#missing-values> for guidelines on missing values that can be used for missing FAIRe or MIOP terms.

### Authors

- All authors known to have contributed to the preparation of this protocol, including those who filled in the template.
- Visit https://orcid.org/ to register for an ORCID.
- Date is the date the author first worked on the protocol.

| PREPARED BY | AFFILIATION | ORCID | DATE |
| ------------- | ------------- | ------------- | ------------- |
| Shannon Brown | Ocean Molecular Ecology, NOAA PMEL & UW CICOES  | 0000-0001-9808-2638 |2025-05-22|
| Han Weinrich  | Ocean Molecular Ecology, NOAA PMEL & UW CICOES  | 0009-0007-6063-0986 |2025-05-22|
| Mckenna Dailey  | Ocean Molecular Ecology, NOAA PMEL & UW CICOES  | 0009-0008-5542-5336 |2025-05-22|

### Related Protocols

- This section contains protocols that should be known to users of this protocol.
- Include the link to each protocol.
- Include the version number and release date (if available).
- Internal/External: "Internal" are derivative or altered protocols, or other protocols in this workflow. "External" are protocols from manufacturers or other groups.

| PROTOCOL NAME | LINK         | VERSION      | RELEASE DATE | INTERNAL/EXTERNAL |
| ------------- | ------------ | ------------ | ------------ | ----------------- |
| NOAA PMEL OME Extraction Protocol for Sterivex Using a Centrifuge|https://github.com/marinednadude/NOAA-PMEL-OME_Extraction_Protocol_Sterivex_Centrifuge/blob/main/NOAA-PMEL-OME_Extraction_Protocol_Sterivex_Centrifuge.md |1.1.1| 2025-02-20 | Internal|
  | Qubit™ 4 Fluorometer User Guide| [MAN0017209_Qubit_4_Fluorometer_UG](https://assets.thermofisher.com/TFS-Assets/LSG/manuals/MAN0017209_Qubit_4_Fluorometer_UG.pdf) | D.0   | 2021-10-20     |External|


### Protocol Revision Record

- Version numbers start at 1.0.0 when the protocol is first completed and will increase when changes that impact the outcome of the procedure are made (patches: 1.0.1; minor changes: 1.1.0; major changes: 2.0.0).
- Release date is the date when a given protocol version was finalised.
- Description of revisions includes a brief description of what was changed relative to the previous version.

| VERSION | RELEASE DATE | DESCRIPTION OF REVISIONS |
| ------------- | ------------- | ------------- |
| 1.0.0 | 2025-06-04 | Initial release |

### Acronyms and Abbreviations

| ACRONYM / ABBREVIATION | DEFINITION |
| ------------- | ------------- |
|BR | Broad Range|
|CICOES|  Cooperative Institute for Climate, Ocean, and Ecosystem Studies|
| DNA | Deoxyribonucleic acid  |
|dsDNA| Double-stranded DNA|
|eDNA|Environmental DNA|
|EtOH| Ethanol|
|HS|High Sensitivity|
|NOAA | National Oceanographic and Atmospheric Administration|
|OME| Ocean Molecular Ecology|
|PCR| Polymerase chain reaction|
|PMEL | Pacific Marine Environmental Laboratory|
|PPE| Personal Protective Equipment|
| RNA  | Ribonucleic acid  |
|UV| Ultraviolet (light) |
|UW |University of Washington|

### Glossary

| SPECIALISED TERM | DEFINITION |
| ------------- | ------------- |
| Fluorometer | Instrument measuring the fluorescence emitted from a sample after illumination wth a specific wavelength of light|


## BACKGROUND

This document outlines the protocol for Qubit quantification of double-stranded DNA in an extraction product.

### Summary

The Invitrogen Qubit Fluorometer accurately and quickly measures the concentration of DNA, RNA, or protein in a single sample. OME utilizes this protocol to quantify the DNA concentration of our samples before PCR amplification.


### Method Description and Rationale

The Qubit fluorometer quantifies PCR products by measuring fluorescence emitted from DNA-binding dyes that are specific to double-stranded DNA. These dyes bind selectively to double-stranded DNA and emit fluorescence proportional to the DNA concentration when excited by a specific wavelength of light. 

### Spatial Coverage and Environment(s) of Relevance

This protocol has been used to quantify DNA concentrations from a variety of sources, including tissue and eDNA from ethanol in plankton jars and filtered water samples.

### Personnel Required

One person with molecular biology experience.

### Safety

This protocol does not involve any hazardous chemicals, although standard precautions, including wearing PP,E should be taken to avoid skin and eye exposure to chemical reagents.

### Training Requirements

Molecular biology training (including, at a minimum, sterile technique and pipetting small volumes) is required to conduct this protocol.

### Time Needed to Execute the Procedure

Quantifying 96 samples takes around 3 hours (180 minutes), including buffer mixture preparation and DNA sample addition.

## EQUIPMENT

- Description: E.g., "filter".
- Product Name and Model: Provide the official name of the product.
- Manufacturer: Provide the name of the manufacturer of the product.
- Quantity: Provide quantities necessary for one application of the standard operating procedure (e.g., number of filters).
- Remark: For example, some of the consumables may need to be sterilized, some commercial solutions may need to be diluted or shielded from light during the operating procedure.

For 96 samples using 2 μL of sample DNA extract each:

| DESCRIPTION | PRODUCT NAME AND MODEL | MANUFACTURER | QUANTITY | REMARK |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| **Durable equipment** |
|Pipetter: 1-10 μl|Pipetman P10L | Gilson | 1| Can be substituted with any accurate pipettor|
|Pipetter: 100-1000 μL|Pipetman P1000| Gilson| 1 | 	Can be substituted with any accurate pipettor|
| Mini-centrifuge | Personal mini centrifuge | 	BioExcell | 1 | Can be substituted with a generic, but needs to fit 0.5 mL tubes |
| Vortex | Analog vortex mixer | Fisher Scientific | 1 | Can be substituted with generic |
Wash bottles|Safety wash bottle 500 mL for ethanol and bleach | VWR| 2 | Can be substituted with generic, but recommend different colored bottles for each reagent. Must be sterilized before use|
|Qubit| Qubit 4 Fluorometer | Invitrogen | 1| Can be substituted with different Qubit model|
|0.5 mL tube rack|96-Well Flipper™ Microtube Racks |Fisher Scientific | 3 |Can be substituted with generic, must fit 0.5 mL tubes|
| 4-way tube racks | 4-way interlocking tube rack| Cole-Parmer | 1 | Can be substituted with generic, must fit 50 mL tubes |
| **Consumable equipment** |
| Lab notebook  | | Generic     | 1  | Dedicated to the lab space |
| Kimwipes  | Delicate task wipes   | Kimtech     |  5 wipes   | Can be substituted with generic; must be lint-free     |
| Nitrile gloves   | Powder free nitrile gloves  | Fisher Scientific    |  2 pairs    |   Can be subsituted with generic nitrile gloves    |
| 200 μL pipette tips | TipOne RPT filter tips 200 μL graduated    | USA Scientific   | 4  |  Can be subsituted with generic; must be sterile and filtered|
| 10 μL  pipette tips  | TipOne RPT filter tips 10 μL graduated | USA Scientific     |  98  |  Can be subsituted with generic; must be sterile and filtered     |
| Writing utensils | Sharpies and pen | Generic | 2  | Dedicated to the lab space |
| 50 mL falcon tube | Falcon® Conical Centrifuge Tube | Corning | 1 |Can be substituted with sterile and DNA-free generic |
| Qubit tubes | Qubit™ Assay Tubes 500 μL | Invitrogen |98 | Must be qubit specific |
**Optional Equipment**||||
|BioSafety II cabinet|Biological safety cabinet (INT-1100A2)|Kewaunee|1|Can be substituted with generic; internal UV light required.|
| UV crosslinker | UV crosslinker AH (115V), 234100 | Boekel Scientific  | 1 | Recommended not required; can be substituted. |
| **Chemicals** |Choose **one** set of reagents - either Broad Range (BR) or High Sensitivity (HS) kit|
| High Sensitivity kit | **For DNA concentrations 0.005 to 120 ng/μL** | |  |  |
| HS iQuant buffer | Qubit dsDNA HS (High Sensitivity) Assay Buffer | Invitrogen |19900 μL | |
| HS iQuant dye reagent| Qubit dsDNA HS (High Sensitivity) Assay 1:200 reagent | Invitrogen |100 μL |   |
| HS standard 1| Qubit™ dsDNA HS (High Sensitivity) standard 1 | Invitrogen |10 μL |   Keep in fridge |
| HS standard 2| Qubit™ dsDNA HS (High Sensitivity) standard 2 | Invitrogen |10 μL | Keep in fridge |
| **OR** - Broad Range kit | **for DNA concentrations 0.2 to 2,000 ng/μL** | |  |  |
|   BR iQuant buffer | Qubit dsDNA BR (Broad Range) Assay Buffer | Invitrogen| 19900 μL | | 
|BR iQuant dye reagent | Qubit dsDNA BR (Broad Range) Assay 1:200 reagent | Invitrogen |100 μL |   |
| BR standard 1| Qubit™ dsDNA BR (Broad Range) standard 1 | Invitrogen |10 μL |   Keep in fridge|
| BR standard 2| Qubit™ dsDNA BR (Broad Range) standard 2 | Invitrogen |10 μL |   Keep in fridge |
| 70% EtOH | Molecular grade ethanol | Generic | 20 mL |  |
| 10% bleach | Hypochlorite bleach | Clorox | 10 mL | Remake every ~5 days as bleach decomposes quickly at 10% concentration |

## STANDARD OPERATING PROCEDURE

### Preparation

1. Sterilize workspaces and durable equipment, including pipettes and all surfaces, with 10% bleach. Then wipe down all surfaces and equipment with 70% EtOH. For low concentration samples or samples especially sensitive to contamination, Qubit quantification should be carried out inside a BioSafety II cabinet if one is available. Run the cabinet UV regularly and keep internal surfaces clean.

2. If you have a UV crosslinker available, UV pipettes and tube racks regularly for 2 minutes.
3. Set up the required number of Qubit tubes for standards and samples in a 0.5 mL tube rack. Both the dsDNA BR and HS kits require two standards. For 96 samples + 2 standards, you will need 98 tubes. Label the tops if each tubes with sample names or standard abbreviations (S1 or S2). **Do not label the side of the tube, as this will interfere with the sample read.**

4. Use the reagent calculator on the Qubit to determine the composition of your working solution (i.e., iQuant BR/HS buffer and iQuant dye reagent). The dye should be mixed into the buffer at a 1:200 ratio. Use a sterile plastic tube (50 mL falcon tube for 96 samples, smaller tube for fewer samples. **Do not mix in a glass container**) to prepare the working solution. Mix the working solution by vortexing or inverting. Take standards 1 and 2 out of the fridge and allow them to warm to room temperature.

5. Add 190 μL of working solution to the qubit tubes labeled S1 and S2, then 198 μL in each of the sample tubes (if you are planning to add 2 μL of DNA per sample).

6. Vortex and spin down the sample DNA in a mini-centrifuge before adding to the qubit tube.

7. Add 10 μL of standard 1 to the S1 tube and 10 μL of standard 2 to the S2 tube. Add 2 μL of DNA into each sample tube. Mix the qubit tubes by vortexing and spinning down on the mini-centrifuge.

**WARNING**: Qubit tube will break if spun down for more than 3-4 seconds at a time or if the caps are not securely snapped in place. **SPIN WITH CAUTION**.

8. Allow all tubes to incubate at room temperature for 5 minutes before quantifying. Once DNA is added to the buffer, it can sit for < 3 hours.

### Quantification

1. On the home screen of the Qubit, click dsDNA. Then click dsDNA BR or HS, depending on which kit you used.
2. The “read standards” screen will be displayed. Press Read Standards to proceed. Wipe down S1 tube with kimwipe and insert it into the sample chamber, close the lid, then press read standard. When the reading is complete (~3 seconds), remove S1. Repeat the same process with S2 for the standard 2 reading.

3. Press run samples. On the assay screen, select 2 μL and then set the units to ng/μL.
4. Wipe down the sample tube with kimwipe and insert into the sample chamber, close the lid, and read tube. The instrument displays the results on the assay screen. The top value (in large font) is the concentration of the original sample. The bottom value is the dilution concentration. Make sure the chamber door is closed when sample reading is underway. Repeat until all samples are quantified.

### Basic Troubleshooting Guide

**Issue 1**: Out of range - too high

**Solution**: First, re-run the tube to verify it was a reading error. If still out of range, if not currently using a BR kit, re-run the sample with those reagents. If already using the BR kit, recommend re-pipetting the sample and running again.

**Issue 2**: Out of range - too low

**Solution**: First re-run the tube to verify it was a reading error. If still out of range, if not currently using a HS kit, re-run the sample with those reagents. If already using the HS kit, recommend re-pipetting the sample and running again.
