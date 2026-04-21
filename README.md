# Deep mutational scan of the pore of the cold-sensing TRPM8 channel. 
**Computational Analysis of TRPM8 DMS Data:** 

Variant Calling Processing, Lilace Variant Effect Scoring, and VDW Contact Mapping

## Publication
[link]

## Experimental Data
[link]

## Directories

### VCtoLilace
_dmsr1_SMrefFINAL.Rmd_ & _dmsr2_SMrefFINAL.Rmd_

Data processing and manipulation to convert satmut_utils output into format friendly for Lilace

**NOTE:** "NEWRep3" and "Rep4" are equivalent to Replicate 1 and Replicate 2, respectively.
### Lilace
_lilace_working.Rmd_

Generation of variant effect scores via Lilace, produces a pooled score set using read counts aggregated across all replicates, and replicate-specific score sets using read counts from each replicate independently
### ContactMapGeneration
_structural_analysis_C1-O-D.Rmd_, _structural_analysis_julius.Rmd_, _structural_analysis_trpm2.Rmd_, _structural_analysis_trpm4.Rmd_

Calculation of van der Waals (VDW) contacts per analyzed structure using a contact function based on ChimeraX's native "contact" function; visualization of contacts via contact maps and heat maps

Each script is for each set of structures analyzed:

_C1-O-D_:


_julius_:


_trpm2_:


_trpm4_:

